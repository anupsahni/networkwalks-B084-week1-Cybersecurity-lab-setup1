# 🛡️ Cybersecurity & Penetration Testing Lab

## Overview

This repository documents the setup of a basic cybersecurity and penetration-testing laboratory using **Kali Linux** and **Oracle VirtualBox**.

The lab was created as part of the **NETWORKWALKS Cybersecurity Program – Week 1**. The purpose is to build a safe and isolated virtual environment where cybersecurity concepts and security tools can be practiced.

Screenshots included in this repository provide evidence of the completed setup and configuration activities.

---

## 🎯 Purpose of the Lab

The main purpose of this practical exercise is to understand how a virtual cybersecurity environment can be created and prepared for future penetration-testing activities.

The lab focuses on:

- Virtual machine installation and configuration
- Kali Linux setup
- Virtual networking
- NAT and NAT Network concepts
- Network configuration
- IP addressing
- DNS and connectivity testing
- Virtual machine snapshots
- Documentation of technical work

---

## 🧰 Technologies and Tools

| Tool / Technology      | Purpose                                                |
| ---------------------- | ------------------------------------------------------ |
| **Oracle VirtualBox**  | Creating and managing the virtual machine              |
| **Kali Linux**         | Cybersecurity and penetration-testing operating system |
| **Virtual Networking** | Providing network connectivity to the VM               |
| **Linux Terminal**     | Checking and troubleshooting network configuration     |
| **GitHub**             | Storing and documenting the lab work                   |

---

## 🖥️ Virtual Lab Setup

The cybersecurity environment was created using Oracle VirtualBox. Kali Linux was imported/configured as the guest operating system.

The virtual machine was configured with appropriate networking so that the system could communicate with the required network while remaining separated from the host environment as needed.

A clean VM snapshot was also created so that the system could be restored to a known working state after future experiments.

---

## 🌐 Network Configuration

The networking portion of the lab involved configuring and verifying the virtual network connection.

The following concepts were explored:

### NAT

NAT allows the virtual machine to access external networks through the host computer's network connection.

### NAT Network

A NAT Network provides network connectivity to virtual machines while also allowing participating virtual machines on the same NAT Network to communicate with each other.

The network configuration was checked from both the VirtualBox settings and inside Kali Linux.

---

## 🔍 Network Verification

After configuring the network, the connection was verified using standard Linux networking commands.

### Display IP Configuration

```bash
ip addr
```

This command displays the network interfaces and the IP addresses assigned to them.

### Check Network Interfaces

```bash
ip link
```

This command provides information about available network interfaces and their current state.

### View Routing Information

```bash
ip route
```

This command displays the system's routing table and helps identify the configured gateway.

### Test Connectivity

```bash
ping -c 4 google.com
```

The ping command was used to verify basic connectivity with an external host.

### Check DNS Configuration

```bash
cat /etc/resolv.conf
```

This can be used to view the DNS configuration being used by the system.

---

## 📸 Practical Evidence

The repository contains screenshots documenting the major stages of the lab.

### 01 — Lab Setup

The first screenshot documents the initial stage of the cybersecurity laboratory setup.

`1-screenshot-title-image.png`

---

### 02 — Virtual Network Configuration

This screenshot shows the network configuration performed for the virtual machine.

`2-screenshot-network-settings-1.png`

---

### 03 — Kali Linux Environment

This screenshot provides evidence that the Kali Linux virtual machine was successfully started and configured.

`3-screenshot-kali-linux.png`

---

### 04 — Kali Network Settings

This screenshot shows the network settings and configuration available inside Kali Linux.

`4-screenshot-kali-network-settings.png`

---

## 📋 Lab Activities Completed

The following activities were completed during the practical:

- Installed and configured Oracle VirtualBox.
- Imported/configured Kali Linux.
- Set up the required virtual networking.
- Created a private NAT Network.
- Configured Kali Linux network settings.
- Checked the assigned IP configuration.
- Verified network connectivity.
- Tested DNS resolution.
- Created a clean VM snapshot for recovery.
- Recorded the setup using screenshots.
- Documented the work in GitHub.

---

## 🧠 Key Learning

This practical helped in understanding how cybersecurity laboratories can be safely created using virtualization.

The major concepts learned include:

- Virtual machines and virtualization
- Kali Linux environment
- NAT and NAT Network
- Network interfaces
- IPv4 configuration
- Default gateway and routing
- DNS resolution
- Network connectivity testing
- VM snapshots and recovery
- Technical documentation using GitHub

---

## 🔄 Snapshot and Recovery

A clean snapshot of the configured Kali Linux virtual machine was created.

Snapshots are useful during cybersecurity experiments because they provide a restore point. If a configuration change or experiment causes a problem, the virtual machine can be returned to the previous working state.

---

## 🔐 Responsible Security Practice

This laboratory is intended strictly for **learning and authorized cybersecurity practice**.

All penetration-testing and security-related activities should be performed only against systems that are owned by the user or where explicit permission has been provided.

The virtual lab provides a controlled environment for practicing cybersecurity concepts safely.

---

## 📁 Repository Contents

```text
CYBERSECURITY-LAB-SETUP
│
├── 1-screenshot-title-image.png
├── 2-screenshot-network-settings-1.png
├── 3-screenshot-kali-linux.png
├── 4-screenshot-kali-network-settings.png
└── README.md
```

---

## 👨‍💻 Author

**Anup Sahni**

Cybersecurity Program
NETWORKWALKS
Batch: **B084J**

---

## 📌 Project Details

**Project:** Cybersecurity & Pentesting Lab Setup
**Program:** Cybersecurity
**Week:** 01
**Platform:** Kali Linux
**Virtualization:** Oracle VirtualBox
**Documentation:** GitHub

---

## ✅ Conclusion

The basic cybersecurity and penetration-testing laboratory was successfully prepared using Kali Linux and Oracle VirtualBox.

The virtual networking, Kali Linux network configuration, connectivity, DNS resolution, and recovery snapshot were verified. This setup provides a suitable foundation for carrying out future cybersecurity practical exercises in a controlled environment.
