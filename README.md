
<img width="567" height="645" alt="image" src="https://github.com/user-attachments/assets/d1790119-8fd2-4fcc-bc18-95aef5bc7351" />


# Service-Desk-Chatbot
Helpdesk Chatbot

# ✅ Service Desk / IT Analyst Intelligent Chatbot

## 📌 Overview
The **Service Desk / IT Analyst Intelligent Chatbot** is a web‑based IT support assistant designed to simulate real-world enterprise IT Service Desk operations.  
It acts as a **Tier 1 IT Support Agent**, handling common IT queries, generating tickets, storing incidents, and demonstrating controlled automation concepts.

This project focuses on **practical IT workflows**, **security awareness**, and **automation-ready design**, making it ideal for learning and portfolio presentation.

---

## 🎯 Project Objectives
- Simulate a professional IT Service Desk environment
- Reduce repetitive support interactions
- Demonstrate ticketing logic and follow‑up workflows
- Showcase automation awareness with security boundaries
- Apply Agile-style task tracking using GitHub Projects

---

## 🤖 Chatbot Workflow

### ✅ Step 1: Greeting
``

### ✅ Step 2: Issue Selection (Checkbox / Button UI)
Users select one of the following IT-related issues:
- 🖥️ PC is slow / performance issues
- 🎧 Headset or audio not working
- 🌐 Network / Internet issues
- 🔐 Reset Windows password / Unlock account

### ✅ Step 3: Ticket Creation
- A unique ticket number is generated (e.g. `IT-2026-000123`)
- Ticket details are captured:
  - Issue category
  - Timestamp
  - Ticket status (To Do / In Progress / Closed)

### ✅ Step 4: Ticket Follow‑Up
Users can query the chatbot using a ticket number to check the status of an incident.

---

## 🎫 Ticketing System
- Lightweight JSON-based storage (prototype)
- Designed for eventual backend migration
- Simulates ITSM platforms such as ServiceNow or Freshservice

**Example ticket record (JSON):**
```json
{
  "ticketId": "IT-2026-000123",
  "category": "Slow PC",
  "status": "Open",
  "createdAt": "2026-05-07"
}
