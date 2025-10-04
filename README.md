<h1>osTicket: System Configuration and Ticket Administration</h1>
<h2>Description</h2>
This project demonstrates my ability to use a professional ticketing help desk system to manage support requests, assign SLAs, escalate issues, and resolve tickets in a structured IT environment. The platform used is osTicket, a widely recognized open-source IT support tool, deployed in a lab environment to simulate real-world IT service desk operations.

<h2>Skills Used</h2>

- <b>SLA Management</b>
- <b>Ticket Workflow Management</b>
- <b>User & Role Administration</b>

<h2>Technology Used</h2>

- <b>osTicket (ticketing/help desk platform)</b>

<h2>Technology Installed</h2>
- <b>IIS (Internet Information Services) (web server)</b>
- <b>PHP (runtime for osTicket)</b>
- <b>MySQL (ticket database)</b>
- <b>HeidiSQL (database management tool)</b>

<h2>Cloud Platform Used</h2>

- <b>Microsoft Azure</b>

<h2>Environments Used</h2>

- <b>Windows 10 (22H2)</b>

<h2>Services Used</h2>

- <b>Virtual Machine (osTicket-vm: Windows 10)</b>

<h2>Project walk-through:</h2>

<p align="center">
Start by opening up the Admin Control Panel in osTicket:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 180626" src="https://github.com/user-attachments/assets/3b8e3dba-f065-4bc6-aae0-5f8652e73653" />

<p align="center">
Navigate to the Agents tab, select Roles and choose Expanded Access to proceed:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 180831" src="https://github.com/user-attachments/assets/971a7489-b8c0-403e-8111-cf34eaf778d7" />

<p align="center">
On the Expanded Access screen, you’ll now see a full list of all the ticket-related permissions available for this role:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 180943" src="https://github.com/user-attachments/assets/2e95b1c5-1bd0-4d09-bcbe-be5b1f0659a6" />

<p align="center">
When selecting the All Access role, you’ll now notice that every permission checkbox is enabled, granting this role full access to all ticket operations and administrative actions:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 181028" src="https://github.com/user-attachments/assets/c374b536-bcd5-4ead-9a12-87a8ff5b219f" />

<p align="center">
Navigate to the Agents tab and select Departments. You will now see a list of all available departments within the system:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 181326" src="https://github.com/user-attachments/assets/fda66032-ad66-497c-a6a6-d491cfd16159" />

<p align="center">
Create a new department named “SysAdmins” and designate it as a top-level (parent) department:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 181650" src="https://github.com/user-attachments/assets/61b6402f-1add-4deb-9111-681f0ee1ff0d" />

<p align="center">
You will now see that the department has been successfully added to the system:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 181720" src="https://github.com/user-attachments/assets/4c128579-acfd-4806-8c89-931b4be2873a" />

<p align="center">
