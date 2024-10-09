# 🛡️ Cyber Security Portfolio

## Welcome to My Cyber Security Portfolio!

Hello, I'm Daniel O'Rourke, a **Cyber Security Analyst** with over two years of experience in cybersecurity operations, vulnerability analysis, digital forensics, and incident response. This portfolio showcases my expertise in protecting and defending against various cyber threats, as well as my projects, certifications, and tools I've worked with.

---

## Navigation 

[About Me](#-about-me)
[Qualifications](#-qualifications)
[Completed Projects](#-completed-projects)
[Future Projects](#️-cyber-security-projects-on-proxmox)
[Career Goals](#-future-goals)
[Contact](#-lets-connect)
[Achivements](#-achivements)

## 🔐 About Me

- **Role:** Cyber Defense Analyst 

- **Experience:** 
2 years in Cyber Security
14 years in Navy (Communications Technician) 
- **Location:** Perth, Australia
- **Passions:** IoT security, Operational Technology, Smart Automation

---

## 🎓 Qualifications

- **Bachelor of Information Technology (Cyber Security & Digital Forensics) | Murdoch University**
- **Microsoft SC-200 Security Operations Analyst Associate**
- **Diploma of Engineering – Advanced Trade | Royal Australian Navy**
- **Certificate IV in Project Management Practice | Open Colleges**
- **Cyber Security Analyst Certificate | With You With Me**

  
---

## 📜 Certifications

- **Microsoft Certified: Security Operations Analyst Associate (SC-200)**
- **ITIL 4 Foundation** (In progress)
- **Splunk Power User** (In progress)
- **CrowdStrike Responder** (In progress)
- **CompTIA Network+** (In progress)

---

## 🛠️ Skills

- **Security Technologies:** 
  - SIEM (Splunk, Microsoft Sentinel)
  - Endpoint Detection & Response (CrowdStrike, Microsoft Defender)
  - Firewalls, Proxies, Intrusion Detection/Prevention Systems (IDPS)
- **Programming Languages:** Python, C++, SQL, KQL
- **Security Tools:** Netskope, Carbon Black, Mimecast, Cisco Firepower
- **Forensics Tools:** Hex Workshop, FTK, Autopsy
- **Network Technologies:** Cisco Routers, Open-source Firewalls

---

## 🏆 Achivements 
2016 & 2018 Winners Navy Engineering Challenge [videos](https://www.youtube.com/watch?v=RwswUrpT4JA)

---

## 📁 Completed Projects

### 1. **Constructed Home Lab**
   - **Overview:** 
     I designed and implemented a secure and efficient home network, integrating both wired and wireless components. The network is configured to optimize performance and security for various connected devices, including smart home IoT devices, a NAS for storage, and a Proxmox server for virtualization.
   
   - **Key Components:**
     - **Firewall:** PfSence installed on Protectli vault – Acts as the main gateway and firewall for the network.
     - **Switch:** TP-Link TL-SG108E – Provides wired connectivity for critical devices.
     - **Access Point:** Ubiquiti UAP-AC-LR – Extends wireless coverage throughout the home.
     - **Proxmox Server:** Intel NUC – Hosts multiple virtual machines for different network services.
   
   - **Security Features:**
     - Implemented **VLANs** to segregate network traffic between different device categories (e.g., IoT, NAS, workstations).
     - Enabled **WPA3 encryption** for wireless security.
     - Configured **port forwarding** for external access to the NAS, with **dynamic DNS** for seamless connectivity.
   
   - [View Detailed Project](./Home%20Network.md)

---

### 2. **Built Proxmox Server**
   - **Overview:**
     Set up a **Proxmox Virtual Environment** to run multiple virtual machines (VMs) for different purposes, such as security testing, hosting services, and learning about virtualization technologies. The Proxmox server allows efficient use of hardware resources while maintaining flexibility for future network expansion.
   
   - **Virtual Machines Hosted:**
     - **pfSense Firewall:** Provides routing and firewall services for the home network.
     - **Kali Linux:** Used for penetration testing and security research.
     - **Ubuntu Server:** Hosts internal websites and acts as a DNS resolver.
     - **Windows Server 2019:** Used for testing Windows environments and simulating a domain controller.
   
   - **Features:**
     - **Snapshots** for VMs to quickly restore environments.
     - Efficient resource management with **dynamic memory allocation**.
     - Centralized control and monitoring via the Proxmox web interface.
   
   - [View Detailed Project](./Proxmox.md)

---

### 3. **Installed and Configured pfSense Open Source Firewall**
   - **Overview:**
     Installed and configured a **pfSense firewall** to secure the home network and control traffic between different network segments. This open-source firewall provides a range of advanced security features, such as VPN access, intrusion detection, and traffic shaping.
   
   - **Key Features:**
     - **Firewall Rules:** Custom firewall rules were created to block unnecessary incoming traffic and allow safe internal communication.
     - **VPN Setup:** Configured **OpenVPN** to allow secure remote access to the home network.
     - **Traffic Shaping:** Optimized bandwidth allocation to prioritize high-demand applications like streaming and gaming.
     - **Intrusion Detection/Prevention:** Set up **Snort** for real-time traffic analysis and intrusion detection.
     - **Dynamic DNS:** Implemented **Dynamic DNS** to maintain consistent external access to services even with changing IP addresses.
   
   - **Security Measures:**
     - Blocked access to known malicious IP addresses.
     - Encrypted all DNS traffic using DNS over TLS.
     - Implemented **failover mechanisms** for dual-WAN connectivity to ensure uptime.

   - [View Detailed Project](./pfSense.md)


---

## 🛡️ Cyber Security Projects on Proxmox

## 1. Security Incident Investigation and Response

This project involves creating a virtual environment to simulate and respond to various cyber security incidents.

### Overview
- **Objective:** Simulate a security incident and perform root cause analysis using a combination of VMs for the attacker, victim, and monitoring systems.
- **Tools:** Microsoft Sentinel, Splunk, Kali Linux.
- **VMs:**
  - **Kali Linux VM** (Attacker)
  - **Windows Server VM** (Victim)
  - **Splunk/Defender VM** (SIEM)

### Key Activities
- Simulate attacks using Kali Linux.
- Investigate incidents in Splunk/Microsoft Sentinel.
- Perform root cause analysis and generate a report.

---

## 2. Scheduled Vulnerability Scans and Compliance Testing

This project demonstrates how to perform vulnerability scans and compliance checks using tools like **Nessus** and **OpenVAS**.

### Overview
- **Objective:** Perform vulnerability scans on various VMs and ensure compliance with security standards.
- **Tools:** Nessus, OpenVAS, Nmap.
- **VMs:**
  - **Windows Server 2019** (Scan Target)
  - **Ubuntu Server** (Scan Target)
  - **Kali Linux** (Scan VM with Nessus/OpenVAS)

### Key Activities
- Set up Nessus on Kali Linux VM.
- Perform scheduled scans on other VMs.
- Generate vulnerability and compliance reports.

---

## 3. Penetration Testing

A project to test network security using **Kali Linux** for penetration testing in an isolated environment.

### Overview
- **Objective:** Conduct internal penetration testing to identify and exploit vulnerabilities within the virtual network.
- **Tools:** Kali Linux, Burp Suite, Metasploit, Nmap.
- **VMs:**
  - **Kali Linux VM** (Penetration Testing)
  - **Windows Server 2019** (Target)
  - **Ubuntu Server** (Target)

### Key Activities
- Use **Metasploit** and **Nmap** to scan for vulnerabilities.
- Attempt to exploit weaknesses in the network.
- Document findings and provide mitigation strategies.

---

## 4. SIEM Deployment and Threat Intelligence Reporting

This project focuses on deploying a **SIEM** solution to monitor and respond to security threats.

### Overview
- **Objective:** Implement a SIEM tool to monitor logs from different VMs and generate threat intelligence reports.
- **Tools:** Splunk, Microsoft Sentinel.
- **VMs:**
  - **Splunk Server VM** (SIEM Tool)
  - **Windows Server VM** (Log Source)
  - **Ubuntu Server VM** (Log Source)

### Key Activities
- Deploy and configure Splunk on a dedicated VM.
- Configure VMs to send logs to Splunk for analysis.
- Analyze logs and create reports on detected threats.

---

## 🚀 Future Goals

- Specializing as an **IoT Security Consultant**
- Continuing to develop skills in **Operational Technologies** and **Cloud Security**
- Contributing to the open-source security community and participating in more **Capture the Flag (CTF)** events.

---

## 📫 Let's Connect!

- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/daniel-o-rourke-160b53ba/)
- **GitHub:** [Git Hub](https://github.com/sailingtheoutback/Portfolio)
- **Email:** [youremail@example.com](mailto:youremail@example.com)

---

Thank you for visiting my portfolio! Feel free to explore my repositories and reach out to discuss cyber security topics or collaboration opportunities.

