# Packet Tracer: Wireless Router & Client Configuration

## 📑 Table of Contents
- [Project Overview](#-project-overview)  
- [Technologies Used](#-technologies-used)  
- [Objectives Completed](#-objectives-completed)  
  - [Part 1: Physical Network Connections](#part-1-physical-network-connections)  
  - [Part 2: Wireless Router Configuration](#part-2-wireless-router-configuration)  
  - [Part 3: IP Addressing & Connectivity Testing](#part-3-ip-addressing--connectivity-testing)  
- [Key Configurations](#-key-configurations)  
- [Security Implementations](#-security-implementations)  
- [Skills Demonstrated](#-skills-demonstrated)  
- [Challenges & Solutions](#-challenges--solutions)  
- [Results](#-results)  
- [What I Learned](#-what-i-learned)  
- [Future Enhancements](#-future-enhancements)  

---

## 📌 Project Overview
This project demonstrates the setup and configuration of a home network using a cable ISP connection. It includes physical device connections, wireless router configuration, DHCP setup, and wired/wireless client connectivity using Cisco Packet Tracer.

---

## 🛠️ Technologies Used
* Cisco Packet Tracer  
* Networking Protocols: DHCP, WPA2-Personal  
* Devices: Cable modem, Wireless router, TV, PCs, Laptop  
* Cables: Coaxial, Copper straight-through Ethernet  
* Wireless Standard: 2.4 GHz Wi-Fi

---

## ✅ Objectives Completed

### Part 1: Physical Network Connections
* Connected coaxial cable from splitter to cable modem and TV  
* Connected cable modem to wireless router using Ethernet  
* Wired two PCs to the router using straight-through Ethernet cables

### Part 2: Wireless Router Configuration
* Accessed router via default gateway in browser  
* Changed default admin credentials  
* Configured DHCP (Starting at 50, max 10 users)  
* Set SSID to **MyHome**  
* Enabled **WPA2-Personal** security

### Part 3: IP Addressing & Connectivity Testing
* Set all devices to use DHCP  
* Connected laptop to wireless network  
* Verified internet access on all devices  
* Tested web access to external site

---

## ⚙️ Key Configurations
**SSID:** MyHome  
**Security:** WPA2-Personal  
**DHCP Pool:** Limited to 10 users  
**Subnet:** Auto-assigned 192.x.x.x range

---

## 🔐 Security Implementations
* Default router password changed  
* WPA2 wireless encryption enabled  
* Strong wireless passphrase configured

---

## 💡 Skills Demonstrated
* Physical network cabling  
* Router GUI administration  
* DHCP configuration  
* Wireless security setup  
* Network troubleshooting  
* Understanding home network topology

---

## ⚠️ Challenges & Solutions
**Challenge:** Understanding device roles (splitter, modem, router)  
**Solution:** Studied ISP data flow from coaxial to LAN  

**Challenge:** Wrong cable selections  
**Solution:** Corrected using coaxial and straight-through Ethernet  

**Challenge:** Office PC had no internet  
**Solution:** Set IP configuration to DHCP

---

## 🏁 Results
* Functional cable internet network  
* Secure wireless network established  
* Two wired PCs and one wireless laptop connected  
* TV service operational

---

## 📚 What I Learned
* Importance of physical layer connections  
* DHCP simplifies IP management  
* Wireless security best practices  
* Why default credentials must always be changed

---

## 🚀 Future Enhancements
* Add 5 GHz wireless network  
* Implement guest network  
* Configure port forwarding  
* Add MAC filtering  
* Use static DHCP reservations  
* Implement QoS
