# 📦 Inventory & Waste Management System (Salesforce)

This is a simple Salesforce project made by me to manage inventory, orders, and plastic waste efficiently. It shows how Salesforce can be used to run basic business operations with automation and data security.

---

## 📌 What This Project Does

- Tracks available stock and products
- Handles customer orders
- Records plastic waste collected
- Sends alerts when stock is low
- Manages who can view or change data (based on roles)

---

## 👤 Who Made This?

This is a solo project created by **Sadwik Varma Vemanamandi** during a Salesforce virtual internship. It helped me learn how to use Salesforce for real-life tasks like tracking stock and automating approvals.

---

## 🧰 Tools & Features Used

### 🔹 Platform:

- Salesforce Developer Edition

### 🔹 Main Tools:

- **Object Manager** – to create custom data types
- **Flow Builder** – to automate tasks
- **Apex (code)** – for approval logic
- **Validation Rules** – to avoid wrong data entries
- **Profiles, Roles, and Users** – for data security

---

## 📦 What’s in the Project?

### ✅ Custom Objects:

- **Inventory** – stores stock quantity
- **Order** – tracks product orders
- **Waste** – records waste from each order
- **Restock Request** – used when stock is low
- **Recycling Center** – where waste is processed
- **Product** – the item being sold or recycled

### ✅ Relationships:

- Orders are connected to Products
- Waste is connected to Orders
- Restock Requests are connected to Products

---

## 🔄 How Automation Works

- When an order is placed, the stock is reduced automatically
- If stock goes below a set limit, a restock request is created
- A manager can approve the restock, and the stock is updated

This is done using:

- **Flow**: checks if stock is low
- **Apex Code**: handles approvals and sends email notifications

---

## 🔐 Data Security

- Users are created for each role (Manager, Collector, etc.)
- Profiles control what each user can do (read, edit, delete)
- Roles decide which records each user can see

This helps keep sensitive data safe and only visible to the right people.

---

## 📝 Key Features

- Track stock in and out
- Record waste per order
- Place and manage orders
- Create and approve restock requests
- Control who can access what using profiles and roles
- Avoid wrong data with validation rules

---

## 🎯 Why This Project?

Even small businesses need a system to stay organized. This project shows how Salesforce can:

- Save time by doing things automatically
- Reduce mistakes with clean data rules
- Give the right access to the right people
- Keep everything in one place

---

## 📚 What I Learned

- Creating and connecting custom objects
- Setting up flows and writing Apex code
- Applying security through profiles and roles
- Automating real business processes in Salesforce

---

## 🧑‍💻 Made by:

**Sadwik Varma Vemanamandi**  
Individual project for internship learning  
📧 Email: svemanam@gitam.in
