<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation</h1>
This tutorial outlines the post installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Post Installation Tasks</h2>

- Configure Roles
  - Admin->Agents->Roles
  - Supreme Admin
- Configure Departments
  - Admin->Agents->Roles
  - Supreme Admin
- Configure Teams
  - Admin Panel -> Agents -> Teams
  - Level I Support
  - Level II Support
- Allow anyone to create tickets
  - Admin Panel -> Settings -> User Settings
  - Registration Required: Require registration and login to create tickets
- Configure Agents (workers)
  - Admin Panel -> Agents -> Add New
    - Jane
    - John
- Configure Users (customers)
  - Agent Panel -> Users -> Add New
    - Karen
    - Ken
- Configure SLA
  - Admin Panel -> Manage -> SLA
    -  Sev-A (1 hour, 24/7)
    - Sev-B (4 hours, 24/7)
    - Sev-C (8 hours, business hours)
- Configure Help Topics
  - Admin Panel -> Manage -> Help Topics
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset






<h2> Post Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Ai6TA4d.png" height="80%" width="80%" alt="Updating Roles"/>
</p>
<p>
I updated the permissions for the Supreme Admin Role.
</p>
<br />

<p>
<img src="https://i.imgur.com/KuH5iEq.png" height="80%" width="80%" alt="Configure Users"/>
</p>
<p>
I created some users to be able to create trouble tickets.
</p>
<br />

</p>
<p>
Here is an example of a helpdesk ticket that was created by Karen.
</p>
<br />
<p>
<img src="https://i.imgur.com/K7qnip9.png" height="80%" width="80%" alt="Configure SLA"/>
</p>
<p>
I added some additional SLA's using the Administrative portal.
</p>
<br />

<img src="https://i.imgur.com/yFVTmzV.png" height="80%" width="80%" alt="Workflow of a Resolved Ticket"/>
</p>
<p>
I updated the priority level and SLA of the ticket. I assigned the ticket to John and he resolved it. 

