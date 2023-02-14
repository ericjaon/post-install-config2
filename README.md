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
<img src="https://i.imgur.com/q4DiGZc.png" height="80%" width="80%" alt=""/>
</p>
<p>
Agents are given roles according to the departments to which they have access. Each position has a set of permissions that agents assigned to that role in relation with a department they have access to can tick or uncheck.
</p>
<br />

Allow anyone to create tickets


Admin Panel -> Settings -> User Settings

Registration Required: Require registration and login to create tickets 



<p>
<img src="https://i.imgur.com/tyV0WOE.png" height="80%" width="80%" alt=""/>
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
<img src="https://i.imgur.com/tyV0WOE.png" height="80%" width="80%" alt=""/>
</p>
<p>
An SLA serves as a written agreement between the party receiving the service's advantages and the party providing it. Traditional SLAs specify service expectations between vendors and consumers, but they can also be used within the same organization between divisions. And even if the SLA may be as little as a few phrases or as long as full pages' worth of clauses and requirements, they are always an important part of contemporary service contracts. It's also critical to remember that SLAs should evolve and adapt to accommodate changing business requirements rather than being viewed as being unchangeable. In light of this, SLAs ought to provide a precise framework for implementing changes or alterations during the term of the contract.
</p>
<br />

Configure Help Topics


Admin Panel -> Manage -> Help Topics

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset


<p>
<img src="https://i.imgur.com/4dCjyoa.png" height="80%" width="80%" alt=""/>
</p>
<p>
A help topic is a separate document in a user guide or software manual, which is created using a modular approach often called "topic-based authoring" in the technical communication area. If you think about an ordinary document created with office text editor, the notion of a topic maps to the notion of a "section" or a "sub-section".

Typically, a help topic is a pretty small chunk of content that focuses on a single subject and can be consumed separately from the remaining part of the same user manual. Another difference is that an office document is linear, while a topic-based manual is a non-linear set of separate documents (help topics) with links and navigation. A nice benefit the topic-based approach gives you is the ability to re-use topics in multiple places of a user manual, as well as assembling several different outputs from the same topic set.
</p>
<br />



