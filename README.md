Arch Linux Installation and Configuration  
**CYB 3353 – Project 1 (Part A)**  
**Student:** Karim Haidari  
**Instructor:** Codi west 
**Date:** November 9, 2025  

---

## 🧾 Overview  
This repository documents the complete process of installing and configuring **Arch Linux (ARM64)** in a **QEMU virtual machine**.  
The project was completed as part of **CYB 3353: Linux Fundamentals**, demonstrating understanding of package management, user privileges, shell configuration, and system networking.  

---

## 🖥️ System Configuration  

| Component | Details |
|------------|----------|
| **OS** | Arch Linux ARM aarch64 |
| **Virtual Host** | QEMU (virt-9.1) |
| **Kernel** | 6.17.7-3-aarch64-ARCH |
| **Desktop Environment** | GNOME 49.1 |
| **Shell** | Zsh 5.9 |
| **Theme** | Adwaita GTK2/3 |
| **Terminal** | kgx |
| **CPU** | 4 vCPUs |
| **Memory** | 4 GB (allocated) |
| **AUR Package Installed** | Neofetch |


## ⚙️ Project Components  

###  Part A – Arch Installation & Configuration  
-  Installed Arch Linux base system  
-  Added and configured a **GNOME Desktop Environment**  
-  Created a **sudo user account (`karim`)**  
-  Installed and configured **Zsh shell** with color prompts  
-  Added **aliases** for faster command execution  
-  Installed and enabled **OpenSSH** service  
-  Installed **Neofetch** from the AUR  
-  Connected to the internet (ping test verified)  

 


 Screenshots  
Key screenshots captured during the process are included in the Word report and GitHub repository:  

- Arch login screen  
- Desktop environment after setup  
- Terminal showing Neofetch output  
- Sudoers file configuration  
- IP and user list commands  
- Ping and SSH service confirmation  
- `.zshrc` aliases and color prompt  

---
 Repository Contents  

| File | Description |
|------|--------------|
| **Karim_Haidari_Arch_Linux_Report.docx** | Full installation and configuration documentation |
| **README.md** | Project overview (this file) |
| *(Optional)* `screenshots/` | Folder containing all installation and verification screenshots |

---


Throughout the installation process, I encountered and resolved several challenges:  
- **AUR Signature Verification Error:** Solved by importing the missing GPG key (`46D62DD9F1DE636E`).  
- **Package Not Found (Neofetch):** Resolved by cloning from AUR and compiling manually.  
- **User Privilege Setup:** Configured `wheel` group and verified sudo access through `/etc/sudoers`.  

These steps strengthened my understanding of Linux user permissions, package sources, and system configuration integrity.

---

**Public Repository:**  
👉 [https://github.com/KarimHaidari2/arch-install-karim-haidari](https://github.com/KarimHaidari2/arch-install-karim-haidari)

---

 Conclusion  
This project successfully demonstrates a full Arch Linux installation, customization, and documentation process.  
By completing it, I gained valuable hands-on experience in Linux system management, automation, and virtualization.  
