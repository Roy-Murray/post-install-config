<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>

<h1>osTicket - Post-Install Configuration</h1>

This tutorial will showcase  the post-install configuration of the open-source help desk ticketing system osTicket.

<h1>Environments and Technologies Used</h1>

- Remote Azure Virtusl Machine
- Remote Desktop
- IIS

<h1>Operating System Used</h1>

- Windows 10

<h1>Post-Install Configuration Steps</h1>

<h2>1. Acknowledge Agent Panel vs Admin Panel</h2>
 - The Agent panel is utilized by agents in order to work on Tickets
 - The Admin Panel is used to manage configurations, system settings and permissions

 <h2>2. Configure roles</h2>

 - Go to Admin Panel then Agents and lastly Roles
 - Add Supreme Admin as a role
 - Give All permissions, tasks, and check Premade in Knowledgebase tab
 - add role

![image](https://github.com/user-attachments/assets/032ea14c-d2c3-4462-9a83-b29fd71c11b9)

![image](https://github.com/user-attachments/assets/0f9cdc1f-5b52-465e-ae88-d47726363ecc)


 <h2>3. Configure Departments</h2>

- Go to Admin panel then departments
- add a new department called SysAdmins
-  create Department

 ![image](https://github.com/user-attachments/assets/baad07fa-d034-489a-b6e0-43bf4bc59f96)
 

 <h2>4. Configure Teams</h2>

 - Go to admin panel then Agents and lastly Teams
 - add a new team called Online Banking then create Team

 ![image](https://github.com/user-attachments/assets/3ac14801-3e6b-4b73-93cf-da2f12c60135)

 <h2>5. Allow anyone to create tickets</h2>

 - Navigate to admin panel
 - go to settings then users

 ![image](https://github.com/user-attachments/assets/31ae2ee6-35dc-49fe-a9ac-57766b30e6a5)

 <h2>6. Configure Agents</h2>

- go to admin panel then agents and add new
- add Jane to Dept: SysAdmins
- add John to Dept: Support

![image](https://github.com/user-attachments/assets/4b2be242-75b8-4037-99d3-3ad6dd5edf8b)

![image](https://github.com/user-attachments/assets/15c099ac-91a9-49ef-a8be-534eda8754e3)

 <h2>7. Configure Users</h2>

 - Go to admin panel, users then add new
 - add Karen and Ken

![image](https://github.com/user-attachments/assets/e143129d-c217-4a0b-b09a-b7fcb7ae22ca)


![image](https://github.com/user-attachments/assets/c297c4ae-08f2-4ad2-9fa7-99cdf6c32549)

 
 <h2>8. Configure SLA</h2>
- Go to admin panel, Manage then SLA
- Add these SLAs:

 - Sev-A Grace period = 1 hour, Schedule 24/7
 - Sev-B Grace period = 4 Hours, Schedule 24/7
 - Sev-C Grace period = 8 hours, Business hours

  ![image](https://github.com/user-attachments/assets/906af9b8-754e-4f95-a2e2-346e17734611)

  ![image](https://github.com/user-attachments/assets/2191bf8a-5a51-4fc7-be7d-d6ec46b71ce9)

  ![image](https://github.com/user-attachments/assets/357a6a3d-09b1-4c1f-941b-a3f7da8f247b)


 <h2>9. Configure Help Topics</h2>
 Go to Admin Panel -> Manage -> Help Topics
- add the following help topics
 
 - Business Critical Outage
 - Personal Computer Issues
 - Equipment Request
 - Password Reset
 - Other

![image](https://github.com/user-attachments/assets/412750c6-08ae-4403-befe-7e5f7421b7b7)

![image](https://github.com/user-attachments/assets/aed5d4bc-228f-4977-9b34-0ec767d28b2a)

![image](https://github.com/user-attachments/assets/f7e2cf6a-efd5-4184-af08-43c292929216)

![image](https://github.com/user-attachments/assets/baa37d4c-0478-4c46-9ca8-31a8fe4736fb)

![image](https://github.com/user-attachments/assets/2f1fadcb-06cb-4579-9588-5981abd99086)


<h2>Conclusion</h2>

The post-Installation configuration is completed which had allowed the osTicket to be suited to our needs. We can now use OsTicket manage issues and tickets.

