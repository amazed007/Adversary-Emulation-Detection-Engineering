# Adversary Emulation & Detection Engineering Lab

## Overview

This repository contains my **CSE-802 (Information Security and Cryptography)** assignment on **Adversary Emulation and Detection Engineering**.

The project demonstrates how to build a Security Operations Center (SOC) home lab using Splunk Enterprise, Sysmon, and Atomic Red Team to simulate cyber attacks and detect malicious activities through behavior-based analysis.

---

## Lab Environment

* Oracle VirtualBox
* Windows Server 2019
* Kali Linux
* Splunk Enterprise
* Splunk Universal Forwarder
* Microsoft Sysmon
* Atomic Red Team

---

## MITRE ATT&CK Techniques

The following attack techniques were emulated:

* T1053.005 – Scheduled Task
* T1218.005 – MSHTA
* T1003.001 – LSASS Memory Dumping
* T1059.001 – PowerShell Download Cradle
* T1112 – Registry Modification

---

## Detection

The attacks were detected using:

* Sysmon Event ID 1 (Process Creation)
* Sysmon Event ID 10 (Process Access)
* Sysmon Event ID 13 (Registry Modification)
* PowerShell Event ID 4104 (Script Block Logging)

Detection and analysis were performed using Splunk Search Processing Language (SPL).

---

## Repository Contents

* **README.md** – Project overview
* **cse_802_Assignment.pdf** (or **cse 802 Assignment.docx**) – Complete project report

---

## Author

**Md Abdul Mazed**

* Course: Information Security and Cryptography (CSE-802)
* Department of Computer Science & Engineering
* University of Dhaka

---

## Disclaimer

This project was developed for educational purposes only. All attack simulations were conducted in an isolated virtual laboratory environment.
