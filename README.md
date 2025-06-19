# AI-Ticket-Router

Welcome to the **AI-Powered Ticket Management System** – a smart solution for automating support ticket handling using artificial intelligence.

## 📌 Overview

The **AI-Ticket-Router** is a web application that leverages AI to:  
✔ **Automatically categorize** incoming support tickets  
✔ **Smartly assign priority** based on content analysis  
✔ **Route tickets** to the most suitable moderators based on their skills  
✔ **Generate helpful AI notes** to assist moderators in resolving issues faster

## ✨ Key Features

### 🤖 **AI-Powered Ticket Processing**

- Automatic ticket categorization using AI
- Smart priority assignment (Low, Medium, High, Critical)
- AI-generated notes for moderators to speed up resolution

### 👥 **Smart Moderator Assignment**

- Matches tickets with moderators based on skillset
- Falls back to admin assignment if no match is found
- Ensures efficient workload distribution

### 🔐 **User & Role Management**

- Role-based access control (**User**, **Moderator**, **Admin**)
- JWT-based authentication for secure access
- Skill management for moderators

### ⚙️ **Background Processing & Automation**

- Event-driven architecture using **Inngest**
- Automated email notifications (via **Nodemailer & Mailtrap**)
- Asynchronous ticket processing for better performance

## 🛠️ Tech Stack

| Category            | Technology Used         |
| ------------------- | ----------------------- |
| **Backend**         | Node.js, Express        |
| **Database**        | MongoDB                 |
| **Auth**            | JWT (JSON Web Tokens)   |
| **AI**              | Google Gemini API       |
| **Background Jobs** | Inngest                 |
| **Email**           | Nodemailer + Mailtrap   |
| **Dev Tools**       | Nodemon (Hot Reloading) |
