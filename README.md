# 🖥️ Cross-Platform OS Utility Tool — Python-Based System Maintenance Suite

_A powerful cross-platform desktop application that performs system cleanup, monitoring, process control, and security scanning across Windows and Linux using a unified Python interface._

---

## Table of Contents
- [Overview](#overview)
- [Project Objective](#project-objective)
- [System Modules](#system-modules)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
- [Key Features](#key-features)
- [Installation & Setup](#installation--setup)
- [Supported Platforms](#supported-platforms)
- [Testing Results](#testing-results)
- [Future Enhancements](#future-enhancements)
- [Conclusion](#conclusion)
- [Role & Contribution](#role--contribution)
- [Authors](#authors)

---

## Overview

Modern operating systems require regular maintenance to ensure optimal performance, security, and stability. Most existing utility tools are platform-specific, forcing users to rely on multiple applications.

This project presents a **Python-based Cross-Platform OS Utility Tool** that provides essential maintenance and monitoring features through a single unified desktop interface.

The system demonstrates practical implementation of **Operating System concepts** while maintaining the clean and user-friendly experience.

---

## Project Objectives

The primary goals of this project are:

- Build a unified cross-platform utility tool  
- Automate common system maintenance tasks  
- Provide real-time system monitoring  
- Enable process and disk management  
- Integrate built-in security scanning  
- Demonstrate core Operating System concepts  
- Deliver a user-friendly desktop GUI  

---

## System Modules

The application is organized into modular components:

- **OS Detection Module** — Identifies Windows or Linux environment  
- **Command Runner** — Executes platform-specific commands  
- **File Cleanup Module** — Removes temporary and cache files  
- **Process Manager** — Lists and terminates processes by PID  
- **Disk Analyzer** — Monitors disk usage and directories  
- **System Monitor** — Tracks CPU and RAM usage  
- **Network Info Module** — Displays IP and interfaces  
- **Security Scanner** — Integrates the Windows Defender and ClamAV  
- **Startup Manager** — Views startup applications  

---

## Tools & Technologies

- **Python 3.x**  
- **Tkinter (ttk)**  
- **subprocess module**  
- **platform module**  
- **Windows Defender**  
- **ClamAV**  
- **Git & GitHub**

---

## Methodology

### OS Abstraction
The system detects the host operating system using the **platform** module and routes commands accordingly.

### Command Execution
System-level operations are performed using Python **subprocess** module to ensure real interaction with the OS.

### Modular Design
Each feature is implemented in separate modules to maintain scalability, readability, and maintainability.

### GUI Implementation
A responsive desktop interface is built using **Tkinter**, ensuring consistent behavior across platforms.

---

## Key Features

-  **File Cleanup** — Removes temporary files, logs, and cache  
-  **Disk Analysis** — Monitors disk usage and directory contents  
-  **Process Management** — View and terminate processes by PID  
-  **System Monitoring** — Real-time CPU and RAM usage  
-  **Network Information** — Displays IP and network interfaces  
-  **Security Scanning** — Integrates Windows Defender and ClamAV  
-  **Startup Manager** — View startup applications  
-  **Cross-Platform Support** — Works on Windows and Ubuntu  

---
## Installation & Setup

### 1. Clone the Repository

``bash
git clone https://github.com/your-username/cross-platform-os-utility-tool.git
cd cross-platform-os-utility-tool
## Supported Platforms

- ✅ Windows 10 and above  
- ✅ Ubuntu 20.04 and above  

---

## Testing Results

- Successful cross-platform execution on Windows and Ubuntu  
- GUI rendered consistently across both operating systems  
- Process termination worked correctly using PID control  
- Security scanners successfully detected potential threats  
- Disk analysis and system monitoring performed accurately  

---

## Future Enhancements

- macOS support  
- Automated task scheduling for cleanup and monitoring  
- Advanced network monitoring and packet inspection  
- Detailed logging and reporting dashboard  
- Performance optimization and background services  

---

## Conclusion

The Cross-Platform OS Utility Tool demonstrates that how Python can be leveraged to build a unified and efficient system maintenance application. By combining OS abstraction, modular architecture, and a user-friendly Tkinter interface, the tool successfully performs essential administrative and monitoring tasks across multiple operating systems. This project highlights the practical application of core Operating System concepts in a real-world utility.

---

## Role & Contribution

- System design and architecture planning  
- OS abstraction implementation  
- GUI development using Tkinter  
- Process and disk management modules  
- Security tool integration  
- Testing and debugging  
- Cross-platform validation  

---

## Authors

**Mian Shakar Afzal**  
**Muhammad Salman**  
**Abdul Mateen Amir**  
**Abdullah**  
**Mohid Asmat**  

**Supervisor:** Ma’am Shanza Zafar

[LinkedIn](https://www.linkedin.com/in/mian-shakar-afzal-959b443a8/) | [GitHub](https://github.com/SHAKAR-AFZAL) | [Email](mailto:mianshakarafzal@gmail.com)
