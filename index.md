---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: true
---

I recently earned my CompTIA Security+ certification after completing QuickStart’s Cybersecurity Bootcamp, where I gained hands-on experience in network security, system hardening, and vulnerability assessments. My main projects showcase practical skills in virtual network design, threat detection, and penetration testing. Driven by curiosity and a passion for continuous learning, I’ve built an Active Directory home lab to explore endpoint telemetry, threat detection, and adversary simulation using tools like Splunk, Sysmon, and Atomic Red Team. I’m now focused on launching a cybersecurity career where I can apply these skills to protect and defend digital infrastructure.


 <h2 style="text-align:left;"><strong>🔥 Featured Cybersecurity Projects</strong></h2>





### 🎥 Creating a Virtual Network

[![Watch the video](https://img.youtube.com/vi/APskQiKWE8M/hqdefault.jpg)](https://www.youtube.com/watch?v=APskQiKWE8M)

This project demonstrates how to build a segmented virtual network using pfSense, Windows Server, and Ubuntu. Watch the full walkthrough by clicking the image above.





- ### 🔍 Internal Network Vulnerabilities

[![Watch the video](https://img.youtube.com/vi/7aJYZqbF838/hqdefault.jpg)](https://www.youtube.com/watch?v=7aJYZqbF838)

This project showcases a vulnerability assessment within a simulated enterprise network using tools like Nmap, Nessus, and Wireshark. It highlights the discovery of outdated software, weak credentials, and open ports.

- ### 🧠 Pentest Sim CTF

[![Watch the video](https://img.youtube.com/vi/y08Rz5pcZNI/hqdefault.jpg)](https://www.youtube.com/watch?v=y08Rz5pcZNI)

This project walks through a Capture the Flag-style penetration testing simulation. It highlights techniques for discovering vulnerabilities, exploiting misconfigurations, and escalating privileges in a controlled lab environment.



<h2 style="text-align:left;"><strong>🔧 Hands-On Cybersecurity Projects</strong></h2>



### 🧠 Active Directory Home Lab

This project simulates a small enterprise environment with centralized identity management, endpoint telemetry, and threat detection. It integrates Windows Server, Splunk, Sysmon, and Atomic Red Team to demonstrate how security teams monitor and respond to suspicious activity.

### 🎯 Objectives

- Deploy and configure **Active Directory Domain Services (AD DS)**
- Integrate **endpoint logging** with **Splunk** and **Sysmon**
- Simulate adversarial techniques using **Atomic Red Team**
- Analyze telemetry to detect suspicious behavior and validate detection rules

---

### 🛠️ Lab Components

| Component           | Role/Function                                      |
|---------------------|----------------------------------------------------|
| Windows Server      | Domain Controller (AD DS, DNS, DHCP)               |
| Windows 10 Client   | Domain-joined endpoint for telemetry and testing   |
| Splunk              | SIEM platform for log aggregation and analysis     |
| Sysmon              | Endpoint telemetry agent for detailed logging      |
| Atomic Red Team     | Adversary simulation framework (MITRE ATT&CK)      |

---

### 📂 Folder Structure

/active-directory-lab
├── /diagrams
│   └── ad-topology.png
├── /configs
│   ├── sysmon-config.xml
│   ├── splunk-inputs.conf
│   └── atomic-red-team-tests.txt
├── /scripts
│   └── setup.ps1
└── README.md



---

### 📊 Sample Use Cases

- Detect PowerShell execution and lateral movement
- Monitor registry changes and scheduled tasks
- Validate Splunk alerts triggered by Atomic Red Team simulations

---

### 📚 Learning Outcomes

- Understand AD architecture and endpoint integration
- Gain experience with SIEM and telemetry tools
- Practice threat detection and rule tuning using MITRE ATT&CK


  


