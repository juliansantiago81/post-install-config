<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/oht2fq0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

To configure Roles, Departments, and Teams, you will need to:

- First make sure when you log in to osTicket, you are in the Admin Panel.
- To configure Roles, you will click on the Agents tab > Roles > Add New Role > Name your new role > Click on the Permissions tab and then choose your applicable permissions within the Tickets, Tasks, and Knowledgebase options > Save Changes.
- To configure Departments, you will click on the Agents tab > Departments > Add New Department > Name your new department > Follow the options and update the Department Information as needed > Click Create Dept.
- To configure Teams, you will click on the Agents tab > Teams > Add New Team > Name your new team > Click Members tab and decide who you want to be part of the team > Create Team.

</p>
<br />

<p>
<img src="https://i.imgur.com/fJdvxtg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I will show you how to create an agent or worker account. 

- Click on the Agents tab > Add new agent > Fill out agent information in Account tab. Access, Permissions, and Teams tabs.
- Click on Access tab and choose the department and role that the new agent will be filling.
- Click on Permissions tab and give appropriate permissions to the new agent.
- Click on Teams and if applicable, select the team that the new agent will be a part of > Click Create.

To configure a user or customer to the platform, follow these simple steps:

- Make sure you are now in the Agent Panel NOT the Admin Panel.
- Click on Users > Click on Add User > Enter the name and email address for the new user account.
That's it!

</p>
<br />

<p>
<img src="https://i.imgur.com/XY9KrS8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order setup an SLA you will need to go to admin panel > manage > SLA > add new SLA plan > choose the name, grace period, and scheduale. You employer will have a specific set of guidlines and SLA's to follow, so use those when creating new SLA's. To create new help topics asside from the ones currently implemented into osTicket you will need to go to admin panel > manage > help topics > add new help topic > create a topic that can be used such as "personal computer issues" and thats all there is to it.
</p>
<br />
