# Home Lab: Active Directory + ServiceNow ITSM

## Overview
Personal project demonstrating enterprise IT infrastructure setup and service desk operations. Built on VirtualBox with Windows Server 2022 domain controller and Windows 10 client.

## Architecture
- **DC01**: Windows Server 2022 Standard (Domain Controller)
  - Active Directory domain: corp.local
  - DNS, DHCP services
  - Organizational Units: IT, Sales, HR
  - Users: john, alice, bob (domain members)
  - Security Groups: IT_Staff, IT_Support

- **CLIENT01**: Windows 10 Pro (Domain Member)
  - Joined to corp.local domain
  - Network: Internal Network (192.168.1.0/24)
  - Static IP: 192.168.1.20

## ITSM Ticketing
ServiceNow Personal Developer Instance with 10 realistic service desk incidents:
1. Password reset (Medium priority)
2. Account lockout (High priority)
3. Printer jam (Low priority)
4. VPN connectivity (High priority)
5. Network drive mapping (Medium priority)
6. Outlook profile corruption (Medium priority)
7. Slow PC performance (Medium priority)
8. Software installation request (Low priority)
9. New user onboarding (High priority)
10. Group access request (Low priority)

Each ticket: created → investigated → resolved with documentation.

## Skills Demonstrated
- Active Directory setup and user management
- Group Policy basics
- Network configuration (TCP/IP, static IPs, DNS)
- Virtualization (VirtualBox)
- ITSM ticketing workflows (ServiceNow)
- Service desk troubleshooting scenarios
- Documentation and SLA management

## Tools Used
- VirtualBox (hypervisor)
- Windows Server 2022 (domain controller)
- Windows 10 Pro (client OS)
- ServiceNow (ITSM platform)
- Active Directory Users and Computers

## What I Learned
- Enterprise domain architecture and AD object management
- Real-world ticketing process: intake → diagnosis → resolution
- Priority-based incident handling
- SLA tracking and escalation procedures
- Cross-team coordination in IT support
