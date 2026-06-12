#  Linux Task 01 – Linux Environment Setup & Essential Commands

##  Author

Meghana S

##  Objective

The primary objective of this task is to gain practical experience with the Linux operating system by working in a virtualized environment. This task focuses on understanding Linux terminal operations, filesystem navigation, directory and file management, and system information gathering.

Linux is the backbone of modern Cyber Security, Ethical Hacking, Cloud Computing, and System Administration. Building strong Linux fundamentals is essential for working with security tools, servers, and penetration-testing environments.

---

#  Environment Setup

| Component               | Details                 |
| ----------------------- | ----------------------- |
| Operating System        | Kali Linux              |
| Virtualization Platform | VMware Workstation      |
| Interface               | KDE Desktop Environment |
| Terminal                | Bash Shell              |

---

#  Part A – Linux Installation & Verification

## Installation Summary

Successfully installed Kali Linux on VMware Workstation and verified proper functionality of:

* Desktop Environment
* Terminal Access
* User Account Configuration
* System Information

### Verification Screenshots

* Kali Linux Desktop
  <img width="1280" height="800" alt="screenshots1" src="https://github.com/user-attachments/assets/50b2e94a-0f62-44d4-8e91-03c4a77b00b7" />

* Terminal Window
  <img width="1280" height="800" alt="screenshots2" src="https://github.com/user-attachments/assets/8468c266-2057-496a-927b-fcea4d2fb4dd" />

* System Information
 <img width="1280" height="800" alt="screenshots3" src="https://github.com/user-attachments/assets/c0282ef8-235a-45af-b5d7-fc6a1ab04e3d" />
 

---

#  Part B – Linux Navigation Commands

The following essential Linux commands were executed and analyzed.

| Command    | Description                                          |
| ---------- | ---------------------------------------------------- |
| `pwd`      | Displays the present working directory               |
| `ls`       | Lists files and directories                          |
| `ls -la`   | Displays detailed information including hidden files |
| `cd`       | Changes the current directory                        |
| `clear`    | Clears the terminal screen                           |
| `history`  | Displays previously executed commands                |
| `whoami`   | Displays the currently logged-in user                |
| `hostname` | Displays the system hostname                         |

<img width="1280" height="800" alt="screenshots4" src="https://github.com/user-attachments/assets/fe45c7c2-6469-4abf-a1e1-e04f48d893a4" />


## Key Learning

These commands form the foundation of Linux navigation and are frequently used by:

* Ethical Hackers
* Cyber Security Analysts
* Linux Administrators
* DevOps Engineers

---

#  Part C – Directory Management

Created a structured Cyber Security Lab environment using Linux commands.

## Directory Structure

```text
CyberSecurity_Lab
│
├── Networking
├── Linux
├── CyberSecurity
├── EthicalHacking
└── Reports
```

## Commands Used

```bash
mkdir CyberSecurity_Lab
cd CyberSecurity_Lab

mkdir Networking
mkdir Linux
mkdir CyberSecurity
mkdir EthicalHacking
mkdir Reports

tree
```

## Learning Outcome
Folder Structure Screenshot
<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/2baa4725-7133-4949-a897-abf9925abde6" />

* Directory Creation
* Hierarchical File Structure
* Linux Filesystem Organization
* Path Navigation

---

#  Part D – File Management Operations

Practical file handling operations were performed inside the Linux environment.

## File Creation

```bash
touch notes.txt
touch commands.txt
touch report.txt
```

### Purpose

Creates empty files without opening an editor.

---

## File Copy

```bash
cp notes.txt notes_backup.txt
```

### Purpose

Creates an exact duplicate of a file.

---

## File Rename

```bash
mv report.txt final_report.txt
```

### Purpose

Renames an existing file.

---

## File Move

```bash
mv commands.txt ../Networking/
```

### Purpose

Moves a file between directories.

---

## File Deletion

```bash
rm notes_backup.txt
```

### Purpose

Permanently removes a file.

---

#  Part E – System Information Collection

The following commands were used to gather system information.

```bash
uname -a
hostname
whoami
date
uptime
pwd
```
<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/5208f299-4115-4807-8ccc-70745c250913" />

## Information Retrieved

| Information         | Command Used |
| ------------------- | ------------ |
| Kernel Version      | uname -a     |
| Hostname            | hostname     |
| Username            | whoami       |
| Current Date & Time | date         |
| System Uptime       | uptime       |
| Current Directory   | pwd          |

## Importance in Cyber Security

System enumeration is one of the first steps performed during:

* Vulnerability Assessment
* Penetration Testing
* Incident Response
* Security Auditing

Understanding system information helps security professionals identify operating systems, kernels, and potential attack surfaces.

---

#  Part F – Linux Research Activity

## What is Linux?

Linux is a free and open-source operating system kernel created by Linus Torvalds in 1991. It serves as the foundation for numerous operating systems known as Linux distributions. Linux is widely recognized for its stability, security, flexibility, and performance.

---

## Why is Linux Important in Cyber Security?

Linux plays a critical role in Cyber Security because:

* Most servers run Linux.
* Security tools are primarily developed for Linux.
* Linux provides powerful command-line utilities.
* Security testing environments are Linux-based.
* It offers better control over system resources and permissions.

---

## Linux vs Windows

| Linux                 | Windows                        |
| --------------------- | ------------------------------ |
| Open Source           | Proprietary                    |
| Highly Customizable   | Limited Customization          |
| More Secure by Design | Frequently Targeted by Malware |
| Strong Command Line   | GUI-Centric                    |
| Preferred in Servers  | Popular on Personal Computers  |

---

## What is a Linux Distribution?

A Linux Distribution (Distro) is an operating system built on the Linux kernel combined with additional software, package managers, desktop environments, and utilities.

Examples:

* Kali Linux
* Ubuntu
* Debian
* Fedora
* Parrot OS
* Arch Linux

---

## Why Ethical Hackers Prefer Linux?

Ethical Hackers prefer Linux because it provides:

* Built-in networking tools
* Advanced scripting capabilities
* Powerful command-line environment
* Better resource utilization
* Thousands of security-testing tools
* Greater control over the operating system

Kali Linux, in particular, comes preloaded with hundreds of penetration-testing and forensic tools.

---

# 📚 Skills Acquired

Throughout this task, the following skills were developed:

✅ Linux Installation and Configuration

✅ Terminal Navigation

✅ Directory Management

✅ File Management

✅ Linux Command Usage

✅ System Information Gathering

✅ Basic Cyber Security Concepts

✅ Linux Filesystem Understanding

---

#  Real-World Applications

The concepts learned in this task are directly applicable to:

* Ethical Hacking
* Penetration Testing
* Security Operations Centers (SOC)
* Cloud Administration
* DevOps Engineering
* Linux System Administration
* Digital Forensics

---

# 🏁 Conclusion

This task successfully provided hands-on exposure to the Linux operating system and its command-line environment. By performing navigation, directory management, file manipulation, and system enumeration activities, a solid foundation was established for future Cyber Security and Ethical Hacking tasks.

Linux proficiency is a fundamental skill for every Cyber Security professional, and this task serves as an important first step toward mastering Linux-based security environments.
