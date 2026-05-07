# Enterprise IT Support Lab (Active Directory)

This project simulates a real-world enterprise IT environment using Active Directory on Windows Server 2022.

It demonstrates core IT support skills including user management, domain configuration, DNS setup, and system verification.

---

## Active Directory

Active Directory is a **centralized directory service** used to manage users, computers, and resources within a Windows domain environment.

### Key Functions:
- Authentication (user logon validation)
- Authorization (access control to resources)
- Centralized identity and access management

---

## Domain

A **domain** is a **logical network boundary** where all objects (users, computers, and resources) are managed centrally.

### Example: braganca.local

### Purpose:
- Centralized management
- Security boundary for authentication and authorization

---

## Domain Controller

A **Domain Controller (DC)** is a server responsible for **authenticating users and enforcing security policies** within the domain.

### Responsibilities:
- User authentication (logon services)
- Directory database management
- Group Policy enforcement
- Access control and security

---

## User Account

A **user account** represents an identity within the domain that allows access to systems and resources.

### Example: john.smith@braganca.local


### Controls:
- System login
- File and folder permissions
- Application access

---

## Security Group

A **security group** is a collection of users used to assign permissions efficiently.

### Example:
- Sales-Team
- HR-Team

---

### Benefit:
Permissions are assigned to groups instead of individual users.

---

## Group Policy (GPO)

A **Group Policy Object (GPO)** is used to enforce configuration settings on users and computers.

### Examples:
- Password policies
- Desktop restrictions
- Software control

---

## DNS (Domain Name System)

DNS translates domain names into IP addresses and is essential for domain communication.

### Role:
- Allows clients to locate Domain Controllers
- Supports authentication within the domain

---

# Technologies Used

## Server Environment
- Windows Server 2022  
- Active Directory Domain Services (AD DS)  

## Client Environment
- Windows 10 Enterprise  

## Virtualization
- VMware Workstation  

---

# Skills Demonstrated

- Active Directory administration  
- User and group management  
- Domain environment configuration  
- Identity and access management (IAM)  
- Group Policy configuration  

---
