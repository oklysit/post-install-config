<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. It will cover the creation of several sample roles, departments, teams, workers, end users, SLA and Help topics to familiarize yourself with the ticketing system environment. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Post-Install Configuration Objectives</h2>

- Configure [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
- Configure [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
- Configure [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html)
- Allow anyone to create tickets
- Configure [Agents (Workers)](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
- Configure [Users (Customers)](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
- Configure [SLA (Service Level Agreement)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
  
Configure [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
> - Admin Panel -> Agents -> Roles
> - Create a Supreme Admin with all permissions

Configure [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
> - Admin Panel -> Agents -> Departments
> - Create a sample System Administrators Department

Configure [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html)
> - Admin Panel -> Agents -> Teams
> - Create sample Teams, eg:
>> - Level I Support
>> - Level II Support

Allow anyone to create tickets
> - Admin Panel -> Settings -> User Settings
> - Registration Required: Require registration and login to create tickets

Configure [Agents (Workers)](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
> - Admin Panel -> Agents -> Add New
> - Create sample workers e.g. Jane, John, etc

Configure [Users (Customers)](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
> - Agent Panel -> Users -> Add New
> - Create sample end users who might create tickets e.g. Ken, Karen, etc

Configure [SLA (Service Level Agreement)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)
> - Admin Panel -> Manage -> SLA
> - Create sample agreements such as:
>> - Sev-A (1 hour, 24/7)
>> - Sev-B (4 hours, 24/7)
>> - Sev-C (8 hours, business hours)

Configure Help Topics
> - Admin Panel -> Manage -> Help Topics
> - Create sample topics for end users to choose when creating tickets, such as:
>> - Business Critical Outage
>> - Personal Computer Issues
>> - Equipment Request
>> - Password Reset

</p>
