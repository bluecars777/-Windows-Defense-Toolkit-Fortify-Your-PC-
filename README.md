# Windows Defense Toolkit

Fortify your Windows PC in minutes. Enhance security, optimize performance, and protect your system from threats.

---

## Supported Windows Versions
This toolkit is designed and tested for **Windows 10 and Windows 11**.  
⚠️ Older versions may not support some PowerShell cmdlets or security features.

---

## Features

| Feature | Description | Status |
|---------|-------------|--------|
| Automatic Windows Updates | Keep your system patched and secure | ✅ |
| Firewall & Network Hardening | Enable Windows Firewall and block risky connections | ✅ |
| Service Optimization | Disable unnecessary services to reduce attack surface | ✅ |
| Account Hardening | Strengthen user accounts and remove unnecessary admin rights | ✅ |
| Performance Boosts | Minor tweaks for smoother and faster operation | ✅ |
| Advanced Malware Protection | Extra layer of security against threats | ❌ |

---

## Quick Start

1. Clone this repository:
git clone https://github.com/<your-username>/Windows-Defense-Toolkit.git

markdown
Copy code

2. Open PowerShell as Administrator.

3. Navigate to the scripts folder:
cd Windows-Defense-Toolkit/security_scripts

css
Copy code

4. Run a script, for example:
.\enable_firewall.ps1

yaml
Copy code

**Tip:** Always run scripts as Administrator to apply system-level changes.

---

## Included Scripts

All scripts are in the `security_scripts` folder. Users only need to **run the scripts**, no copying of code is required.  

| Script | Description |
|--------|-------------|
| enable_firewall.ps1 | Enables Windows Firewall |
| update_windows.ps1 | Installs the latest Windows updates |
| disable_unneeded_services.ps1 | Disables unnecessary background services |
| user_account_hardening.ps1 | Hardens user accounts and enforces strong password policy |

---

## Target Audience

- Students learning IT and PowerShell scripting  
- IT beginners and enthusiasts  
- Anyone who wants to harden and optimize their Windows 10 or 11 PC  

---

## Disclaimer
This project is for **educational purposes only**. Always back up your system before running scripts. The author is **not responsible** for data loss or system issues.
