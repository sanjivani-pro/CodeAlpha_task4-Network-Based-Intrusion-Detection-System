# CodeAlpha_task4-Network-Based-Intrusion-Detection-System
Network-Based Intrusion Detection System odeAlpha Task 4 – Snort NIDS on Ubuntu (Summary) 🔍 Objective Set up Snort as a Network Intrusion Detection System (NIDS)

Monitor real-time traffic for attacks

Simulate attacks using Kali Linux

Detect and log suspicious activity

⚙️ Setup Steps Installed Snort and Gedit on Ubuntu

Edited snort.conf to set HOME_NET to Ubuntu IP

Verified config using: sudo snort -T -c /etc/snort/snort.conf -i ens33

Ran Snort in live mode: sudo snort -A console -q -u snort -g snort -c /etc/snort/snort.conf -i ens33

💣 Attack Simulation (Kali Linux) Performed Nmap Null Scan: nmap -sN [Ubuntu IP]

Performed Ping Scan: nmap -Pn [Ubuntu IP]

✅ Snort detected and alerted both scans

📁 Files snort.conf (optional) – Config file

screenshots/ – Setup & detection (coming soon)

🧠 What I Learned How to install and configure Snort

Real-time intrusion detection basics

Testing and simulating threats

Reading Snort console alerts

📜 Credits Internship: CodeAlpha

Role: Cybersecurity Intern

Task: 4 – NIDS Setup

Date: June 2025

