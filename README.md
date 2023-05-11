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

- Roles
- Departments
- Teams
- Allow anyone to create tickets
- Agents (workers)
- Users (customers)
- SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/c1TwgXN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Configure Roles, Admin Panel -> Agents -> Roles

</p>
<br />

<p>
<img src="https://i.imgur.com/71Vt6Ye.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/1KLa64s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/pcNQQ8N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/qFXEAmV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xB9i9Hq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1a. Create "Supreme Admin" role
</p>
<br />

<p>
<img src="https://i.imgur.com/0DgCtN2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/FDDu8Bg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Configure Departments, Admin Panel -> Agents -> Departments, System Administrators
</p>
<br />

<p>
<img src="https://i.imgur.com/t02ZGkD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/RemgJgq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ZcRahXW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Configure Teams, Admin Panel -> Agents -> Teams, Level I Support, Level II Support
</p>
<br />

<p>
<img src="https://i.imgur.com/VuYKe3F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Allow anyone to create tickets, Admin Panel -> Settings -> User Settings, Registration Required: Require registration and login to create tickets (Leave unchecked)
</p>
<br />

<p>
<img src="https://i.imgur.com/6H7Od4V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/17RLsDC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2rkRae7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Configure Agents (workers), Admin Panel -> Agents -> Add New, Jane, John. You can customize their access and permissions based on job position/description.
</p>
<br />

<p>
<img src="https://i.imgur.com/U0NYnDy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/oBr5Tov.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2no2ngv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sFbm9Nn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/nu0VFUl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/FMzGZRQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/zA8TfEp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Configure Users (customers), Agent Panel -> Users -> Add New, Karen, Ken
</p>
<br />

<p>
<img src="https://i.imgur.com/wf3HjhA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/51YvGAv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/x8NcyP2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UCQhX4f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/QtKh7PZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Configure SLA, Admin Panel -> Manage -> SLA, Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://i.imgur.com/7rJHN3N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2dODTWa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/orX9Yl4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bNiMXjd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XDUXL23.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MLRYHHP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Configure Help Topics
, Admin Panel -> Manage -> Help Topics
, Business Critical Outage
, Personal Computer Issues
, Equipment Request
, Password Reset
</p>
<br />
