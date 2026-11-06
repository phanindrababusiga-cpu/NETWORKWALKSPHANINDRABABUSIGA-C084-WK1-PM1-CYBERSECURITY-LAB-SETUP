# 🔐 Cybersecurity Lab Environment Setup

**Week 1 Project – Cybersecurity Internship at NETWORKWALKS**

## 📌 Project Overview

This project focuses on preparing a virtual cybersecurity lab environment using Oracle VM VirtualBox and Kali Linux.

The objective is to understand virtualization, virtual networking, NAT Network configuration, Linux commands, and shared-folder communication between Windows and Kali Linux.

## 🎯 Objectives

- Set up and explore Oracle VM VirtualBox.
- Prepare a Kali Linux virtual machine.
- Create and configure a NAT Network.
- Understand virtual machine networking.
- Configure shared folders between Windows and Kali Linux.
- Practice basic Linux terminal commands.
- Document practical activities and learning.

## ⚙️ Lab Configuration

| Component | Configuration |
|---|---|
| Host OS | Windows |
| Hypervisor | Oracle VM VirtualBox |
| Security OS | Kali Linux |
| Network Type | NAT Network |
| Network Name | NatNetwork |
| IPv4 Prefix | 10.0.0.0/24 |
| DHCP | Enabled |
| Shared Folder | Downloads |

## 🪜 Lab Setup Procedure

### Step 1: Explore Oracle VM VirtualBox

Opened Oracle VM VirtualBox and explored its features for managing virtual machines and virtual networks.

### Step 2: Prepare Kali Linux

Prepared the Kali Linux virtual machine for cybersecurity learning and practical exercises.

### Step 3: Configure NAT Network

Created a NAT Network in VirtualBox with the following configuration:

- Network Name: NatNetwork
- IPv4 Prefix: 10.0.0.0/24
- DHCP: Enabled
- IPv6: Disabled

### Step 4: Configure Shared Folder

Configured a shared folder between the Windows host and Kali Linux guest system.

Used the following command to list shared folders:

```bash
sudo VBoxControl sharedfolder list
```

### Step 5: Access Shared Folder Using Linux

Explored the shared-folder mount directory:

```bash
ls /media/
```

Accessed the Downloads shared folder:

```bash
ls -la /media/sf_Downloads
```

Also practiced listing files and directories using Linux terminal commands.

## 📸 Screenshots

### 1. Kali Linux Terminal and Shared Folder

Shows shared-folder configuration and Linux file-listing commands.

### 2. Shared Folder Contents

Shows files accessed through the shared folder in Kali Linux.

### 3. VirtualBox NAT Network Configuration

Shows the NatNetwork configuration with IPv4 prefix 10.0.0.0/24 and DHCP enabled.

### 4. Additional Practical Evidence

Add further screenshots of your Kali Linux virtual machine and network adapter settings here.

## 💡 What I Learned

1. Basics of Oracle VM VirtualBox.
2. Preparing a Kali Linux virtual machine.
3. Understanding NAT Network configuration.
4. Basic virtual networking concepts.
5. Configuring VirtualBox shared folders.
6. Accessing shared files from Kali Linux.
7. Practicing Linux terminal commands.
8. Documenting cybersecurity practical work.

## 🔐 Security and Ethical Use

This virtual lab is intended for educational purposes and authorized cybersecurity practice only.

## 👤 Author

**Siga Phanindra Babu**

Cybersecurity Intern – NETWORKWALKS

**Project:** Week 1 – Cybersecurity Lab Setup

## 🙏 Acknowledgement

I sincerely thank Waqas Karim (CCIE) and the NETWORKWALKS team for their guidance and support throughout this learning experience.
