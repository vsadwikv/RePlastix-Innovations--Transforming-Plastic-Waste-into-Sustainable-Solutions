# ♻️ Inventory & Waste Management System (Salesforce)

A simple Salesforce project built individually to streamline how inventory, orders, and waste are tracked and managed — with smart automation and role-based access for different types of users.

---

## 📌 About the Project

This project is a basic but powerful simulation of how a company like **RePlastix Innovations** can use Salesforce to:

- Track **inventory levels**
- Handle **orders** from customers
- Record and manage **waste** generated
- Automate **approval processes**
- Control **who sees or edits what**

It demonstrates core Salesforce features like:

- Custom objects & relationships
- Flow Builder automation
- Role-based data access
- Approval processes using Apex

---

## 👨‍💻 Who Made This?

> 🧑‍💼 This is an **individual project** done by me as part of a virtual internship with Salesforce. It helped me understand Salesforce CRM's data modeling, automation, and security concepts in a real-world scenario.

---

## 🚀 Features

- ✅ Inventory Tracking (Stock-In, Stock-Out)
- ✅ Order Creation & Status Updates
- ✅ Waste Logging per Order
- ✅ Automated Restocking Approval via Flows
- ✅ Access Control with Roles & Profiles
- ✅ Apex-based Approval Flow for Managers

---

## 🧱 Tech Stack

- **Platform:** Salesforce Developer Edition
- **Tools Used:** Flow Builder, Object Manager, Apex, Validation Rules
- **Custom Objects:**
  - `Inventory__c`
  - `Order__c`
  - `Waste__c`
- **Object Relationships:**
  - Order ⟶ Inventory (Lookup)
  - Waste ⟶ Order (Lookup)
- **Automation:**
  - Flow Builder for Restock Logic
  - Apex for Approvals
- **Security:**
  - Users (Manager, Handler, Collector)
  - Roles & Profiles to manage visibility and actions

---

## 📚 Project Modules

### 1️⃣ Data Modeling

Defined custom objects and relationships to simulate inventory operations in a factory environment.

### 2️⃣ Data Security

Used **Users, Profiles, and Roles** to make sure only the right people see and edit specific data.  
E.g., Waste Collectors can't access inventory records.

### 3️⃣ Automation

Set up **Flow Builder** to auto-check inventory levels. If stock is low, it creates a restock request and sends it for approval.

### 4️⃣ Approval Process

Created an **Apex-based approval process** where a manager approves restock requests.

---

## 🎥 Demo Video Walkthrough

- Overview of the project
- Data model setup
- Flow and automation demo
- Security logic
- Sample test cases (Order creation, Restock request, etc.)

📌 [Video Link (to be added)]()

---

## 🧪 Sample Test Cases

| Scenario              | Action Taken        | Result                      |
| --------------------- | ------------------- | --------------------------- |
| Creating an Order     | Linked to Inventory | Quantity auto-decreased     |
| Logging Waste         | Linked to Order     | Waste recorded successfully |
| Stock below threshold | Triggered Flow      | Restock Request Created     |
| Manager views request | Approves via Apex   | Status updated to Approved  |

---

## 💡 Why This Project Matters

Even small businesses need smart systems to manage their work. This project shows how Salesforce:

- Keeps data **organized**
- Automates **boring tasks**
- Improves **team collaboration**
- Controls **who can do what**

---
