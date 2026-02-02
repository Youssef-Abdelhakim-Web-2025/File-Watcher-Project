# FileWatcher PowerShell Script

![PowerShell](https://img.shields.io/badge/PowerShell-blue?logo=powershell&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

It is robust PowerShell script that monitors a folder (and optionally its subfolders) for all file changes in real-time. It logs events such as **file creation, modification, deletion, and renaming** to both the console and a log file.  

This script is perfect for system administrators, developers, or anyone who wants to **track changes in critical directories** for backup, audit, or monitoring purposes.

---

## Features

- Monitor a folder for changes in **real-time**
- Detect file events:
  - **Created** ✅
  - **Modified** ⚠️
  - **Deleted** ❌
  - **Renamed** 🔄
- Optional monitoring of **subdirectories**
- Logs events to a **console with color-coded output**:
  - Green → Created  
  - Yellow → Modified  
  - Red → Deleted  
  - Cyan → Renamed
- Logs events to a **log file** with timestamps
- Easy configuration and setup

---

## Requirements

- Windows with **PowerShell 5.1+**
- Permission to read/write in the monitored folder and log file path

---

## Installation

1. Clone the repository or download the script:

```bash
git clone https://github.com/yourusername/FileWatcher.git
