# Yuva-Intern

# 💰 FinBuddy – Smart Student Expense Tracker

FinBuddy is a simple web-based expense tracking application made especially for students. The main purpose of this project is to help students keep track of their income and daily expenses in one place.

Many students receive a limited amount of money every month but do not always keep track of how they spend it. FinBuddy provides an easy way to record transactions, check spending patterns, and understand their financial situation.

## 📌 Project Overview

FinBuddy allows users to create an account, log in, and manage their personal financial records. Users can add income and expenses, select categories, and view their overall balance from the dashboard.

The application also includes a **Financial Health Score (0–100)** that gives users a simple idea of how well they are managing their spending.

The project is being developed as part of a software development/internship project and focuses on applying concepts such as web development, backend development, database management, authentication, and CRUD operations.

## ✨ Features

* 🔐 User Registration and Login
* 👤 Personal User Dashboard
* 💵 Add Income
* 💸 Add Expenses
* ✏️ Edit Transactions
* 🗑️ Delete Transactions
* 📂 Expense Categories
* 📊 Spending Summary
* 💰 Balance Calculation
* 📈 Financial Health Score
* 💡 Basic Spending Recommendations
* 🔒 Secure Password Storage
* 📱 Responsive User Interface

## 🛠️ Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MySQL

### Other Technologies

* JWT Authentication
* bcryptjs
* dotenv
* CORS
* Nodemon

## 🏗️ Project Structure

```text
FinBuddy/
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── database/
│   └── database.sql
│
├── db.js
├── server.js
├── package.json
├── package-lock.json
├── .env
└── README.md
```

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/FinBuddy.git
```

### 2. Open the Project Folder

```bash
cd FinBuddy
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Create the Database

Open MySQL and create the database:

```sql
CREATE DATABASE finbuddy;
```

Then create the required tables using the SQL file provided in the `database` folder.

### 5. Configure Environment Variables

Create a `.env` file in the project folder.

```env
PORT=3000
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=finbuddy
JWT_SECRET=your_secret_key
```

Replace the database password with your local MySQL password.

### 6. Start the Application

For development:

```bash
npm run dev
```

Or:

```bash
node server.js
```

### 7. Open in Browser

Open:

```text
http://localhost:3000
```

## 📊 Main Modules

### 1. Authentication

Users can register and log in to their account. Passwords are stored using hashing instead of plain text.

### 2. Transaction Management

Users can add, update, and delete their income and expense records.

### 3. Dashboard

The dashboard provides a quick overview of:

* Total Income
* Total Expenses
* Current Balance
* Recent Transactions
* Category-wise Spending

### 4. Financial Health Score

FinBuddy calculates a score between **0 and 100** based on selected spending indicators. The score is intended to give users a simple understanding of their spending habits.

### 5. Spending Suggestions

Based on the recorded expenses, the application can provide basic suggestions to help users control unnecessary spending.

## 🎯 Project Objectives

* To make expense tracking simple for students.
* To help users understand their spending habits.
* To provide a centralized place for managing income and expenses.
* To encourage better budgeting and saving habits.
* To practice real-world web development and database concepts.

## 🔮 Future Improvements

The project can be improved further by adding:

* 📱 Android/iOS mobile application
* 🤖 AI-based spending analysis
* 📧 Email notifications
* 📅 Monthly budget planning
* 📊 More detailed charts and reports
* 📄 PDF/Excel expense reports
* 🔔 Budget limit notifications
* 🌐 Multi-language support
* ☁️ Cloud deployment
* 🔗 Bank account integration

## 🔒 Security

The project uses basic security practices such as:

* Password hashing using bcrypt
* JWT-based authentication
* Protected user routes
* Environment variables for sensitive configuration
* Input validation

**Note:** FinBuddy is an educational/student project and should not be considered a replacement for professional financial advice.

## 🚧 Project Status

**Current Status:** 🚀 In Development

The project is being developed step by step, starting with requirements and planning, followed by design, implementation, testing, and deployment.

## 👨‍💻 Developer

**Aniket Kumar Gupta**

B.Tech – Computer Science & Engineering

Interested in Java, Web Development, Backend Development, and Software Engineering.

## 📄 License

This project is created for educational and learning purposes.

---

⭐ If you find this project useful, feel free to give the repository a star!
