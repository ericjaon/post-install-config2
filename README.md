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

(Post Installation Setup)

Configure Roles

Admin Panel -> Agents -> Roles

Supreme Admin

Configure Departments

Admin Panel -> Agents -> Departments

System Administrators

Configure Teams

Admin Panel -> Agents -> Teams

Level I Support
Level II Support


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/q4DiGZc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents are given roles according to the departments to which they have access. Each position has a set of permissions that agents assigned to that role in relation with a department they have access to can tick or uncheck.
</p>
<br />

Allow anyone to create tickets


Admin Panel -> Settings -> User Settings

Registration Required: Require registration and login to create tickets 



<p>
<img src="https://i.imgur.com/tyV0WOE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
anonymous users now have the ability to create tickets, despite whether or not they're in the sysytem.
</p>
<br />
Configure SLA


Admin Panel -> Manage -> SLA

Sev-A (1 hour, 24/7)

Sev-B (4 hours, 24/7)

Sev-C (8 hours, business hours)



<p>
<img src="https://i.imgur.com/tyV0WOE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
An SLA serves as a written agreement between the party receiving the service's advantages and the party providing it. Traditional SLAs specify service expectations between vendors and consumers, but they can also be used within the same organization between divisions. And even if the SLA may be as little as a few phrases or as long as full pages' worth of clauses and requirements, they are always an important part of contemporary service contracts. It's also critical to remember that SLAs should evolve and adapt to accommodate changing business requirements rather than being viewed as being unchangeable. In light of this, SLAs ought to provide a precise framework for implementing changes or alterations during the term of the contract.
</p>
<br />
