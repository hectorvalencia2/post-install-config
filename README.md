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



<h2>Configuration Steps</h2>

![Screenshot 2024-03-13 050151](https://github.com/hectorvalencia2/post-install-config/assets/161524174/88b55ebd-2740-4e44-80d0-a007deca4dc4)

Configure Roles
- Admin Panel -> Agents -> Roles
- Supreme Admin+

![Screenshot 2024-03-13 050254](https://github.com/hectorvalencia2/post-install-config/assets/161524174/aea676cf-6092-4571-8d20-af7a6fba2e95)

Configure Departments
- Admin Panel -> Agents -> Departments
- System Administrators

![Screenshot 2024-03-13 050338](https://github.com/hectorvalencia2/post-install-config/assets/161524174/fc954736-45fb-462f-92c5-992391e3cd51)

Configure Teams
- Admin Panel -> Agents -> Teams
  - Level I Support
  - Level II Support

![Screenshot 2024-03-13 050506](https://github.com/hectorvalencia2/post-install-config/assets/161524174/5edf8464-084e-4993-b8c7-caaf74f0aa03)

Allow anyone to create tickets
- Admin Panel -> Settings -> User Settings
- Registration Required: Require registration and login to create tickets 

![Screenshot 2024-03-13 050533](https://github.com/hectorvalencia2/post-install-config/assets/161524174/664c97a5-f13d-4387-a566-0265fdd72b0e)

Configure Agents (workers)
- Admin Panel -> Agents -> Add New
  - Jane and John

![Screenshot 2024-03-13 050615](https://github.com/hectorvalencia2/post-install-config/assets/161524174/28791c06-13a8-4bd9-8e1e-fa2578164c95)

Configure Users (customers)
- Agent Panel -> Users -> Add New
  - Karen and Ken

![Screenshot 2024-03-13 050658](https://github.com/hectorvalencia2/post-install-config/assets/161524174/bebc70d8-d8a9-4f91-8998-b7c84304a1e3)

Configure SLA
- Admin Panel -> Manage -> SLA
  - Sev-A (1 hour, 24/7) - Sev-B (4 hours, 24/7) - Sev-C (8 hours, business hours)

![Screenshot 2024-03-13 050731](https://github.com/hectorvalencia2/post-install-config/assets/161524174/b17f71ea-6aa6-4b93-b72a-56d290917d01)

Configure Help Topics
- Admin Panel -> Manage -> Help Topics
  - Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset

