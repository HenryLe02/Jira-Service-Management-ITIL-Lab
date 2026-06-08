# Jira-Service-Management-ITIL-Lab
# Project 2 - Ticketing System / ITIL Service Desk Lab

## Overview

In this project, I built a simulated IT Help Desk environment using Jira Service Management and ITIL 4 practices.

The lab focuses on managing the full lifecycle of support tickets, including ticket creation, prioritisation, investigation, troubleshooting, resolution, documentation, and closure.

I created and resolved six common Help Desk scenarios to demonstrate how IT Support teams handle user issues in a real-world service desk environment.

---

## Business Scenario

A small business requires a structured service desk process to manage user support requests and technical incidents.

To simulate this environment, I used Jira Service Management to create realistic support tickets based on common workplace issues. Each ticket followed an ITIL-style workflow, including incident logging, prioritisation, troubleshooting, internal documentation, resolution, and closure.

---

## Environment & Tools Used

- Jira Service Management
- ITIL 4 Framework
- Active Directory
- Microsoft 365
- Microsoft Entra ID
- Microsoft Authenticator
- VPN Client
- Network Printers
- Shared Network Drives
- Windows 10/11

---

## Tickets Completed

| Ticket | Scenario | Priority | Status |
|---|---|---|---|
| Ticket 001 | Password Reset Incident | Medium | Resolved |
| Ticket 002 | Outlook Not Opening | Medium | Resolved |
| Ticket 003 | VPN Connection Failure | High | Resolved |
| Ticket 004 | Network Printer Offline | High | Resolved |
| Ticket 005 | MFA Registration Issue | High | Resolved |
| Ticket 006 | Shared Drive Access Issue | Medium | Resolved |

---

## Full Documentation

📄 [View Full Project Documentation](docs/Project-2-Ticketing-System-with-ITIL.pdf)

---

## Ticket 001 - Password Reset Incident

The first ticket involved a user who was unable to sign in to their Windows workstation after forgetting their password.

I verified the user's identity before making any account changes. After confirming that the issue was caused by a forgotten password, I reset the password in Active Directory and required the user to create a new password at the next sign-in.

The user successfully regained access to their workstation, and the ticket was resolved and closed.

<img width="994" height="756" alt="image" src="https://github.com/user-attachments/assets/5b7e5ec8-ed45-4e70-978c-d8c4c2ca86ed" />


---

## Ticket 002 - Outlook Not Opening

The second ticket involved a user whose Microsoft Outlook application crashed immediately after launch.

I checked Microsoft 365 service status and tested Outlook in Safe Mode. Since Outlook worked in Safe Mode, I suspected the issue was related to the user's Outlook profile. I created a new Outlook profile, reconfigured the mailbox, and confirmed that email synchronisation completed successfully.

The user was able to access email, calendar, and contacts again.

<img width="940" height="775" alt="image" src="https://github.com/user-attachments/assets/9a373680-6727-4f66-ac18-ab57c5f2abdc" />


---

## Ticket 003 - VPN Connection Failure

The third ticket involved a remote user experiencing repeated VPN disconnections while working from home.

I first verified that the user's internet connection was stable and that external websites could be accessed without interruption. This helped isolate the issue to the VPN client rather than the user's network connection.

After reviewing the VPN configuration, I recreated the VPN profile and updated the connection settings. The user confirmed stable VPN access to internal company resources.

<img width="921" height="825" alt="image" src="https://github.com/user-attachments/assets/d16940bf-38c4-469a-8dd0-383d86083e66" />


---

## Ticket 004 - Network Printer Offline

The fourth ticket involved a shared office printer showing as Offline and preventing multiple users from printing business documents.

I checked the printer's power status and confirmed that it was connected to the network. After testing connectivity to the printer, I determined that the issue was related to the Windows Print Spooler service.

I restarted the Print Spooler service, cleared pending print jobs, and confirmed that the printer returned to Online status. A successful test print was completed.

<img width="860" height="771" alt="image" src="https://github.com/user-attachments/assets/62e0feac-62dc-48cc-9901-7296a9f53d6c" />


---

## Ticket 005 - MFA Registration Issue

The fifth ticket involved a user who had changed mobile devices and could no longer receive Microsoft Authenticator verification prompts.

I verified the user's identity and reviewed their authentication methods in Microsoft Entra ID. The existing Microsoft Authenticator registration was still linked to the previous device, so I removed the outdated registration and reset the user's MFA methods.

The user registered Microsoft Authenticator on the new device and successfully completed a test sign-in.

<img width="865" height="748" alt="image" src="https://github.com/user-attachments/assets/2111ea6e-b224-4481-97c4-1176d44ffaa0" />


---

## Ticket 006 - Shared Drive Access Issue

The final ticket involved a user receiving an Access Denied message when attempting to open a shared network drive.

I confirmed that the user had network connectivity and could access other company resources. After reviewing Active Directory group membership, I found that the user was missing the required security group for shared drive access.

I added the user to the correct Active Directory security group and allowed the permission changes to replicate. After signing back in, the user confirmed access to the shared drive and required files.

<img width="915" height="759" alt="image" src="https://github.com/user-attachments/assets/964a7658-1780-447b-9426-a1a6cca2423a" />


---

## Project Summary

- 6 Help Desk incidents created and resolved
- 6 tickets documented using Jira Service Management
- 3 High-priority incidents resolved
- Covered Active Directory, Microsoft 365, VPN, MFA, printer, and shared drive support scenarios
- Practised ITIL-based incident management and ticket documentation

---

## Key Skills Demonstrated

- ITIL 4 Incident Management
- Jira Service Management
- Ticket Documentation
- Active Directory Administration
- Microsoft 365 Support
- Microsoft Entra ID Administration
- MFA Troubleshooting
- VPN Troubleshooting
- Printer Troubleshooting
- User Access Management
- Root Cause Analysis
- Customer Communication
- IT Help Desk Operations


---

## Overall Outcome

Through six simulated Help Desk incidents, I demonstrated the complete ticket lifecycle using Jira Service Management, including ticket creation, prioritisation, investigation, troubleshooting, resolution, documentation, and closure.

This project helped strengthen my understanding of ITIL-based service desk operations, customer communication, ticket documentation, and common IT support processes used in Help Desk and IT Support roles.

---

## What I Learned

This project gave me hands-on experience with the day-to-day responsibilities of an IT Help Desk technician. I learned how to manage tickets through their full lifecycle, document troubleshooting activities, prioritise incidents based on business impact, and communicate solutions clearly.

Working through different scenarios also improved my confidence with common support tasks involving Active Directory, Microsoft 365, VPN connectivity, shared drives, printers, and MFA. Overall, the project helped me better understand how enterprise service desks operate and how IT support teams follow structured processes to resolve user issues efficiently.
