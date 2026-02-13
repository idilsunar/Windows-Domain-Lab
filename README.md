# Windows-Domain-Lab

## Overview
This project simulates a small corporate network using virtual machines.  
It demonstrates basic Active Directory configuration, domain-joined clients, shared file access, and a simple backup automation.

---

## Environment
- VMware Workstation
- Windows Server (Domain Controller)
- Windows 11 Client

---

## Configuration Steps

### 1. Domain Controller Setup
1. Installed Windows Server
2. Configured Active Directory Domain Services (AD DS)
3. Created domain: **lab.local**
4. Created domain user: **testuser**

### 2. Client Configuration
5. Installed Windows 11 client
6. Joined the client to the **lab.local** domain
7. Logged in using domain credentials
8. Created a shared folder on the server:
9. Configured permissions for domain users
10. Accessed the shared folder from the Windows 11 client

This simulates a basic **corporate file server environment**.

---

## Backup Automation
11. Created a backup folder:
12. Wrote a backup script:
Script content:
@echo off
xcopy C:\Shared C:\Backups\Shared_Backup /E /I /Y
13. Executed the script to copy files from:
C:\Shared to C:\Backups\Shared_Backup

## Skills Demonstrated
- Active Directory basics
- Domain join process
- User account management
- Shared folder configuration
- Basic file server concepts
- Backup scripting (batch)
- Virtual lab environment setup



