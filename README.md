# Windows-Server-VM-in-Azure

## 1. How to create a domain controller in Windows Server.
Domain control is the main controller of your domain, Which controls things like logins, permissions, and security across all computers in the networks. Wihtout domain controller, there is no central control. 
### Steps:
* First go to Server Manager, click on AD DS. 
* Under all Servers, Click "more..."
* In Post Deployment configuration, click on promote this server to a domain controller as shown below
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/c534425df8ff7b20d7a42008742afef2d05841c5/%231%20Promoting%20Server%20to%20domain.jpg)
* Under deployment configurations, select add a new forest, followed by a root domain name of a choice. Next

![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/d47f78b74e94c1571f11d566285e93c2d0573d50/%232.jpg)
* Nexting until reaching Prequisites check then press install.
* Now the domain controller is established.

### Creating an Organizational Unit
Folders in Active Directory are called OUs for organizational units. In Active directory people, users, and computers are objects, including security groups. 
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/8e98e2bcc79e871839ff849d7d78006a6c2c102c/%233.png)

### Creating a User in AD
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/095f9f155b326f545c45db21accf80599a76e29e/%234.png)
Our first user created in Branch 1
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/f54735c070b318b2a949002cc1a0b927c7959c4d/%235.png)
User created under Branch 1 of users
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/dfb15552a605a74d1cebf9fcb188f37985e4131c/%236.jpg)
