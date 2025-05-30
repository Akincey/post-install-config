<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/5fa784c3-42ac-4e7c-9004-0b10822dd1d3)


<p>
</p>
<p>
This screenshot shows me actively working a ticket from the admin panel. Through this interface, I configured departments, created teams, assigned agents, and defined their roles and permissions to ensure proper access control and workflow management.
</p>
<br />

<p>

  ![image](https://github.com/user-attachments/assets/e2b7040a-78eb-49e2-83bd-fb0d56ca3865)


</p>
<p>
I created an agent profile for Jane Doe, assigning her to the Sys Admins department and granting her full access permissions. This level of access was necessary to allow her to manage tickets, configure system settings, and support administrative operations without limitations
</p>
<br />

<p>
</p>
<p>

  ![image](https://github.com/user-attachments/assets/e8d20149-b99b-4734-8292-f170a9c3c900)

I created three distinct SLA (Service Level Agreement) policies to define the severity levels and corresponding response times for tickets:

Sev-A (Major): 1-hour grace period, 24/7 support schedule
Sev-B (Moderate): 4-hour grace period, weekday-only (24/1) support schedule
Sev-C (Minor): 8-hour grace period, 24/7 support schedule
These SLAs ensure that ticket prioritization aligns with issue severity and business impact, supporting efficient and timely resolution.
</p>
<br />
