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

## 🛠️ osTicket Post-Installation Configuration (Admin Panel Setup)

Once osTicket is installed, use the Admin Panel to configure roles, departments, agents, and user access settings for your helpdesk system.

### 🔐 Access Panels
- **Admin/Analyst Login Page:**  
  [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End User Portal:**  
  [http://localhost/osTicket](http://localhost/osTicket)

---
## 🔧 Admin Panel Configuration (Roles, Teams, Agents)

---

### 🧩 Role & Permission Setup

#### 1. Acknowledge Agent Panel vs Admin Panel
- **Agent Panel:** Used by staff to manage and respond to tickets.
- **Admin Panel:** Used for managing system settings, users, SLAs, help topics, and permissions.

#### 2. Configure Roles
Navigate to:  
`Admin Panel → Agents → Roles`
- Example Role: `Supreme Admin`

#### 3. Configure Departments
Navigate to:  
`Admin Panel → Agents → Departments`
- Example Department: `SysAdmins`  
> Used to assign tickets to specific technical groups or support categories.

#### 4. Configure Teams
Navigate to:  
`Admin Panel → Agents → Teams`  
> Teams can include agents from multiple departments.

- Example Team: `Online Banking`

#### 5. Adjust User Ticket Permissions
Navigate to:  
`Admin Panel → Settings → User Settings`

- **Uncheck:** `Unregistered users can create tickets`
- **Enable:** `Registration Required` to force user authentication before ticket creation

---

### 👥 Add Agents (Support Staff)
Navigate to:  
`Admin Panel → Agents → Add New`

- `Jane` — Dept: `SysAdmins`
- `Anthony` — Dept: `Support`

> These agents will be assigned tickets based on department or team routing.

---

### 7. Configure Users (Customers)
Navigate to:  
`Agent Panel → Users → Add New`

- Example Users:
  - `Karen`
  - `Ken`

> These users represent customers who can submit and track tickets in the osTicket system.

---

### 8. Configure SLA (Service Level Agreements)
Navigate to:  
`Admin Panel → Manage → SLA`

- **Sev-A**  
  - Grace Period: `1 hour`  
  - Schedule: `24/7`

- **Sev-B**  
  - Grace Period: `4 hours`  
  - Schedule: `24/7`

- **Sev-C**  
  - Grace Period: `8 hours`  
  - Schedule: `Business Hours`

> SLAs define response time guarantees based on ticket severity or priority, improving accountability and service quality.

---

### 9. Configure Help Topics (Ticket Categories)
Navigate to:  
`Admin Panel → Manage → Help Topics`

- **Help Topics List:**
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  - Other

> Help topics streamline ticket routing and enable departments to triage and respond more effectively.

---

✅ *These configurations ensure your osTicket helpdesk is aligned with organizational support priorities and ticket workflows, access control, and secure ticket submission policies for a functional and scalable osTicket helpdesk.*- Item 1

<h2>Configuration Steps</h2>

Image 1
Creating ticket with our created customer, karen (https://github.com/user-attachments/assets/48e91b93-8187-44da-9871-69c9fb69c400)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
Photo of successful ticket creation from created user karen (https://github.com/user-attachments/assets/9c514a9e-ab80-41db-a103-8ab573ff32f0)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
logging in os ticket as Anthony, observing seeing new ticket (https://github.com/user-attachments/assets/7e9fd69a-4340-48c3-a538-9ab34a6ab600)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />



![upgrading ticket priority to sev-a after reviewing ticket](https://github.com/user-attachments/assets/b4672a57-23a0-4f11-80f8-a172d42c3c7b)









![photo of anthony documenting everything   assigning ticket to jane](https://github.com/user-attachments/assets/432b3c3f-e0f5-496c-bfb6-59b5c18e5deb)




