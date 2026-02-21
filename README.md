# Cybersecurity Lab Portfolio
Hands-on cybersecurity labs demonstrating practical experience in network scanning, vulnerability analysis, system hardening, and penetration testing environments.

---

## Lab 1 — Virtual Lab Setup and Network Reconnaissance

### Objective
Build a virtual penetration-testing lab using Kali Linux and Ubuntu Server and perform initial network reconnaissance.

### Environment
- Host: VirtualBox
- Attacker Machine: Kali Linux
- Target Machine: Ubuntu Server 24.04
- Network: NAT + Host-Only configuration

### Tools Used
- Nmap
- SSH
- Linux networking utilities

### Steps Performed
1. Configured virtual networking between Kali and Ubuntu.
2. Verified connectivity using `ip a`.
3. Conducted service detection scan using Nmap.
4. Identified open SSH service on target machine.
5. Successfully established SSH connection from Kali to target.

### Key Findings
- Target system reachable on host-only network
- SSH service detected on port 22
- Remote login successfully validated

## Evidence

Detailed documentation and screenshots for this lab are available in the Lab 1 folder:

[View Lab 1 — Virtual Network Reconnaissance and SSH Access](lab-1-virtual-network-recon/README.md)


---

## Lab 2 — Service Enumeration

### Objective
Perform service enumeration on discovered hosts to identify exposed network services such as FTP and SMB.

### Tools Used
- Nmap
- Nmap Scripting Engine (NSE)

### Key Findings
- FTP service detected on port 21
- SMB service detected on ports 139/445
- Enumeration revealed accessible system services

### Evidence

Detailed documentation and screenshots for this lab are available in the Lab 2 folder:

[View Lab 2 — Service Enumeration](lab-2-service-enumeration/README.md)
