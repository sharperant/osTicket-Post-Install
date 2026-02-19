<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
<p>
In this tutorial we will demonstrate the post configuration setup of the osTicket system.
</p>
<p>
<h2>Environments and Technologies Used</h2>
</p>
<p>
  
- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

</p>
<p>
<h2>Operating Systems Used</h2>
</p>
<p>
  
- Windows 10 (21H2)
</p>
<p>
<h2>Post-Install Configuration Objectives</h2>
  
- Configure Roles
  
- Configure Departments
- Configure Teams 
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics
<p>
<p>
<h2>Configuration Steps</h2>
</p>
<p>
<p>
CONFIGURE ROLES. After logging into osTicket with Admin credentials, Go to Admin Panel > Click "Agents" > Click "Roles" Click "Add New Role" and name it Supreme Admin granting you it's full permissions.
<p>
<p>
SUPREME ADMIN:
<p>
<p>
<img width="80%" height="1146" alt="slide2" src="https://github.com/user-attachments/assets/39d6d34a-5e75-4267-b173-f41102edcd65" />
<p>
<p>
<img width="80%" height="1434" alt="slide1" src="https://github.com/user-attachments/assets/1449191a-1863-4d49-bb10-7325de9db619" />
<p>
<p>
<img width="80%" height="1127" alt="slide3" src="https://github.com/user-attachments/assets/95bf7ead-1e5e-485c-b4a3-4a2f82ce27e2" />
<p>
<p>
<img width="80%" height="837" alt="slide4" src="https://github.com/user-attachments/assets/cb2e835e-2a99-4c8e-b2d5-4ff7cecae168" />
<p>
<p>
<img width="80%" height="913" alt="slide5" src="https://github.com/user-attachments/assets/0a16b60d-95a4-44b3-948c-f5806af087b8" />
<p>
<p>
CONFIGURE DEPARTMENTS. Go back to Agents > Click "Departments" > click "Add New Department" Name it "Sysadmin" and set its parent to Top-Level.
<p>
<p>
SYSTEM ADMINISTRATORS:
<p>
<p>
<img width="2252" height="1514" alt="slide6" src="https://github.com/user-attachments/assets/40bf9b1e-4f2a-4cba-8125-c3ced63e70e8" />
<p>
<p>
<img width="2252" height="1514" alt="slide7" src="https://github.com/user-attachments/assets/2baf0a3a-0d26-40ba-84af-92a033bd11e7" />
<p>
<p>
CONFIGURE TEAMS. Go back to "Agents" again > Click "Teams" > add a new team and name it whatever you want.
<p>
<p>
<img width="2164" height="1370" alt="slide8" src="https://github.com/user-attachments/assets/aabf04c2-fc7a-4266-b936-f2a5ea67c010" />
<p>
<p>
Allow anyone to create ticket. Under the Admin Panel > Click on "Settings" > Go to "User Settings" > Uncheck the "Registration Required" box. Now unregistered users can create tickets, this helps in scenarios where quick ticket creation is vital. Make sure "Require registration and login to create tickets" is not selected.
<p>
<p>
<img width="2062" height="1388" alt="slide9" src="https://github.com/user-attachments/assets/cc67ca57-b378-423d-bac9-60bf1992dd4f" />
<p>
<p>
CONFIGURE AGENTS (WORKERS). Under Admin Panel > Go to Agents > Click "Add New" Here I created: Jane Doe – Department: Sysadmin, Role: Supreme Admin, Team: Online Banking. And : John – Department: Support, Role: View Only.
<p>
<p>
<img width="2116" height="1097" alt="slide10" src="https://github.com/user-attachments/assets/f2a85671-a2b1-40ce-b265-2506fb07cbfb" />
<p>
<p>
<img width="2210" height="1484" alt="slide11" src="https://github.com/user-attachments/assets/df28cf35-e7de-457f-99ee-569e9fba30ff" />
<p>
<p>
<img width="2126" height="1088" alt="slide12" src="https://github.com/user-attachments/assets/42873b7a-3e33-4957-89e2-d0b051931d9d" />
<p>
<p>
CONFIGURE USERS (CUSTOMERS). Under Admin Panel > Go to "Users" -> Click "Add New" Add two end users named Ken & Karen. End users or customers, can create and view support tickets, access a knowledge base, and track the status of their issues through the customer portal.
<p>
<p>
KEN USER:
<p>
<p>
<img width="1542" height="914" alt="slide13" src="https://github.com/user-attachments/assets/066e64e9-cbad-47a1-8a53-d30d12b0bdc3" />
<p>
<p>
Do the same Step for Karen User.
<p>
<p>
CONFIGURE SLA. Under the Admin Panel > Go to "Manage" section > Click on "SLA" 1. Name: Sev-A 2. Sev-B 3. Sev-C 1. Grace Period: 1-hour 2. 4-hour 3. 8-hour 1. Schedule: 24/7 2. 24/7 3. M-F 8am-5pm + holidays.
<p>
<p>
<img width="2090" height="1340" alt="slide14" src="https://github.com/user-attachments/assets/278a34b8-15aa-4f89-87a2-39c0b81e66c8" />
<p>
<p>
<p>
<img width="2060" height="1338" alt="slide15" src="https://github.com/user-attachments/assets/9c735bd2-ad6b-4a05-8f08-63b93132d501" />
<p>
<p>
<img width="2100" height="1332" alt="slide16" src="https://github.com/user-attachments/assets/35d9330d-68b5-4ccc-b283-2977307ded4c" />
<p>
<p>
CONFIGURE HELP TOPICS. Under Admin Panel > Go to "Manage" > Click "Help Topics" Business Critical Outage (parent: Report a Problem) Personal Computer Issues (parent: Report a Problem) Equipment Request (parent: General Inquiry) Password Reset (parent: Report a Problem) Other (parent: General Inquiry)
<p>
<p>
<img width="2042" height="1360" alt="slide17" src="https://github.com/user-attachments/assets/4328f2a2-b9a7-4d38-938b-cecdf167c04c" />
<p>
<p>
<img width="2048" height="1357" alt="slide18" src="https://github.com/user-attachments/assets/1a53814f-6780-4135-99d4-397d7432a28d" />
<p>
<p>
<img width="2070" height="1358" alt="slide19" src="https://github.com/user-attachments/assets/6951174b-fa12-4471-acdd-60954e8f33ae" />
<p>
<p>
<img width="2094" height="1360" alt="slide20" src="https://github.com/user-attachments/assets/cbf26709-0f10-4ad3-82dd-c68b012a2663" />
<p>
<p>
This now fully configures our osTicket and for a real-world help desk environment. I hope this guide was able to help clarify and assist you in setting up your osTicket. I recommended to practice triaging and solving tickets.
