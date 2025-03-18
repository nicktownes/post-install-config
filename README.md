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
<ul>
- Configure Roles (for grouping permissions)
     <li>Admin Panel -> Agents -> Roles</li>
     <li>Supreme Admin</li>

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
    <li> Admin Panel -> Agents -> Departments</li>
    <li> SysAdmins</li>

- Configure Teams
    <li> Admin Panel -> Agents -> Teams (Pull Agents from different Departments)</li>
    <li> Online Banking</li>
</ul>
</p>
<br />

<p>
<img src="https://docs.osticket.com/en/latest/_images/admin_agents_agents.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <ul>
- Configure Agents (workers)
    <li> Admin Panel -> Agents -> Add New</li>
            <li>Jane (Dept: SysAdmins)</li>
            <li>John (Dept: Support)</li>

- Configure Users (customers)
    <li> Agent Panel -> Users -> Add New</li>
            <li>Karen</li>
            <li> Ken</li>
</ul>
</p>
<br />

<p>
<img src="https://docs.osticket.com/en/latest/_images/schedules1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<ul>
- Configure SLA
     <li>Admin Panel -> Manage -> SLA</li>
        <ul>
           <li>Sev-A (Grace Period: 1 hour, Schedule: 24/7)</li>
           <li>Sev-B (Grace Period: 4 hours, Schedule: 24/7)</li>
           <li>Sev-C (Grace Period: 8 hours, Business Hours)</li>
        </ul>

- Configure Help Topics (For when users create a ticket)
     <li>Admin Panel -> Manage -> Help Topics</li>
        <ul>
           <li>Business Critical Outage</li>
           <li>Personal Computer Issues</li>
           <li>Equipment Request</li>
           <li>Password Reset</li>
           <li>Other</li>
        </ul>
</ul>
</p>
<br />
