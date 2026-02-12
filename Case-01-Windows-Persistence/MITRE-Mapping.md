# MITRE ATT&CK Mapping – Case 01: Windows Persistence Techniques

This case study simulated multiple Windows persistence mechanisms and mapped them to the MITRE ATT&CK framework.

---

## Persistence Techniques

### T1547.001 – Registry Run Keys / Startup Folder
- HKCU\Software\Microsoft\Windows\CurrentVersion\Run
- Startup Folder shortcut persistence
- Executed at user logon via explorer.exe

---

### T1053.005 – Scheduled Task / Job: Scheduled Task
- Logon-triggered scheduled task
- Persistence achieved via task scheduler
- Execution context observed in Security Event ID 4688

---

### T1547.004 – Winlogon (Userinit Modification)
- Modified:
  HKLM\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\Userinit
- Appended PowerShell execution
- Triggered during user logon process

---

## Execution Techniques

### T1059.001 – PowerShell
- Used PowerShell to execute script
- Included flag:
  -ExecutionPolicy Bypass
- Detected via Security Event ID 4688 (Process Creation)

---

## Detection & Telemetry Mapping

Primary Log Source:
- Windows Security Log

Key Event:
- Event ID 4688 – Process Creation

Important Fields:
- New Process Name
- Process Command Line
- Creator Process Name
- Subject User Name
- Timestamp

---

## Defensive Insight

This case demonstrates:

- How multiple persistence mechanisms map to ATT&CK persistence tactics.
- How execution techniques (PowerShell) overlap with persistence methods.
- How parent process analysis helps distinguish persistence mechanisms.
