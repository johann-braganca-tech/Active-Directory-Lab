# Enterprise IT Support Lab (Active Directory)

This project simulates a small business IT environment using Windows Server 2022, Active Directory and a Windows 10 client machine.

It demonstrates core IT support skills including domain setup, user and group management, DNS configuration, Group Policy basics and system verification.

---

# Project Overview

In this lab, I configured a Windows Server 2022 domain environment using Active Directory Domain Services (AD DS). The environment includes a domain controller, Windows client machine, DNS configuration, user accounts, security groups and basic Group Policy testing.

The aim of this project is to practise common IT support tasks such as user account management, password resets, account unlocks, domain login testing and basic troubleshooting in a Windows domain environment.

---

# Active Directory

Active Directory is a centralized directory service used to manage users, computers and resources within a Windows domain environment.

## Key Functions:
- Authentication (user logon validation)
- Authorization (access control to resources)
- Centralized identity and access management

---

# Domain

A domain is a logical network boundary where users, computers and resources are managed centrally.

## Example: braganca.local

## Purpose:
- Centralized management
- Security and access control
- Simplified administration

---

## Domain Controller

A Domain Controller (DC) is a server responsible for authenticating users and enforcing security policies within the domain.

## Responsibilities:
- User authentication and logon services
- Directory database management
- Group Policy enforcement
- Access control and security management

---

# User Account

A user account represents an identity within the domain that allows access to systems and network resources.

## Example: `john.smith@braganca.local`


## Controls:
- System login
- File and folder permissions
- Application access

---

## Security Group

A security group is a collection of users used to manage permissions efficiently.

## Example:
- Sales-Team
- HR-Team

## Benefit:
Permissions can be assigned to groups instead of individual users, making access management easier and more secure.

---

# Group Policy (GPO)

A Group Policy Object (GPO) is used to apply and enforce configuration settings across users and computers within the domain.

## Examples:
- Password policies
- Desktop restrictions
- Software configuration
- Security settings

---

## DNS (Domain Name System)

DNS translates domain names into IP addresses and is essential for communication within a Windows domain environment.

## Role:
- Allows client devices to locate the Domain Controller
- Supports domain authentication and communication
- Resolves hostnames to IP addresses

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
- Password resets and account unlocks
- Domain environment configuration
- DNS configuration and troubleshooting
- Basic Group Policy configuration
- Identity and access management (IAM)
- Windows domain administration

---

# Future Lab Tasks

This project will continue to expand with additional IT support scenarios including:

- User onboarding and account provisioning
- Shared folder permissions
- Group Policy testing
- Domain join troubleshooting
- Remote support scenarios
- Microsoft 365 administration
- Ticket logging and incident management
