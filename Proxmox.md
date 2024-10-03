# 💻 Proxmox Server

This project focuses on my Proxmox server setup, which is used to host multiple virtual machines (VMs) for different purposes, including testing and network services.

## 🖥️ Virtual Machines (VMs)

| VM Name             | OS                 | Purpose                   | Resources Allocated        |
|---------------------|--------------------|---------------------------|----------------------------|
| pfSense Firewall     | pfSense            | Network firewall/router    | 2 CPU, 4GB RAM, 20GB Disk  |
| Kali Linux           | Kali Linux         | Penetration testing lab    | 4 CPU, 8GB RAM, 50GB Disk  |
| Windows Server 2019  | Windows Server 2019| Domain controller, testing | 4 CPU, 16GB RAM, 100GB Disk|
| Ubuntu Server        | Ubuntu 22.04       | Web server & DNS resolver  | 2 CPU, 4GB RAM, 40GB Disk  |

---

## 📋 VM Details

### pfSense Firewall
- **Purpose:** Provides firewall and routing capabilities for the home network.
- **Configuration:** Utilizes WAN and LAN interfaces, configured for NAT and DHCP.

### Kali Linux
- **Purpose:** Penetration testing environment for practicing ethical hacking skills.
- **Key Tools:** Metasploit, Wireshark, Burp Suite, Nmap.

### Windows Server 2019
- **Purpose:** Domain controller and testing environment for Active Directory services.
- **Key Features:** Active Directory, DNS, DHCP setup for a test lab.

### Ubuntu Server
- **Purpose:** Web server hosting internal websites and serving as a DNS resolver for the network.
- **Services:** Apache, MySQL, Bind9 for DNS.


[Return](./Front%20page.md)