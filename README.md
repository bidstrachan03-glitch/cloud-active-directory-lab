# 🟦 Cloud Active Directory Lab  
Deploying a Windows Server Domain Controller on AWS and simulating a real IT Help Desk workflow.

---

## 📘 Overview

This project demonstrates how to deploy a Windows Server 2022 instance on AWS EC2, promote it to a Domain Controller, configure Active Directory, create Organizational Units, users, and security groups, and simulate an IT Help Desk onboarding workflow using documentation and Jira.

**Skills Demonstrated**

- ☁️ AWS EC2 provisioning  
- 🖥️ Windows Server administration  
- 🗂️ Active Directory Domain Services  
- 🏢 Organizational Unit design  
- 👤 User & group management  
- 💻 PowerShell automation  
- 🎫 IT Help Desk ticketing workflow  
- 📊 Jira task management  

---

## 🏗️ Architecture

### 🖥️ AWS EC2 Instance
- Windows Server 2022  
- AD DS + DNS installed  
- Promoted to Domain Controller  

### 🗂️ Active Directory Structure
- **Human Resources OU**  
- **IT Department OU**  
- Users: John Smith, Sarah Johnson  
- Security Groups: Employees, IT Administrators  

### 🎫 ITSM Workflow
- Ticket #001: New Employee Account Creation  
- Documented in Notepad  
- Logged in Jira  

---

## 🚀 Deployment Steps

1. Launch Windows Server 2022 EC2 instance  
2. Configure storage, security groups, and key pair  
3. Retrieve Windows password using PEM key  
4. Connect via RDP  
5. Install AD DS and promote to Domain Controller  
6. Create OUs, users, and security groups  
7. Verify domain configuration via PowerShell  
8. Document onboarding workflow  
9. Log tasks in Jira  

---

## 🧩 Active Directory Configuration

- Created OUs for HR and IT  
- Created users:  
  - 👤 John Smith (HR)  
  - 👤 Sarah Johnson (IT)  
- Created security groups:  
  - 👥 Employees (HR)  
  - 👥 IT Administrators (IT)  
- Verified domain with `Get-ADDomain`  

---

## 📝 Help Desk Workflow

Simulated a real onboarding ticket:

- Ticket #001: Create new user account for John Smith  
- Documented steps in Notepad  
- Closed ticket after verification  
- Logged tasks in Jira  

---

# 📸 Screenshots

A complete visual walkthrough of the Cloud Active Directory Lab — from EC2 provisioning to AD configuration and ticketing workflow.

### 01 — AWS Console  
`01-aws-console.png`

### 02 — EC2 Instance Details  
`02-ec2-instance-details.png`

### 03 — Download PEM Key  
`03-download-pem-key.png`

### 04 — Security Group RDP Rule  
`04-security-group-rdp-rule.png`

### 05 — EC2 Storage Configuration  
`05-ec2-storage-configuration.png`

### 06 — EC2 Storage Configuration (Updated)  
`06-EC2-Storage-Configuration.png`

### 07 — RDP Authentication Login  
`07-RDP-Authentication-Login.png`

### 08 — AD Domain Controller Promotion (Troubleshooting)  
`08-AD-Domain-Controller-Promotion-Troubleshooting.png`

### 09 — AD Domain Controller Promotion (Retry)  
`09-AD-Domain-Controller-Promotion-Retry.png`

### 10 — Domain Controller Automatic Reboot  
`10-Domain-Controller-Automatic-Reboot.png`

### 11 — EC2 Instance Running / Health Check  
`11-EC2-Instance-Running-Health-Check.png`

### 12 — EC2 Windows Password Retrieval  
`12-EC2 Windows Password Retrieval via Private Key`

### 13 — EC2 Windows Desktop After Reboot  
`13-EC2-Windows-Desktop-After-Reboot`

### 14 — Active Directory Users and Computers  
`14-Active-Directory-Users-and-Computers-Console`

### 15 — Get‑ADDomain PowerShell Command  
`15-Get-ADDomain-PowerShell-Command`

### 16 — Active Directory OU Structure  
`16-Active-Directory-OU-Structure`

### 17 — HR OU: John Smith  
`17-Human-Resources-OU-User-John-Smith`

### 18 — IT OU: Sarah Johnson  
`18-IT-Department-OU-User-Sarah-Johnson`

### 19 — HR Security Group: Employees  
`19-Human-Resources-OU-Employees-Security-Group`

### 20 — IT Security Group: IT Administrators  
`20-IT-Department-OU-IT-Administrators-Security-Group`

### 21 — Ticket #001 (Start)  
`21-Ticket-001-New-Employee-Account-Creation-Notepad`

### 22 — Ticket #001 (Completed)  
`22-Ticket-001-Closed-John-Smith-Account-Created`

### 23 — Jira Dashboard  
`23-Jira-Beshorn-IT-Help-Desk-Lab`

---

## 💻 Scripts

Located in the `/scripts` directory:

- `create-ous.ps1` — Creates Organizational Units  
- `create-users.ps1` — Automates user creation  
- `create-groups.ps1` — Creates security groups  
- `verify-domain.ps1` — Runs domain verification commands  

---

## 📚 Documentation

Located in the `/docs` directory:

- `project-overview.md`  
- `ad-architecture.md`  
- `ticketing-workflow.md`  
- `jira-tasks.md`  

