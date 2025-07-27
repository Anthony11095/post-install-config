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

CONFIGURATION STEPS

Image 1.

Creating ticket with our created customer, karen (https://github.com/user-attachments/assets/48e91b93-8187-44da-9871-69c9fb69c400)

</p>
<p>
## 📋 Help Desk Ticket Submission - Issue Example

This document outlines the steps to submit a support ticket using the internal help desk system (osTicket).

### 🛠️ Instructions

1. Open the internal help desk portal (e.g. `http://yourdomain.com/helpdesk`).
2. Fill in the **Email Address** field with your corporate email.
3. Enter your **Full Name**.
4. (Optional) Add your **Phone Number** and **Extension**.
5. Under **Help Topic**, select:  
   `Report a Problem`
6. In the **Issue Summary** field, describe the issue clearly.  
   Example:  
</p>
<b

Image 2.

Photo of successful ticket creation from created user karen (https://github.com/user-attachments/assets/9c514a9e-ab80-41db-a103-8ab573ff32f0)

</p>
<p>
## 📷 Screenshot: osTicket - Ticket Confirmation Page

### 🖼️ Description

This screenshot shows the **ticket confirmation screen** from the `osTicket` Support Ticket System, as accessed through the browser. The screen confirms that a support ticket has been successfully created and submitted.

---

### ✅ Observations

- The message displayed confirms ticket creation:
</p>
<br />

Image 3.

logging in os ticket as Anthony, observing seeing new ticket (https://github.com/user-attachments/assets/7e9fd69a-4340-48c3-a538-9ab34a6ab600)

</p>
<p>
## 📸 Screenshot: osTicket Admin Panel – Ticket List View

### 🖥️ Description

This screenshot displays the **Tickets** section of the **osTicket Admin Panel**, showing submitted support tickets.

---

### 🔎 What’s Visible

- Logged-in user: `Anthony`
- Visible navigation tabs:
  - Dashboard
  - Users
  - Tasks
  - Tickets (active tab)
  - Knowledgebase
- Ticket filter set to: `Open` tickets
- Total tickets displayed: 2

---

### 📋 Ticket Table Details

| Ticket ID | Last Updated       | Subject                                        | From       | Priority | Assigned To |
|-----------|--------------------|------------------------------------------------|------------|----------|--------------|
| 593503    | 4/3/25 12:08 AM    | entire mobile/online banking system is down   | karen      | Normal   | (blank)      |
| 196357    | 3/21/25 8:36 PM    | osTicket Installed!                            | osTicket Support | Normal | (blank)      |

---

### 📌 Notes

- The first ticket, submitted by user `karen`, indicates a critical service issue affecting the mobile/online banking system.
- The second ticket is likely a system-generated message confirming successful installation of osTicket.
- The system is functioning as expected — capturing and listing incoming tickets properly.
- The `Assigned To` column is blank, meaning no staff have yet been assigned to respond.

---

### ⚙️ System Info

- Powered by: **osTicket**
- Copyright footer: `© 2006–2025 Anthony’s Help Desk`
- Accessed via browser with visible tabs indicating:
  - Installation labs/checklists
  - osTicket post-install docs
  - Anki and ASVAB prep tools

---
</p>
<br />
Image 4.

![upgrading ticket priority to sev-a after reviewing ticket](https://github.com/user-attachments/assets/b4672a57-23a0-4f11-80f8-a172d42c3c7b)

## 📝 Screenshot: osTicket Ticket View – Critical Service Disruption

### 🎯 Ticket Overview

This screenshot shows the detailed view of a support ticket inside the **osTicket Admin Panel**. The ticket highlights a reported issue with the mobile/online banking system being inaccessible.

---

### 📄 Ticket Metadata

| Field              | Value                                 |
|-------------------|---------------------------------------|
| **Ticket ID**      | #593503                               |
| **Subject**        | entire mobile/online banking system is down |
| **Status**         | Open                                  |
| **Priority**       | Normal                                |
| **Department**     | Support                               |
| **Create Date**    | 4/3/25 12:08 AM                        |
| **Assigned To**    | Unassigned                            |
| **SLA Plan**       | SEVA                                  |
| **Due Date**       | 4/3/25 5:00 PM                         |
| **User**           | karen                                 |
| **Email**          | karen@lognpacific.com                 |
| **Source**         | Web                                   |
| **Help Topic**     | Report a Problem                      |
| **Last Message**   | 4/3/25 12:08 AM                        |
| **Last Response**  | —                                     |

---

### 💬 Message Thread

> **karen posted 4/3/25 12:08 AM**  
> *"My employees are reporting that users are no longer able to access the online banking portal. The ones who can occasionally access it, cannot log in."*

---

### ⚠️ Issue Summary

This is a **critical service-impacting issue** reported by the user. The mobile/online banking system is down and inaccessible to end users. No technician has yet been assigned to the ticket, and the SLA deadline is later the same day.

---

### 🛠️ Action Items

- Assign a technician to investigate and resolve the outage.
- Check system logs for authentication or availability failures.
- Communicate updates to the requester (`karen@lognpacific.com`).
- Ensure the issue is resolved before the SLA due time (4/3/25, 5:00 PM).

---
Image 5.
![photo of anthony documenting everything   assigning ticket to jane](https://github.com/user-attachments/assets/432b3c3f-e0f5-496c-bfb6-59b5c18e5deb)

## 🧾 Ticket #593503 – Online/Mobile Banking System Outage

### 📍 Issue Summary

**Subject**: `entire mobile/online banking system is down`  
**Reported by**: karen (karen@lognpacific.com)  
**Date Created**: 4/3/25 at 12:08 AM  
**Ticket Status**: Open → Resolved  
**SLA Plan**: Upgraded to **SevA (1 hour SLA)**  
**Assigned Technician**: Jane Doe  
**Category**: Business Critical Outage

---

### 🧠 Description

Customer reported a widespread issue where users are unable to access the online banking portal. Some users were intermittently able to access the system but could not log in.

---

### 📋 Timeline of Events

| Timestamp        | User               | Action                                                                 |
|------------------|--------------------|------------------------------------------------------------------------|
| 4/3/25 12:08 AM  | karen              | Ticket created describing outage.                                     |
| 4/3/25 12:26 AM  | Anthony Hamilton   | SLA Plan updated. Comment: "Wide impact. Customers unable to do online banking." |
| 4/3/25 12:26 AM  | Anthony Hamilton   | SLA changed: `Default SLA (18h)` → `SevA (1h)`                        |
| 4/3/25 12:28 AM  | Anthony Hamilton   | Help Topic changed: `Report a Problem` → `Business Critical Outage`   |
| 4/3/25 12:31 AM  | Anthony Hamilton   | Assigned to Jane Doe. Noted impact on login functionality.            |
| 4/3/25 12:40 AM  | Jane Doe           | Initial analysis: suspected recent updates as potential root cause.   |

---

### ✅ Resolution Steps

1. **Investigation**:
   - Jane Doe reviewed the recent system updates and patch deployments.
   - Verified that update package `v3.2.15` had introduced authentication API schema changes.

2. **Rollback**:
   - Update `v3.2.15` was rolled back to stable version `v3.2.14`.
   - Restarted authentication services and cleared active sessions.

3. **Validation**:
   - Internal QA confirmed that customers could now log in without issue.
   - Status monitoring showed stable login/authentication metrics post-recovery.

4. **Communication**:
   - Notified user (karen@lognpacific.com) of resolution.
   - Added post-mortem summary to internal log.
   - Ticket marked as **Resolved** at 4/3/25 2:00 AM.

---

### 🧾 Final Resolution Entry (for ticket system)

> **Resolution**:  
> Authentication failure was caused by a schema incompatibility introduced in update `v3.2.15`. The update was rolled back, and normal service was restored.  
> Ticket closed as **Resolved**. Monitored for 30 minutes with no recurrence.  
> – Jane Doe, Systems Engineer

---

### 📌 Lessons Learned

- Add pre-deployment compatibility checks to staging pipelines.
- Review authentication update impacts on legacy mobile clients.
- Document changes more clearly in internal update logs.

---




