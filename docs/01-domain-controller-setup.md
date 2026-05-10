## Domain Controller Setup

A virtual machine running Windows Server 2022 was configured as the Domain Controller for this lab environment.  

This server provides centralized authentication, authorization, and directory services using Active Directory.

---

## Server Configuration

- **Hostname:** DC01  
- **Operating System:** Windows Server 2022  
- **IP Address:** 192.168.26.129 (Static)  
- **Server Role:** Active Directory Domain Services (AD DS)  

### Server Setup
![Server Setup](https://github.com/user-attachments/assets/029090cc-52a6-4517-a219-fd4109354767)

![Server Setup](https://github.com/user-attachments/assets/c97ccc46-93de-4275-acce-edd386df6a24)

---

## Network Configuration (Static IP)

A static IP address was configured to ensure the Domain Controller remains consistently reachable by client machines.

### IP Configuration

![IP Config 2](https://github.com/user-attachments/assets/25ab1072-7c86-4cb2-990e-792b72cb458b)

---

## Domain Configuration

- **Domain Name:** braganca.local  

### Domain Creation

![Domain Setup](https://github.com/user-attachments/assets/01512b78-0e72-466f-a5bd-45683c15cb59)

![Domain Setup](https://github.com/user-attachments/assets/bbf17f31-123d-4051-8243-9138d2a1d1b1)

### Why `.local`?

- Used for **internal/private networks**
- Avoids conflicts with public domains
- Common practice in lab environments

> In production, a registered domain (e.g., company.com) or subdomain (e.g., ad.company.com) is typically used.

---

## Verification & Testing

After configuration, the following tests were performed to validate the setup.


### 1. Verify IP Configuration

Command:
```bash
ipconfig
```

<img width="2703" height="1635" alt="Image" src="https://github.com/user-attachments/assets/0c388985-c458-4709-acc2-5f4cb0bc3e04" />


### 2. Verify DNS Resolution

**Command:**
```bash
nslookup braganca.local
```

<img width="2172" height="1354" alt="Image" src="https://github.com/user-attachments/assets/2decef54-e6fc-459f-a88e-63449ed296b4" />


### 3. Verify Domain Authentication

**Login Used:**
```text
braganca\Administrator
```

<img width="2178" height="1359" alt="Image" src="https://github.com/user-attachments/assets/b1c5f423-83df-48c0-ad55-c9a8b7f9113f" />

Result: Domain authentication verified using braganca\Administrator credentials.

---



