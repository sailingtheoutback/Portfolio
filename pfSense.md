# 🔒 pfSense Firewall Setup

This project covers the configuration and setup of my **pfSense** firewall, which secures and manages traffic on my home network.

## 🔧 Features Configured

- **Firewall Rules:** Custom rules to block unwanted traffic and allow necessary services (e.g., web, SSH).
- **NAT (Network Address Translation):** Configured for proper routing between internal and external networks.
- **VPN (Virtual Private Network):** Set up OpenVPN for secure remote access to the home network.
- **Traffic Shaping:** Optimized network traffic to prioritize critical services like streaming and gaming.
- **DHCP Server:** Provides automatic IP address allocation for devices on the network.

## 📊 Interfaces

| Interface           | IP Address         | Purpose                   |
|---------------------|--------------------|---------------------------|
| WAN                 | DHCP (External)    | Internet connection        |
| LAN                 | 192.168.1.1        | Internal home network      |
| VPN                 | 10.10.10.1         | VPN access point           |

## 🔐 Security Settings

- **Firewall Rules:** Configured to block inbound connections by default.
- **Intrusion Detection:** Using Snort to monitor for suspicious activity.
- **DNS Resolver:** Ensures DNS queries are encrypted using DNS over TLS (DoT).