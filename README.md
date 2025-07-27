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
![image](https://github.com/user-attachments/assets/b772e696-73c3-4389-8d4d-776e4a594fe7)
  Fill out the support form with the following details:
   - Email: karen@lognpacific.com  
   - Full Name: Karen  
   - Help Topic: Report a Problem  
   - Issue Summary: entire mobile/online banking system is down  

2. **Support Ticket Confirmation**
![image](https://github.com/user-attachments/assets/64049df0-a2ad-45b0-a1a7-8ea539c2565f)
  A confirmation message appears stating:
- *"Support ticket request created"*
   - The user is informed a representative will respond if necessary.

3. **Admin Panel - View Ticket List**
![image](https://github.com/user-attachments/assets/7a5fa555-8294-4db0-a7f4-ec4721e4e85b)
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

