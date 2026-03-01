# Windows-Server-VM-in-Azure

## 1. How to create a domain controller in Windows Server.
Domain control is the main controller of your domain, Which controls things like logins, permissions, and security across all computers in the networks. Wihtout domain controller, there is no central control. 
### Steps:
* First go to Server Manager, click on AD DS. 
* Under all Servers, Click "more..."
* In Post Deployment configuration, click on promote this server to a domain controller as shown below
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/c534425df8ff7b20d7a42008742afef2d05841c5/%231%20Promoting%20Server%20to%20domain.jpg)
* Under deployment configurations, select add a new forest, followed by a root domain name of a choice. Next
* Nexting until reaching Prequisites check then press install. 
