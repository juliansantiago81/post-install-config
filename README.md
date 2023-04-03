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

- Log in to the admin panel.
- Go to the Agents tab next to the Emails tab.
- To set up Roles, you will go to Agents > Roles > Add new role > Create a name for the role > Choose applicable permissions.
- To set up Departments, you will go to Departments (next to Roles under the Settings tab) > Add New Department > Create a name for the department > Follow the options down the list as required.
- To set up Teams, you will go to Teams > Select the name of the team > Choose who you want to be part of the team.

</p>
<br />

<p>
<img src="https://i.imgur.com/fJdvxtg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I will tell you how to create the agent or worker account. First go to the Agents tab in the upper level next to emails > agents on the tier below > add new agent > create a name and email address as well as a username and password > choose which department and role you need this person to fill > give appropriate permissions > select the team if any that this person will be in. In order to add a users or cusomer, its very easy just got to agent panel > users > add user > create a name an email and thats it.
</p>
<br />

<p>
<img src="https://i.imgur.com/XY9KrS8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order setup an SLA you will need to go to admin panel > manage > SLA > add new SLA plan > choose the name, grace period, and scheduale. You employer will have a specific set of guidlines and SLA's to follow, so use those when creating new SLA's. To create new help topics asside from the ones currently implemented into osTicket you will need to go to admin panel > manage > help topics > add new help topic > create a topic that can be used such as "personal computer issues" and thats all there is to it.
</p>
<br />
