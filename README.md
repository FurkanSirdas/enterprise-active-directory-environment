# Enterprise Active Directory Environment

## Project Overview

This project is a Windows Server Active Directory lab environment designed to simulate a small enterprise infrastructure.

The environment includes:

- Active Directory Domain Services (AD DS)
- DNS Configuration
- Organizational Units (OU)
- Department-based Security Groups
- Group Policy Objects (GPO)
- Shared Network Drives
- NTFS Permissions
- Access-Based Enumeration
- Centralized User and Permission Management

---

## Technologies Used

- Windows Server 2016
- Windows 10 Client
- Active Directory
- DNS
- Group Policy Management
- SMB File Sharing
- NTFS Permissions
- Oracle VirtualBox

---

## Implemented Features

### Active Directory Structure
- Finance OU
- HR OU
- Interns OU
- IT OU

### Security Groups
- Finance_Users
- HR_Users
- Interns_Users
- IT_Admins

### Group Policies
- Automatic local administrator assignment for IT_Admins
- Shared network drive mapping
- Centralized configuration management

### File Server
- Department-based shared folders
- Restricted folder permissions
- Hidden inaccessible folders using Access-Based Enumeration

---

## Network Configuration

| Device | IP Address |
|---|---|
| Domain Controller | 192.168.111.17 |
| Windows Client | 192.168.111.18 |

Domain Name:

```text
atlas.local
```

---

## Lab Environment

- Virtualized using Oracle VirtualBox
- Windows Server acting as Domain Controller
- Windows 10 joined to the domain

---

## Future Improvements

- DHCP Server
- WSUS
- PowerShell Automation
- Backup System
- Monitoring Solutions
- SIEM Integration
- Azure AD Hybrid Environment

---

## Author

Furkan Sirdas
