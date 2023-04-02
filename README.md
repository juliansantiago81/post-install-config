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

<h2>Post-Install Configuration Objectives</h2>

- Configure:
- Roles, departments, teams
- Workers, customers, (Agents, users) respectively 
- Help topics
- SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/oht2fq0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure the roles, departments and teams, you need to be logged into the admin panel and make your way to the agents option next to the emails option. Following from there in order to setup roles you will need to go to the Agents > roles > add new role > create a name for this role > choose the applicable permissions in that tab. Similarly to the role setup is for the departments. In the dpartments tab next to the roles tab go there > add new department > from there choose a name for the department you want to create then follow the rest of the options down the list as required for your specific purpose. Finally he teams is setup in almost the same way, go to the teams tab > select the name of the team > choose who you want to be part of your team.
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
