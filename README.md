<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
<p>
In this tutorial we will demonstrate the post configuration setup of the osTicket system.
</p>
<p>
We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup. First we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should look something like this. As you can see we have successfully created the "Supreme Admin" role.<br />
</p>
<p><img width="1460" height="539" alt="slide1" src="https://github.com/user-attachments/assets/fb85e0a4-51b7-40f1-8e5f-039c1e727ec9" />

</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department. This is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab.
</p>
<p>
<img width="1074" height="865" alt="slide2" src="https://github.com/user-attachments/assets/4ebe6655-af8d-4ca4-9302-73c2a5945c45" />
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an "A team" that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team.
</p>
<p>
<img width="1033" height="714" alt="slide3" src="https://github.com/user-attachments/assets/64997f1a-c7c0-48d3-9551-34ae4117c9d8" />

</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.
</p>
<p>
<img width="1071" height="704" alt="slide4" src="https://github.com/user-attachments/assets/45bf375b-2c1b-4b9d-82ed-fdba0a343cd1" />

</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab.
</p>
<p>
<img width="932" height="843" alt="slide5" src="https://github.com/user-attachments/assets/6a775721-3dc7-47c2-a3f1-6163f2b5b298" />
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new.
</p>
<p>
<img width="925" height="339" alt="slide6" src="https://github.com/user-attachments/assets/b40e019c-656d-4aff-8f05-8a4ce0b24219" />
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period.
</p>
<p>
<img width="923" height="601" alt="slide7" src="https://github.com/user-attachments/assets/6a767aa2-bbec-411c-a92d-53d1ff77b4b5" />
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage". This can be used if customers cannot access mobile banking.
</p>
<p>
<img width="934" height="577" alt="slide8" src="https://github.com/user-attachments/assets/15537372-765e-4493-80f1-4b8e7490a701" />
</p>
<p>
Congratulations, hopefully you followed all the steps with no errors!
