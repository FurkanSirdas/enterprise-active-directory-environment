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


---

# Turkish Description (Türkçe Açıklama)

## Proje Özeti

Bu proje, küçük ölçekli bir şirket altyapısını simüle etmek amacıyla oluşturulmuş bir Windows Server Active Directory laboratuvar ortamıdır.

Bu ortam içerisinde:

- Active Directory Domain Services (AD DS)
- DNS yapılandırması
- Organizational Unit (OU) yapısı
- Departman bazlı güvenlik grupları
- Group Policy Objects (GPO)
- Ortak ağ sürücüleri
- NTFS izinleri
- Access-Based Enumeration
- Merkezi kullanıcı ve yetki yönetimi

uygulanmıştır.

---

## Kullanılan Teknolojiler

- Windows Server 2016
- Windows 10 Client
- Active Directory
- DNS
- Group Policy Management
- SMB File Sharing
- NTFS Permissions
- Oracle VirtualBox

---

## Gerçekleştirilen Yapılar

### Organizational Unit (OU) Yapısı
- Finance
- HR
- Interns
- IT

### Güvenlik Grupları
- Finance_Users
- HR_Users
- Interns_Users
- IT_Admins

### Group Policy Yapıları
- IT_Admins grubuna otomatik local administrator yetkisi verilmesi
- Ortak ağ sürücüsünün otomatik bağlanması
- Merkezi kullanıcı ve yapılandırma yönetimi

### Dosya Sunucusu Yapısı
- Departman bazlı ortak klasörler
- Yetki bazlı erişim kontrolü
- Access-Based Enumeration ile yetkisiz klasörlerin gizlenmesi

---

## Ağ Yapısı

| Cihaz | IP Adresi |
|---|---|
| Domain Controller | 192.168.111.17 |
| Windows Client | 192.168.111.18 |

Etki Alanı:

```text
atlas.local
```
---

## Laboratuvar Ortamı

- Oracle VirtualBox kullanılarak sanallaştırılmıştır
- Windows Server Domain Controller olarak yapılandırılmıştır
- Windows 10 istemcisi domaine dahil edilmiştir

---

## Gelecekte Eklenebilecek Yapılar

- DHCP Server
- WSUS
- PowerShell Otomasyonu
- Backup Sistemi
- Monitoring Çözümleri
- SIEM Entegrasyonu
- Azure AD Hybrid Yapısı



## Yazar
Furkan Sirdas
