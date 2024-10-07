<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This page outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA's

<h2>Configuration Steps</h2>

<p>
  
![osTicket Roles Pic](https://github.com/user-attachments/assets/30bac426-92c6-457c-98ea-06521c8edbe7)

<p>
  
![osTicket Roles Pic 2](https://github.com/user-attachments/assets/520e18bd-2813-49fc-8d83-4524961cee19)
  
</p>
</p>
<p>
Configure Roles
  
Roles are permissions granted to agents. Every employee has a set of permissions and tasks that they have access to. It is important so that only the right people have access to do certain tasks.

https://docs.osticket.com/en/latest/Admin/Agents/Roles.html
  
</p>
<br />

<p>
  
![osTicket Departments Pic](https://github.com/user-attachments/assets/162942f2-6258-4f9b-bc98-38a7b45b369b)

</p>
<p>

Configure Departments

Departments are needed for organization. Certain groups will be put in certain departments and certain departments will have certain tasks assigned to them. Some tasks need certain expertise to solve and that is where departments come in play.
  
https://docs.osticket.com/en/latest/Admin/Agents/Departments.html

</p>
<br />

<p>
  
![osTicket Teams Pic](https://github.com/user-attachments/assets/6a23351b-2b4c-45ab-8f66-e09448883ecd)
  
</p>
<p>

Configure Teams

Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter. If an issue or problem comes up and you need a group of people from different departments are needed to solve it, teams are created and assigned the issue.

https://docs.osticket.com/en/latest/Admin/Agents/Teams.html

</p>
<br />

<p>
  
![osTicket Agents Pic](https://github.com/user-attachments/assets/04e29408-8a7f-46c4-ac79-3d2b959037e9)
  
</p>
<p>

Configure Agents

Agents are the workers who will provide support. They are the ones assigned tickets and will work to solve them and any other cutomer issues.

https://docs.osticket.com/en/latest/Admin/Agents/Agents.html

</p>
<br />

<p>
  
![osTicket Users Pic](https://github.com/user-attachments/assets/313cdb52-b206-481d-b87d-03f64a7ad752)
  
</p>
<p>
Configure Users

Users are the customers with issues that need to be resolved. They create the tickets and those tickets are sent to the help desk professionals to be solved

https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html

</p>
<br />

<p>
  
![osTicket SLA Pic](https://github.com/user-attachments/assets/91811de2-b99e-46a9-bb17-bf3923973ee8)
  
</p>
<p>

Configure SLA's

SLA's or Service Level Agreements is like a set of guidelines for time management. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed. They are differentiated by severity. High severity issues are expected to solved and taken care of quikly while low level severity issues are given more time to solve.

https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html

</p>
<br />

<p>
  
![osTicket Help Topics](https://github.com/user-attachments/assets/952e9d0f-e058-4bde-9467-362c40570536)
  
</p>
<p>
Help Topics

Help Topics will determine what Department the ticket is routed to, which will determine which Agents have access to the ticket. The Help Topic also can determine other configurations of the ticket, such as the ticket’s SLA (or Service Level Agreement) and priority of a ticket, i.e. Emergency to Low. 

Help Topics help stream line the process and make it easier for the user and agents
https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html
</p>
<br />
