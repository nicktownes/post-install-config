<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>
    <ul>
        <li> Configure roles for grouping permissions</li>
        <li> Configured Deparments and Teams</li>
        <li> Configured Agents(workers) and Users(customers)</li>
        <li> Created Service Level Agreements(SLAs)</li>
        <li> Created Help Topics</li>
    </ul>
<h2>Configuration Steps</h2>

<p>
<img src="https://docs.osticket.com/en/latest/_images/admin_agents_roles.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Configure Roles (for grouping permissions)
    Admin Panel -> Agents -> Roles
    Supreme Admin

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
    Admin Panel -> Agents -> Departments
    SysAdmins

- Configure Teams
    Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
    Online Banking
</p>
<br />

<p>
<img src="https://docs.osticket.com/en/latest/_images/admin_agents_agents.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Configure Agents (workers)
    Admin Panel -> Agents -> Add New
          Jane (Dept: SysAdmins)
          John (Dept: Support)

- Configure Users (customers)
    Agent Panel -> Users -> Add New
          Karen
          Ken
</p>
<br />

<p>
<img src="https://docs.osticket.com/en/latest/_images/schedules1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Configure SLA
    Admin Panel -> Manage -> SLA
          Sev-A (Grace Period: 1 hour, Schedule: 24/7)
          Sev-B (Grace Period: 4 hours, Schedule: 24/7)
          Sev-C (Grace Period: 8 hours, Business Hours)

- Configure Help Topics (For when users create a ticket)
    Admin Panel -> Manage -> Help Topics
          Business Critical Outage
          Personal Computer Issues
          Equipment Request
          Password Reset
          Other
</p>
<br />
