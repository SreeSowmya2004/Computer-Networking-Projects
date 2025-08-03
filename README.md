# 🌐 Computer Networks Guide

## 🔌 1. What is a Computer Network?
A computer network is a system that connects multiple computing devices (computers, servers, mobile phones, etc.) so they can communicate, share data, and access resources.

---

## 🌐 2. Types of Computer Networks

| Network Type | Scope        | Description                             |
|--------------|--------------|-----------------------------------------|
| PAN          | Few meters   | Bluetooth, USB connections              |
| LAN          | Building     | Office/home network                     |
| WLAN         | Local        | Wi-Fi                                   |
| MAN          | City-wide    | Used by ISPs or large campuses         |
| WAN          | Country/global | Internet                              |
| CAN          | Campus       | Multiple LANs in schools/universities  |
| SAN          | Storage      | Dedicated storage network              |
| VPN          | Virtual      | Secure tunnel over public network      |

---

## 🧱 3. Networking Models (Layers of Abstraction)

### 🌐 OSI Model (7 Layers)
1. **Physical** – Cables, switches, physical medium  
2. **Data Link** – MAC addressing, switches (Ethernet)  
3. **Network** – IP addressing, routers (IPv4/IPv6)  
4. **Transport** – TCP/UDP, ports  
5. **Session** – Managing sessions (e.g., WebSockets)  
6. **Presentation** – Data formatting, encryption  
7. **Application** – HTTP, FTP, SMTP, DNS, etc.

### 🧰 TCP/IP Model (Real-world Use)
- Application  
- Transport  
- Internet  
- Link  

---

## 🗺️ 4. Addressing in Networking

### 🔢 A. IP Addressing
- **IPv4**: 32-bit (e.g., `192.168.1.1`)  
- **IPv6**: 128-bit (e.g., `2001:0db8:85a3::8a2e:0370:7334`)  
- **Types**:
  - Public vs Private
  - Static vs Dynamic (DHCP)

### 🧾 B. MAC Address
- 48-bit physical address (e.g., `00:1A:2B:3C:4D:5E`)  
- Burned into NICs  
- Used in Data Link Layer  

### 🔀 C. Port Numbers
- **Used in Transport Layer (TCP/UDP)**
- **Examples**:
  - HTTP: 80  
  - HTTPS: 443  
  - FTP: 21  
  - DNS: 53  
- **Ranges**:
  - Well-Known: `0–1023`  
  - Registered: `1024–49151`  
  - Dynamic/Private: `49152–65535`

---

## 📡 5. Communication Types

| Type     | Description                |
|----------|----------------------------|
| Unicast  | One-to-one                 |
| Broadcast| One-to-all (IPv4 only)     |
| Multicast| One-to-many (group-based)  |
| Anycast  | One-to-nearest (IPv6/CDNs) |

---

## 🚦 6. Protocols & Services

### ⚙️ Transport Layer
- **TCP**: Reliable, connection-based (web, email)  
- **UDP**: Unreliable, fast, connectionless (streaming, gaming)  

### 🌐 Application Layer
- **HTTP/HTTPS** – Web browsing  
- **DNS** – Domain name resolution  
- **FTP/SFTP** – File transfer  
- **SMTP/IMAP/POP3** – Email  
- **SSH** – Secure remote access  

### 📡 Network Layer
- **IP** – Routing data  
- **ICMP** – Diagnostics (e.g., ping)  
- **ARP** – Maps IP to MAC  

---

## 🧰 7. Networking Devices

| Device       | Purpose                             |
|--------------|-------------------------------------|
| Router       | Connects different networks         |
| Switch       | Connects devices in a LAN           |
| Hub          | Broadcasts to all ports (legacy)    |
| Modem        | Converts digital ↔ analog signals   |
| Access Point | Provides Wi-Fi connectivity         |
| Firewall     | Controls network traffic (security) |

---

## 📐 8. Network Topologies

| Topology | Description                          |
|----------|--------------------------------------|
| Bus      | Single cable; one failure breaks all |
| Star     | Central switch/hub; common in LANs   |
| Ring     | Devices connected in a loop          |
| Mesh     | Fully connected, high redundancy     |
| Hybrid   | Combination of two or more           |

---

## 🧠 9. Subnetting & CIDR

### 🧮 Subnetting
- Divides large networks into smaller subnets  
- Better IP management  

### 🔢 CIDR (Classless Inter-Domain Routing)
- e.g., `192.168.1.0/24` means 256 IPs  
- More flexible than Class A/B/C  

---

## 🔒 10. Network Security Concepts

- Encryption (TLS, SSL, IPsec)  
- Firewalls  
- VPNs  
- IDS/IPS (Intrusion Detection/Prevention Systems)  
- NAT (Network Address Translation)  
- Zero Trust Networking  
- DDOS Protection  

---

## 📈 11. Network Performance Metrics

| Metric       | Meaning                        |
|--------------|--------------------------------|
| Bandwidth    | Max data transfer rate         |
| Latency      | Time delay in communication    |
| Jitter       | Variability in packet delay    |
| Packet Loss  | Lost data during transmission  |

---

## 🧪 12. Useful Tools

- **Wireshark** – Packet analyzer  
- **Ping/Traceroute** – Network diagnostics  
- **netstat** – Displays active connections  
- **nmap** – Network scanner  
- **iptables/firewalld** – Linux firewall rules  
- **tcpdump** – Command-line packet capture  

---

## 🎓 13. Real-World Concepts

- Cloud Networking (VPCs, Subnets, Load Balancers)  
- SDN (Software Defined Networking)  
- IoT Networking  
- Edge Computing  
- 5G and Mobile Networks


## 🔌 1. What is a Computer Network?
A computer network is a system that connects multiple computing devices (computers, servers, mobile phones, etc.) so they can communicate, share data, and access resources.

---

## 🌐 2. Types of Computer Networks

| Network Type | Scope        | Description                             |
|--------------|--------------|-----------------------------------------|
| PAN          | Few meters   | Bluetooth, USB connections              |
| LAN          | Building     | Office/home network                     |
| WLAN         | Local        | Wi-Fi                                   |
| MAN          | City-wide    | Used by ISPs or large campuses         |
| WAN          | Country/global | Internet                              |
| CAN          | Campus       | Multiple LANs in schools/universities  |
| SAN          | Storage      | Dedicated storage network              |
| VPN          | Virtual      | Secure tunnel over public network      |

---

## 🧱 3. Networking Models (Layers of Abstraction)

### 🌐 OSI Model (7 Layers)
1. **Physical** – Cables, switches, physical medium  
2. **Data Link** – MAC addressing, switches (Ethernet)  
3. **Network** – IP addressing, routers (IPv4/IPv6)  
4. **Transport** – TCP/UDP, ports  
5. **Session** – Managing sessions (e.g., WebSockets)  
6. **Presentation** – Data formatting, encryption  
7. **Application** – HTTP, FTP, SMTP, DNS, etc.

### 🧰 TCP/IP Model (Real-world Use)
- Application  
- Transport  
- Internet  
- Link  

---

## 🗺️ 4. Addressing in Networking

### 🔢 A. IP Addressing
- **IPv4**: 32-bit (e.g., `192.168.1.1`)  
- **IPv6**: 128-bit (e.g., `2001:0db8:85a3::8a2e:0370:7334`)  
- **Types**:
  - Public vs Private
  - Static vs Dynamic (DHCP)

### 🧾 B. MAC Address
- 48-bit physical address (e.g., `00:1A:2B:3C:4D:5E`)  
- Burned into NICs  
- Used in Data Link Layer  

### 🔀 C. Port Numbers
- **Used in Transport Layer (TCP/UDP)**
- **Examples**:
  - HTTP: 80  
  - HTTPS: 443  
  - FTP: 21  
  - DNS: 53  
- **Ranges**:
  - Well-Known: `0–1023`  
  - Registered: `1024–49151`  
  - Dynamic/Private: `49152–65535`

---

## 📡 5. Communication Types

| Type     | Description                |
|----------|----------------------------|
| Unicast  | One-to-one                 |
| Broadcast| One-to-all (IPv4 only)     |
| Multicast| One-to-many (group-based)  |
| Anycast  | One-to-nearest (IPv6/CDNs) |

---

## 🚦 6. Protocols & Services

### ⚙️ Transport Layer
- **TCP**: Reliable, connection-based (web, email)  
- **UDP**: Unreliable, fast, connectionless (streaming, gaming)  

### 🌐 Application Layer
- **HTTP/HTTPS** – Web browsing  
- **DNS** – Domain name resolution  
- **FTP/SFTP** – File transfer  
- **SMTP/IMAP/POP3** – Email  
- **SSH** – Secure remote access  

### 📡 Network Layer
- **IP** – Routing data  
- **ICMP** – Diagnostics (e.g., ping)  
- **ARP** – Maps IP to MAC  

---

## 🧰 7. Networking Devices

| Device       | Purpose                             |
|--------------|-------------------------------------|
| Router       | Connects different networks         |
| Switch       | Connects devices in a LAN           |
| Hub          | Broadcasts to all ports (legacy)    |
| Modem        | Converts digital ↔ analog signals   |
| Access Point | Provides Wi-Fi connectivity         |
| Firewall     | Controls network traffic (security) |

---

## 📐 8. Network Topologies

| Topology | Description                          |
|----------|--------------------------------------|
| Bus      | Single cable; one failure breaks all |
| Star     | Central switch/hub; common in LANs   |
| Ring     | Devices connected in a loop          |
| Mesh     | Fully connected, high redundancy     |
| Hybrid   | Combination of two or more           |

---

## 🧠 9. Subnetting & CIDR

### 🧮 Subnetting
- Divides large networks into smaller subnets  
- Better IP management  

### 🔢 CIDR (Classless Inter-Domain Routing)
- e.g., `192.168.1.0/24` means 256 IPs  
- More flexible than Class A/B/C  

---

## 🔒 10. Network Security Concepts

- Encryption (TLS, SSL, IPsec)  
- Firewalls  
- VPNs  
- IDS/IPS (Intrusion Detection/Prevention Systems)  
- NAT (Network Address Translation)  
- Zero Trust Networking  
- DDOS Protection  

---

## 📈 11. Network Performance Metrics

| Metric       | Meaning                        |
|--------------|--------------------------------|
| Bandwidth    | Max data transfer rate         |
| Latency      | Time delay in communication    |
| Jitter       | Variability in packet delay    |
| Packet Loss  | Lost data during transmission  |

---

## 🧪 12. Useful Tools

- **Wireshark** – Packet analyzer  
- **Ping/Traceroute** – Network diagnostics  
- **netstat** – Displays active connections  
- **nmap** – Network scanner  
- **iptables/firewalld** – Linux firewall rules  
- **tcpdump** – Command-line packet capture  

---

## 🎓 13. Real-World Concepts

- Cloud Networking (VPCs, Subnets, Load Balancers)  
- SDN (Software Defined Networking)  
- IoT Networking  
- Edge Computing  
- 5G and Mobile Networks
