# Windows-Domain-Lab
## Overview
This project simulates a small corporate network using virtual machines.

## Environment
- VMware Workstation
- Windows Server (Domain Controller)
- Windows 11 Client

## Configuration Steps
1. Installed Windows Server
2. Configured Active Directory Domain Services
3. Created domain: lab.local
4. Created domain user: testuser
5. Joined Windows 11 client to the domain
6. Logged in using domain credentials

## Validation
Command:
whoami

Output:
lab\testuser

This confirms successful domain authentication.

## Skills Demonstrated
- Active Directory basics
- Domain join process
- User account management
- Virtual lab environment setup
