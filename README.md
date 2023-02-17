# post--Install-config<p align="center">
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

- Configure Agents
- Configure Users
- Configure SLA's
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/0pS3UAZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating two teams, L1 & L2 Support, created two Agents, Vinny & Larry. Each was assigned to a different team.
</p>
<br />

<p>
<img src="https://i.imgur.com/0gEIaxM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create two users, Gina Gahlic and Carmela Cookie, that will serve as end users relying on osTicket agents when encountering system issues.
</p>
<br />

<p>
<img src="https://i.imgur.com/JTNKvgs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure three Service Level Agreements (SLA) with three different categories and response times. The first one, SEV-A, has to be resolved within 1-hour in  24-hr period. The second one, SEV-B, must be resolved within 4-hours in a 24-hour period, and the last one, SEV-C, must be resolved within 8 business hours. The SLA's for your organization will be different, but the key point is that these SLA's are agreements that determine the timely manner that an issue must be resolved so that your organization is meeting its commitments.
</p>
<br />

<p>
<img src="https://i.imgur.com/145552h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create four categories (Business Critical Outage; Personal Computer Issues; Equipment Issues; & Password Reset) for end users to utilize when reporting an issue.
</p>
<br />
