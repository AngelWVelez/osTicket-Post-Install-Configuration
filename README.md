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

 Configure:
- Roles
- Departments
- Teams
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/yPUFGFg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles (for grouping permissions):
  
- Admin Panel -> Agents -> Roles

- Create roles

</p>
<br />

<p>
<img src="https://i.imgur.com/AtxQ45C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking):
  
- Admin Panel -> Agents -> Departments
  
- Create Agents

</p>
<br />

<p>
<img src="https://i.imgur.com/SzsM9UZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams:
  
- Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
  
- Create Team

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers):
  
- Admin Panel -> Agents -> Add New

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers):
  
- Agent Panel -> Users -> Add New

</p>
<br />

<p>
<img src="https://i.imgur.com/Ces3FYM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA:
  
 - Admin Panel -> Manage -> SLA

</p>
<br />

<p>
<img src="https://i.imgur.com/5sANMq9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics (For when users create a ticket):
  
- Admin Panel -> Manage -> Help Topics

</p>
<br />
