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

## ✅ Prerequisites

- A virtual machine environment (e.g., VirtualBox or VMware)
- Supported operating system installed (e.g., Windows Server or Ubuntu)
- osTicket ZIP file downloaded from [https://osticket.com/download/](https://osticket.com/download/)
- PHP installed
- MySQL or MariaDB installed
- IIS or Apache Web Server installed
- Stable internet connection
- Administrative access to the server
- Text editor (e.g., VS Code, Notepad++)
  
CONFIGURATION STEPS

## 🧾 osTicket Ticket Submission Walkthrough

1. **Open a New Ticket**
Creating ticket with our created customer, karen (https://github.com/user-attachments/assets/48e91b93-8187-44da-9871-69c9fb69c400)
   Fill out the support form with the following details:
   - Email: karen@lognpacific.com  
   - Full Name: Karen  
   - Help Topic: Report a Problem  
   - Issue Summary: entire mobile/online banking system is down  

2. **Support Ticket Confirmation**
Photo of successful ticket creation from created user karen (https://github.com/user-attachments/assets/9c514a9e-ab80-41db-a103-8ab573ff32f0)
   A confirmation message appears stating:
   - *"Support ticket request created"*
   - The user is informed a representative will respond if necessary.

3. **Admin Panel - View Ticket List**
logging in os ticket as Anthony, observing seeing new ticket (https://github.com/user-attachments/assets/7e9fd69a-4340-48c3-a538-9ab34a6ab600)
   The admin can view the new ticket submitted by Karen in the Tickets tab.
   - The ticket appears with the subject: *entire mobile/online banking system is down*

4. **Ticket Details Page**
![upgrading ticket priority to sev-a after reviewing ticket](https://github.com/user-attachments/assets/b4672a57-23a0-4f11-80f8-a172d42c3c7b)
   Clicking on the ticket shows full ticket information:
   - User, Email, Department, SLA Plan, Help Topic, and the full message submitted by the user.

5. **Ticket Thread and Technician Updates**
![photo of anthony documenting everything   assigning ticket to jane](https://github.com/user-attachments/assets/432b3c3f-e0f5-496c-bfb6-59b5c18e5deb)
   The conversation thread displays:
   - SLA and help topic updates  
   - Assignment to technician (Jane Doe)  
   - Technician response indicating investigation underway  

