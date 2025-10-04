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
On the Agents tab go to Teams and create a new team named Online Banking:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 182136" src="https://github.com/user-attachments/assets/1db6b693-f411-4010-ad8f-4a2f60ad8854" />

<p align="center">
You will now see the team name Online Banking reflected on the teams tab:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 182212" src="https://github.com/user-attachments/assets/cabefbd6-e922-4f86-8f9a-f63c495a5eb4" />

<p align="center">
Now go to Settings under the Users tab and make sure Registration Required is unchecked to allow any user to create tickets without needing to log in:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 182327" src="https://github.com/user-attachments/assets/26b45a7d-01b8-418c-b2f0-a0b0df845966" />

<p align="center">
On the Agents tab, create a new agent:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 182452" src="https://github.com/user-attachments/assets/6322b766-1f06-413c-931e-5462c02df1f6" />

<p align="center">
Assign the agent to the SysAdmins department with the Supreme Admin role for full system access:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 183147" src="https://github.com/user-attachments/assets/5fd556a2-c1a1-4463-bc77-293f27d1e189" />

<p align="center">
Name this agent Taylor Bennett with the email address taylor.bennett.it@gmail.com:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 183509" src="https://github.com/user-attachments/assets/63b12143-5404-4e47-8c99-9c2a71390df5" />

<p align="center">
Create another new agent and name this one Jordan Alvarez with the email address jordan.alvarez.it@gmail.com:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 183855" src="https://github.com/user-attachments/assets/472044d9-ff11-4c05-afcf-965346990996" />

<p align="center">
Grant this agent access to the Support department and assign them the Expanded Access role:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 183931" src="https://github.com/user-attachments/assets/9e85cdbe-7816-489e-8793-c0a881d02c3c" />

<p align="center">
You will now see all active and concurrent agents listed under the Agents tab:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 184005" src="https://github.com/user-attachments/assets/3ff3d550-f5aa-4c94-9b2c-7d0ee0a329a5" />

<p align="center">
Now navigate to the Agent panel, select Users, click Add User, and create a new user named Daniel Ortiz with the email address daniel.ortiz.user@gmail.com:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 185140" src="https://github.com/user-attachments/assets/38393005-1daa-4fab-a7f8-51ac485f275f" />

<p align="center">
You should now see the user Daniel Ortiz added on the user directory Agent Panel:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 185122" src="https://github.com/user-attachments/assets/77624414-aa7e-4911-b2f1-009aee927e0f" />

<p align="center">
Return to the Admin Panel, navigate to the Manage tab, and select SLA:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 185235" src="https://github.com/user-attachments/assets/1984e755-9dc0-48ce-838f-8c25ce99aa3e" />

<p align="center">
Add a new SLA Plan named Sev-A and set the grace period to 1 hour with a 24/7 assigned schedule to ensure continuous coverage:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 185443" src="https://github.com/user-attachments/assets/8bef72c1-3c62-4034-a930-25191da36312" />

<p align="center">
Create two additional Service Level Agreements: Sev-B with a 4-hour grace period and a 24/7 schedule, and Sev-C with an 8-hour grace period and a Monday–Friday 8 AM–5 PM (with U.S. Holidays) schedule:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 185752" src="https://github.com/user-attachments/assets/aa531af7-5b1f-4df1-970d-17514ee1f24f" />

<p align="center">
Now scroll to the Help Topics section under the Manage tab this will show all active topics associated in the system:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 185844" src="https://github.com/user-attachments/assets/197f4f2c-ebd0-48b0-8e56-57cef2df9a5a" />

<p align="center">
Add a new Help Topic titled Business Critical Outage and set its parent topic to Report a Problem:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 185949" src="https://github.com/user-attachments/assets/92bc8769-0f69-4cd1-82ae-22372abe660e" />

<p align="center">
Make another Help Topic titled Equipment Request and set its parent topic to General Inquiry:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 190212" src="https://github.com/user-attachments/assets/76bafd4d-8b51-4d42-ad79-d37056e96c54" />

<p align="center">
Create additional Help Topics titled Report a Problem / Password Reset, Report a Problem / Personal Computer Issues, and General Inquiry / Other:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 190411" src="https://github.com/user-attachments/assets/061170bf-c091-407a-89eb-d0d68f4aa49c" />

<p align="center">
