# Financial_App
This is an app to track income, expenses, bills due with pay reminders, and financial goals.


# Finance Tracker App

A full-stack personal finance management app that helps users track income and spending, manage bills with reminders, set income goals, calculate monthly budgets, and (optionally) connect to real bank accounts using Plaid.

This app is designed to support **web**, **mobile**, and **API backend** from a single unified project folder.

---
🚀 Features

User Accounts & Security
- Secure login & registration (JWT authentication)
- Encrypted passwords (bcrypt)
- User notification preferences (email, SMS, push)

Expense & Income Tracking
- Add income and expenses
- Categorize transactions
- Automatic monthly summaries (income, expenses, net)

Bill Management + Reminders
- Add bills with due dates
- Mark bills as paid
- Daily cron job to trigger reminders
- Supports email, SMS, and push notifications (via SendGrid, Twilio, FCM)

Budgeting & Goals
- Monthly budget planner (income target + spending limit)
- Track savings goals and deadlines

Bank Account Connection (Optional)
- Plaid Link integration for connecting real bank accounts
- Secure token exchange
- Fetching account and transaction data

 Multi-Platform Support
- Web app (React)
- Mobile app (React Native / Expo)
- Backend API (Node.js + Express + MongoDB)

---

Project Structure

finance-app/
├── api/ Node.js + Express backend
├── web/ React web application
├── mobile/ React Native mobile application
├── docs/ Optional documentation
└── README.md


---

## 🛠️ Tech Stack

Backend
- Node.js
- Express.js
- MongoDB (Atlas recommended)
- Mongoose
- JWT authentication
- bcrypt (password hashing)
- node-cron (scheduled jobs)
- dotenv (environment variables)

 Notifications
- Twilio (SMS)
- SendGrid (Email)
- Firebase Cloud Messaging (Push)
  
Integrations
- Plaid (bank account aggregation)

Frontend
- React (web)
- React Native + Expo (mobile)

---
⚙️ Setup Instructions

1. Clone the repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

Project Structure

