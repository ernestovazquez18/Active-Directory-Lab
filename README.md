# Active Directory Lab

## Project Overview

This project simulates a small enterprise Active Directory environment using Windows Server 2025 and VirtualBox.

The goal of this project was to gain hands-on experience with Windows Server administration, Active Directory Domain Services (AD DS), Group Policy Objects (GPOs), user administration, security policies, and enterprise identity management.

---

## Environment

### Hardware

- Surface Pro 9
- Intel 12th Generation Processor
- 16 GB RAM
- Windows 11

### Virtualization

- Oracle VirtualBox

### Operating Systems

- Windows Server 2025 Standard Evaluation

---

## Active Directory Configuration

### Domain Controller

| Component | Value |
|------------|---------|
| Hostname | DC01 |
| Domain | vaztech.local |
| Role | Domain Controller |
| Services | Active Directory Domain Services, DNS |

---

## Organizational Units (OUs)

The following Organizational Units were created to simulate departments within an organization:

- IT
- HR
- Sales

Example Structure:

vaztech.local
├── IT
├── HR
└── Sales

---

## User Management

Created and managed Active Directory user accounts including:

- evazquez
- jsmith
- sjones
- tmiller

Tasks performed:

- User creation
- Password management
- Account administration
- OU management

---

## Security Groups

Created security groups to support role-based administration:

### IT

- IT_Admins

### HR

- HR_Users

### Sales

- Sales_Users

---

## Group Policy Objects (GPOs)

### Password Policy

Configured enterprise-style password controls:

- Minimum password length: 12 characters
- Password complexity enabled
- Maximum password age: 90 days

Purpose:

Improve account security and enforce strong authentication practices.

---

### Workstation Security Policy

Configured workstation security settings:

- Screen lock after 15 minutes
- Password required after lock

Purpose:

Protect unattended workstations and improve endpoint security.

---

### HR Restrictions Policy

Linked specifically to the HR Organizational Unit.

Configured:

- Prohibit access to Control Panel
- Restrict local system settings

Purpose:

Demonstrate role-based access control and department-specific restrictions.

---

## Skills Demonstrated

### Windows Server Administration

- Server deployment
- Server configuration
- Domain Controller promotion
- DNS configuration

### Active Directory

- User administration
- Group administration
- Organizational Unit design
- Security group management

### Identity and Access Management (IAM)

- Access control
- Group-based permissions
- User lifecycle management

### Security Administration

- Password policies
- Endpoint security controls
- Group Policy management

### Virtualization

- VirtualBox deployment
- Virtual machine configuration
- Infrastructure management

---

## Lessons Learned

Through this project I gained practical experience in:

- Active Directory architecture
- Domain administration
- Windows Server management
- Enterprise identity management
- Group Policy deployment
- Security policy implementation

This project provided hands-on exposure to technologies and administrative tasks commonly used by System Administrators, Help Desk Technicians, Identity & Access Management teams, and Cybersecurity professionals.

---

## Future Enhancements

Planned improvements include:

- Windows 11 domain-joined workstation
- Additional users and departments
- Shared network drives
- Advanced Group Policies
- Home SOC integration
- Wazuh deployment
- Security event monitoring
- Active Directory attack simulations

---

## Technologies Used

- Windows Server 2025
- Active Directory Domain Services
- DNS
- Group Policy Management
- VirtualBox
- Windows Administration
