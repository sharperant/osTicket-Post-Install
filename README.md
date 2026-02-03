<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
<p>
This tutorial demonstrates the post configuration setup of the osTicket system .
</p>
<p>
Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup. first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role<br />
</p>
<p>
<img width="1460" height="618" alt="slide1" src="https://github.com/user-attachments/assets/0bb68300-c230-48e5-a68e-fddcf4b4d8a1" />
</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab.
</p>
<p>
<img width="1074" height="865" alt="slide2" src="https://github.com/user-attachments/assets/4ebe6655-af8d-4ca4-9302-73c2a5945c45" />
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team.
</p>
<p>
<img width="1033" height="737" alt="slide3" src="https://github.com/user-attachments/assets/ce06a8b1-a731-42b7-8a55-9f7570fc567a" />
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.
</p>
<p>
<img width="1071" height="729" alt="slide4" src="https://github.com/user-attachments/assets/9ee90072-12cd-4eff-866e-0674efec3e5f" />
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab.
</p>
<p>
<img width="932" height="843" alt="slide5" src="https://github.com/user-attachments/assets/6a775721-3dc7-47c2-a3f1-6163f2b5b298" />
</p>
<p>
