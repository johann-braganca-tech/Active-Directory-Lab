# Active Directory User & Group Management

This section covers the creation and organization of users, Organizational Units (OUs), and security groups within the Active Directory environment.

---
## Organizational Units

Custom Organizational Units (OUs) were created to structure the Active Directory environment.


### Structure:

```text
Braganca.local
│
├── Braganca-Users
│   ├── IT
│   ├── HR
│   ├── Finance
│   └── Sales
│
├── Braganca-Groups
└── Braganca-Computers
```

### Purpose:
- Organize users by department
- Enable Group Policy application
- Avoid use of default Active Directory containers

### Output

<img width="2178" height="1353" alt="Image" src="https://github.com/user-attachments/assets/fde84993-5457-436f-a749-c1be22a8cf29" />

---

## User Accounts

User accounts were created and organized by department within the Braganca-Users OU.

### IT Department
- daniel.carter – IT Manager  
- aisha.khan – System Administrator  
- james.walker – IT Support  
- ryan.patel – IT Support  
- chloe.bennett – Junior IT Support  

### HR Department
- emma.johnson  
- liam.smith  
- grace.hall  

### Finance Department
- olivia.brown  
- noah.wilson  
- lucas.green  

### Sales Department
- sophia.taylor  
- ethan.davis  
- mia.clark  

### Output

<img width="2178" height="1354" alt="Image" src="https://github.com/user-attachments/assets/7e317436-9ff7-41e1-8f61-004743e7f3e3" />

<img width="2176" height="1353" alt="Image" src="https://github.com/user-attachments/assets/995e0f71-a453-446c-a520-8c4d47365fef" />

<img width="2179" height="1360" alt="Image" src="https://github.com/user-attachments/assets/b5349b93-19ee-443b-a36a-416020a8552d" />

<img width="2173" height="1359" alt="Image" src="https://github.com/user-attachments/assets/fc7e338b-bdf9-49d7-ab52-07a923ed35a6" />

---

## Security Groups

Security groups were created to manage access and permissions efficiently.

### Groups:
- IT-Team
- HR-Team
- Finance-Team
- Sales-Team

### Purpose:
- Simplify permission management
- Assign access based on department
- Follow best practices (group-based access control)

---

## Group Membership

Users were assigned to groups based on their department.

### IT-Team
- daniel.carter
- aisha.khan
- james.walker
- ryan.patel
- chloe.bennett

### HR-Team
- emma.johnson
- liam.smith
- grace.hall

### Finance-Team
- olivia.brown
- noah.wilson
- lucas.green

### Sales-Team
- sophia.taylor
- ethan.davis
- mia.clark

### Output

<img width="2176" height="1357" alt="Image" src="https://github.com/user-attachments/assets/e12a680c-3468-4e3a-9de8-861871ddc53e" />

<img width="2181" height="1351" alt="Image" src="https://github.com/user-attachments/assets/68fe2c67-8ad5-404c-ac4d-75409f45aee1" />

<img width="2182" height="1354" alt="Image" src="https://github.com/user-attachments/assets/1c0d626a-09b2-48b7-830d-a2bfd53e0ea6" />

---
