# 👻 Ghostscan

![Bash](https://img.shields.io/badge/language-bash-blue)
![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-linux-lightgrey)

> Interactive Auto-Reconnaissance Tool for Pentesting Beginners

Ghostscan is a Bash-based tool designed to help beginners perform structured reconnaissance during penetration testing.  
It automates common enumeration tasks and provides guidance on how to proceed based on discovered services.

---

## 🚀 Features

- 🔍 Full port scanning (`nmap`)
- 🧠 Automatic service detection (`-sV -sC`)
- ⚡ Auto-recon mode based on open ports
- 📁 Organized output (per target)
- 🔗 Basic correlation of findings (users, credentials)
- 📢 Verbose output to understand each step

---

## 📦 Requirements

- nmap
- whatweb
- gobuster
- enum4linux
- smbclient
- dig
- netcat

---

## ⚙️ Installation

```bash
git clone https://github.com/Fchazychaz/ghostscan.git
cd ghostscan
chmod +x ghostscan
sudo mv ghostscan /usr/local/bin/


## ⚙️ Usages

ghostscan <IP>
ghostscan <IP> -a
ghostscan <IP> -a -v


## 📂 Output Structure

10.10.10.10/
├── nmap/
├── web/
├── smb/
├── ftp/
├── dns/
├── mail/
├── db/
└── report/


## ⚠️ Disclaimer

This tool is for educational purposes and authorized environments only.
