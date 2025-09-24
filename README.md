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
