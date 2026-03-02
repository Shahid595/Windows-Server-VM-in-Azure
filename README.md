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
### Creating a group
Groups are a good way of organizing people, especially when we're giving permissions to things - granting people the ability to do certain things, we generally want to do it with a group as opposed to a user, even if only one user is in the group. Because when you have more users and you become a bigger organization, you're not going to want to have put individual users permissions to different things. It gets messy and it also gets dangerous from a security perspective. You would rather give the group a permission to a certain thing or apply a GPO to you group or give permission to some certain app or something like that access and then you'd rather put people in this group.
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/c17ecff27d2572d06f99e2336de35fd7bc20bd9d/%23groups.png)
Adding Tom Brady to the group:
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/63c5c9c02595e2c1fa93fca9c83c4c338b2c0b8e/Adding%20Tom%20to%20a%20group.jpg)
*Now that Tom Brady is the part of "IT workers" group. 
*We can add a new user that might be in the same department/s as Tom brady by simply copying the user.
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/a8730f79cf7b8df0ce8a2e8c226f7bc303a00e22/copyingTom.jpg)
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/f0830742a7a5d9f0e5bfc6aa4f2e8d180b30a371/MikeSmithCopy2.jpg)
Now, you can see Mike Smith is automatically a member of the group IT workers.
![image alt](https://github.com/Shahid595/Windows-Server-VM-in-Azure/blob/ed496b49b2d8a0b5c649ccde39f6bcbbff2b6af2/MikeGroups3.jpg)
