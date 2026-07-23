# SSH Service Hardening Lab

## Overview

This project demonstrates basic SSH service hardening on a Linux system using Kali Linux and Metasploitable 2.

The objective was to improve the security of the SSH service by changing the default SSH port and verifying the changes using Nmap.

---

## Lab Environment

- Kali Linux
- Metasploitable 2
- OpenSSH
- Nmap

---

## Initial Enumeration

The SSH service was initially running on the default port (22).

### Initial Scan

![Before Scan](screenshots/before-scan.png.)

---

## SSH Configuration

The SSH server configuration was modified by changing the default SSH port from 22 to 2098.

### Configuration File

![SSH Configuration](screenshots/sshd-config-port2098.png.)

---

## Verification

After restarting the SSH service, a new Nmap scan confirmed that SSH was available on the new port.

### Final Scan

![After Scan](screenshots/after-scan.png.)

---

## Skills Demonstrated

- Linux administration
- SSH configuration
- Basic service hardening
- Network enumeration with Nmap
- Security verification

---

## Tools Used

- Kali Linux
- Metasploitable 2
- OpenSSH
- Nmap

---

## Disclaimer

This project was created in a controlled virtual lab environment for educational purposes only.
