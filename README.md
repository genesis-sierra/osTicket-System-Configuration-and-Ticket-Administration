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
Go to the Support Center page of osTicket as the user Daniel Ortiz and open a new ticket under Report a Problem. Enter the issue summary “Online Banking System Down” and describe the outage details. Then click Create Ticket to submit it for investigation.
<img width="1919" height="1079" alt="Screenshot 2025-08-20 195126" src="https://github.com/user-attachments/assets/0533c35a-a61a-4f0f-943c-e3db28c7e33c" />

<p align="center">
After submitting the form, you should now see a confirmation message stating Support ticket request created:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 195217" src="https://github.com/user-attachments/assets/202752b3-4326-4915-87bd-9be8da7f81a2" />

<p align="center">
Log in to osTicket as the agent Jordan using the provided credentials:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 195934" src="https://github.com/user-attachments/assets/ae2859cd-1c59-46a6-993b-7fc1d41078b1" />

<p align="center">
Navigate to the Tickets section and locate the ticket created by Daniel Ortiz to review its details and submission information:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 200138" src="https://github.com/user-attachments/assets/55b12a8d-5232-497c-82d5-407f2c31e4a6" />

<p align="center">
Update the SLA Plan to Sev-A to ensure critical issues are prioritized with the shortest response and resolution time:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 200440" src="https://github.com/user-attachments/assets/9adf7596-71d2-4d7c-8982-ad4432418cea" />

<p align="center">
Update the Help Topic to Business Critical Outage to categorize this issue as a major system failure requiring immediate response:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 200556" src="https://github.com/user-attachments/assets/5fd9bb6c-3d0e-4eaf-bbd1-6175d6b26686" />

<p align="center">
Assign the ticket to the Online Banking Team since the issue affects the online banking portal and requires their expertise:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 201430" src="https://github.com/user-attachments/assets/85cbf362-cba9-4521-b49a-57a274be9733" />

<p align="center">
Click on Agents, navigate to Teams, and then select Members to view all active agents assigned to that team:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 201125" src="https://github.com/user-attachments/assets/9f5bcaa9-adcc-47ed-b937-216dbc9affb9" />

<p align="center">
Now go back to the osTicket mainpage and login as Taylor:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 201715" src="https://github.com/user-attachments/assets/9ee33186-4fa2-4233-babf-188648c98b93" />

<p align="center">
Reassign the ticket to the login user Taylor Bennett with a provided comment:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 201955" src="https://github.com/user-attachments/assets/41e3f6d3-556b-46a0-af71-e525437b9db3" />

<p align="center">
Go to the Ticket Thread to review all replies and updates that have been made:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 202127" src="https://github.com/user-attachments/assets/2e3c370f-9808-4fda-98ba-9b0d49a7e92f" />

<p align="center">
Post a reply to update the team on your next steps and explain how you plan to investigate the issue further:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 202520" src="https://github.com/user-attachments/assets/eb584fc8-83a0-4f72-ada4-5e001424db95" />

<p align="center">
Post a new response confirming that the issue has been resolved and briefly explain the steps taken to fix it:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 202858" src="https://github.com/user-attachments/assets/07f12383-c441-4d99-a2c0-1a45bb0328de" />

<p align="center">
Close the ticket and update the status to Resolved:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 203033" src="https://github.com/user-attachments/assets/ad4c8090-dec7-4185-b792-3b25954be8fc" />

<p align="center">
Confirm the ticket was successfully closed by navigating to the Tickets section and selecting the Closed tab:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 203202" src="https://github.com/user-attachments/assets/32272446-f275-4047-9754-38935ac55a4c" />

<p align="center">
Back in the agent panel login in as an administrator and create a new user named Olivia Hayes with the email address olivia.hayes.user@gmail.com:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 204149" src="https://github.com/user-attachments/assets/0cf5f108-81a9-4e41-8293-6a239c8386cb" />

<p align="center">
Create a new ticket with the user Olivia Hayes and classify the help topic in other with a brief summary of the issue:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 204252" src="https://github.com/user-attachments/assets/dec2e181-76d4-4d7a-9c65-127999132e96" />

<p align="center">
Log in to osTicket as Jordan Alvarez and provide help desk support by updating the ticket thread, classifying the issue as Sev-C, and include detail replies explaining as to how the problem was resolved:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 205504" src="https://github.com/user-attachments/assets/02f0e278-cdfa-493d-9632-b962da193bb0" />

<p align="center">
Add an internal note explaining that the customer was impatient and that you responded with empathy to address their concerns:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 210102" src="https://github.com/user-attachments/assets/c356e4e6-4d59-4540-b0e2-554cbad5f021" />

<p align="center">
Close out the ticket with a brief comment as to how it was fixed:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 210243" src="https://github.com/user-attachments/assets/b38a75c4-d9e9-4eae-b7b5-97b9a59f501b" />

<p align="center">
Observe that a new ticket was created by Daniel Ortiz and assist in resolving it while logged in as Jordan Alvarez:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 211719" src="https://github.com/user-attachments/assets/005b1502-28a9-43e6-8765-d8941f722162" />

<p align="center">
Post a reply explaining how the issue was resolved and close out the ticket:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 212116" src="https://github.com/user-attachments/assets/0e47a270-9fe2-4813-aa95-1bc386b46d4f" />

<p align="center">
Back in the Agent Panel as an administrator review the ticket activity that was completed today:
<img width="1919" height="1079" alt="Screenshot 2025-08-20 213415" src="https://github.com/user-attachments/assets/020faf59-1299-4ecb-8688-dabee0eac98c" />
