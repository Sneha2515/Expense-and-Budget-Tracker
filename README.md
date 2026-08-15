# 💰 Expense & Budget Tracker

A **Python Flask-based personal finance management application** designed to help users track expenses, manage budgets, monitor financial goals, and understand their spending patterns.

## 📌 About the Project

Managing personal expenses manually can make it difficult to understand where money is being spent and whether monthly budgets are being followed.

The **Expense & Budget Tracker** provides a centralized platform where users can:

* Record income and expenses
* Categorize transactions
* Set and monitor budgets
* Track financial goals
* Import transaction data
* View spending insights
* Manage recurring transactions
* Reconcile financial records

The project is built using **Flask, Python, SQLite, HTML, CSS, and JavaScript**.

---

## ✨ Features

### 🔐 User Authentication

* User registration and login
* Secure password handling
* Session-based authentication

### 💳 Transaction Management

* Add income and expense transactions
* Categorize transactions
* View transaction history
* Track spending over time

### 📊 Budget Management

* Create monthly budgets
* Monitor spending against budgets
* Identify budget overruns

### 📥 Transaction Import

* Import transaction data from files
* Automatically process imported transactions
* Reduce manual data entry

### 🔄 Recurring Transactions

* Detect recurring transactions
* Help users identify regular expenses and payments

### 🎯 Financial Goals

* Create financial goals
* Track progress toward goals
* Monitor savings progress

### 🔍 Reconciliation

* Compare and verify financial records
* Identify discrepancies in transaction data

### 📈 Financial Insights

* Analyze spending patterns
* Generate useful summaries from transaction data
* Help users understand their financial behavior

---

## 🛠️ Tech Stack

### Backend

* **Python**
* **Flask**
* **SQLite**

### Frontend

* **HTML5**
* **CSS3**
* **JavaScript**
* **Jinja2 Templates**

### Data Processing

* **Pandas**
* CSV-based transaction processing

---

## 📥 Importing Transactions

The application supports importing transaction data.

A sample CSV can contain fields such as:

```text
date,description,type,amount,account,category
2026-08-01,Salary,Income,45000,HDFC Bank,Salary
2026-08-02,Rent,Expense,12000,HDFC Bank,Housing
2026-08-03,Grocery Store,Expense,1850,HDFC Bank,Groceries
```

This allows users to test the transaction import functionality without manually entering every transaction.

---

## 🔄 Application Flow

```text
User
  │
  ▼
Register / Login
  │
  ▼
Dashboard
  │
  ├── Add Transactions
  │
  ├── Import Transactions
  │
  ├── Manage Budgets
  │
  ├── Track Financial Goals
  │
  ├── View Recurring Transactions
  │
  ├── Reconcile Records
  │
  └── View Financial Insights
          │
          ▼
    Spending Analysis
```

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Provide an easy-to-use platform for personal expense tracking.
2. Reduce manual financial record keeping.
3. Help users monitor their budgets.
4. Provide insights into spending patterns.
5. Support transaction data import.
6. Help users track financial goals.
7. Demonstrate the development of a full-stack Flask application.

---

## 👩‍💻 Author

**Sneha Negi**
