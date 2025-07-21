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

### 🧩 Admin Panel Configuration Steps

#### 1. Acknowledge Panel Differences
- **Admin Panel**: Full configuration access
- **Agent Panel**: Ticket handling interface only

#### 2. Configure Roles (for permission grouping)
Navigate to:  
`Admin Panel → Agents → Roles`
- Example Roles:
  - `Supreme Admin`
  - `SysAdmins`

#### 3. Configure Departments (Ticket Visibility & Routing)
Navigate to:  
`Admin Panel → Agents → Departments`
- Example Departments:
  - `Help Desk`
  - `SysAdmins`
  - `Networking`

#### 4. Configure Teams (Cross-department agent groups)
Navigate to:  
`Admin Panel → Agents → Teams`
- Example Team:
  - `Online Banking`

#### 5. Adjust User Ticket Permissions
Navigate to:  
`Admin Panel → Settings → User Settings`
- **Uncheck:**  
  `Unregistered users can create tickets`
- **Enable:**  
  `Registration Required` — Forces users to register/login before submitting tickets

#### 6. Add Agents (System Users/Workers)
Navigate to:  
`Admin Panel → Agents → Add New`
- Example Agents:
  - `Jane` (Dept: SysAdmins)
  - `John` (Dept: Support)

## 👥 Customer & Ticketing Configuration (Post-Install Setup)

After initial installation and admin setup, configure the following key components to enable structured customer interaction and ticket categorization.

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

<p>
<img src="![image](https://github.com/user-attachments/assets/90f10dcf-ab9c-478c-b3a6-28c59e7f4e1a)

" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
