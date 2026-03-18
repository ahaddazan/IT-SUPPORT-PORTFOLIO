# Jira Service Management – IT Support Ticketing Lab

## Overview

This lab documents hands-on practice with **Jira Service Management (JSM)**, Atlassian's ITSM platform used by IT support teams to manage, track, and resolve service requests. The goal was to simulate a real IT support workflow — from a customer submitting a ticket to an agent updating its status in the agent workspace.

---

## Tools Used

- Jira Service Management (cloud/free tier)
- Atlassian demo environment

---

## What Was Covered

### 1. Customer Portal – Raising a Request

Accessed the **Basic IT Support** customer-facing portal, which organises request types into categories: Common Requests, Computers, Logins and Accounts, Applications, and Servers and Infrastructure.

A test ticket was submitted under **Common Requests → Get IT help** on behalf of a simulated user (Oliver Johnson), with the summary:

> *"My laptop is laggy and slow, it has only been 2 months since I got this company laptop"*

The form included fields for Summary, Description, and optional Attachments before submitting.

| Customer Portal | Request Categories | Logging a Request |
|---|---|---|
| ![Portal](screenshots/jiraportal.png) | ![Categories](screenshots/jiraportal2.png) | ![Logging](screenshots/loggingarequest.png) |

---

### 2. Agent Workspace – Viewing the Ticket Queue

After the request was submitted, it appeared in the agent workspace under **Basic IT Support → Queues → All open**. The newly created ticket (BIT-1) was visible immediately after submission.

![Agent Workspace](screenshots/agentworkspace.png)

---

### 3. Changing Ticket Status to "In Progress"

Once the ticket was assigned, the status was updated to **In Progress** via the agent view. This change is reflected on the customer-facing side of the portal in real time.

![Status Changed](screenshots/changedstatuscustomerside.png)

---

### 4. Video Walkthrough – Changing Status to In Progress

A ~1 minute screen recording demonstrating how the agent can go into their workspace and transition its status to **In Progress**.

📹 [Watch the walkthrough]()

---

## Key Concepts Practised

- Navigating the customer portal and understanding request categories
- Submitting a ticket on behalf of a user (agent-raised request)
- Working within the agent workspace (queues, spaces, assignments)
- Transitioning ticket status and understanding how it reflects to the customer
- Full ticket lifecycle: Open → In Progress → Resolved

---


