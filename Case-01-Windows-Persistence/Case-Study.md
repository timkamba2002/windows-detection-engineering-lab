
---

## Evidence Gallery (Screenshots)

### Telemetry Setup (Logging Enabled)
![Process Creation + Command Line Logging Enabled](Screenshots/01-ProcessCreation-and-CommandLine-Logging-Enabled.png)

---

### Payload Creation
![Script Creation - updater.ps1](Screenshots/01-Script-Creation-updater-ps1.png)

---

### Persistence Technique: Registry Run Key
![Run Key Added](Screenshots/02-Registry-RunKey-Persistence-Added.png)
![Execution After Login](Screenshots/03-Persistence-Executed-After-Login.png)
![PowerShell Run Key Enumeration](Screenshots/04-Detection-PowerShell-Enumeration.png)
![Run Key Cleaned](Screenshots/05-Registry-RunKey-Cleaned.png)
![Run Key Removed (SOC Cleanup)](Screenshots/SOC-Hunt-RunKey-Removed.png)

---

### Persistence Technique: Startup Folder
![Startup Folder Location](Screenshots/01-Startup-Folder-Location.png)
![Startup Shortcut Created](Screenshots/02-Startup-Shortcut-Created.png)
![Startup Persistence Executed](Screenshots/03-Startup-Persistence-Executed.png)
![Startup Folder Enumeration](Screenshots/04-Detection-Startup-Folder-Enumeration.png)
![Startup Folder Cleaned](Screenshots/05-Startup-Folder-Cleaned.png)

---

### Persistence Technique: Scheduled Task
![Scheduled Task Created + Verified](Screenshots/01-ScheduledTask-Creation-and-Verification.png)
![Scheduled Task Executed](Screenshots/02-ScheduledTask-Persistence-Executed.png)
![Scheduled Task Detection + Execution Details](Screenshots/03-ScheduledTask-Detection-and-Execution-Details.png)
![Scheduled Task Removed + Verified](Screenshots/04-ScheduledTask-Removed-and-Verified.png)

---

### Persistence Technique: Winlogon Userinit
![Userinit Modified (Persistence Added)](Screenshots/02-Userinit-Modified-Persistence-Added.png)
![Userinit Persistence Executed After Login](Screenshots/03-Userinit-Persistence-Executed-After-Login.png)
![Userinit Enumeration (Detection)](Screenshots/04-Detection-Userinit-Registry-Enumeration.png)
![Userinit Restored](Screenshots/05-Userinit-Restored.png)

---

### SOC Investigation Artifacts
![4688 Detection Evidence](Screenshots/SOC-Hunt-4688-RunKey-Persistence-Detected.png)
![File Metadata](Screenshots/Persistence-Hunt-File-Metadata.png)
![Payload Removed](Screenshots/SOC-Hunt-Payload-Removed.png)
![VirusTotal Hash Check](Screenshots/virustotalhash.png)

