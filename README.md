# 🔒 Firewall Rules Lab

This project demonstrates how to configure and test **advanced Windows Firewall rules** as part of cybersecurity training.  
It includes step-by-step tasks, screenshots, and explanations useful for SOC and IT students.

---

## 📖 Objectives
- Understand the basics of Windows Firewall  
- Create inbound and outbound rules  
- Test connectivity before and after applying rules  
- Document results with screenshots and analysis  

---

## 🛠️ Lab Environment
- **Operating System:** Windows 10 (VM in VirtualBox)  
- **Tools:** Command Prompt, PowerShell, GUI Firewall settings  
- **Network Setup:**  
  - PC1 (Lab workstation)  
  - PC2 (Target for ping and file share tests)  

---

## 🔧 Steps Performed
1. **Checked current firewall status** using PowerShell:  
   ```powershell
   Get-NetFirewallProfile
## 📸 Screenshots

### Linux – Default Route
![Default Route](Screenshot%202025-09-23%20132133.png)

### Linux – IP Addresses
![IP Addresses](Screenshot%202025-09-23%20133001.png)

### Linux – Ping Test
![Ping Test](Screenshot%202025-09-23%20133230.png)

### Linux – Ifconfig Output
![Ifconfig](Screenshot%202025-09-23%20133525.png)

### Linux – IP After DHCP
![After DHCP](Screenshot%202025-09-23%20133945.png)

### Windows – IP Configuration
![Windows IP Config](Screenshot%202025-09-23%20134144.png)
