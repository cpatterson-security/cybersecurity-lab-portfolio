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
