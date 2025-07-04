# 💰 Personal Finance Tracker+

A full-stack personal finance tracker web application that allows users to manage daily expenses, set budgets, visualize spending patterns, and receive smart suggestions to optimize their financial habits.

---

## 🚀 Features

### 🔐 User Accounts

* Sign up & login with email/password
* Secure authentication (only see your own data)

### 💸 Expense Management

* Add, edit, delete expenses
* Each expense includes:

  * Amount
  * Category (e.g., Food, Rent)
  * Date
  * Payment Method (UPI, Credit Card, etc.)
  * Optional Notes
* Filter and search by date, category.

### 📊 Budget & Alerts

* Set monthly spending limits per category
* Alerts when 80% or 100% of budget is reached

### 📈 Dashboard Reports

* Total spending this month
* Most spent category
* Top 3 payment methods
* Category-wise spending (Pie Chart)
* Spending trend over time (Line Graph)

### 🧠 Smart Suggestions (Python Service)

* Flask API analyzes last 30 days of spending
* Suggestions like:

  * “You're spending a lot on Food. Try to reduce it by 15%.”
  * “Your travel expenses increased a lot this month.”
* Built using Pandas, returns JSON

---

## 🛠️ Tech Stack

| Part          | Technology                                           |
| ------------- | ---------------------------------------------------- |
| Frontend      | React.js + BootStrap/MUI                             |
| Backend       | Node.js + Express.js                                 |
| Main Database | MongoDB                                              |
| Charts        | Chart.js                                             |
| Smart API     | Python Flask + Pandas                                |
| Deployment    | Vercel (Frontend), Vercel (Backend), Render (Python) |

---

## ⚙️ How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Priyanshu879/Personal-Finance-Tracker.git
cd Personal-Finance-Tracker
```
### 2. Set Up Environment Variables
* Create a .env file in each folder as needed (/backend).


* Never commit actual credentials or secrets.

### 3. Frontend (React.js + BootStrap/MUI)

```bash
cd frontend
npm install
npm start
```

* Runs on http://localhost:3000

### 4. Backend (Node.js + Express + MongoDB)

```bash
cd backend
npm install
npm run dev
```
* Ensure MongoDB is running (local or Atlas)

* Runs on http://localhost:5000

### 5. Python Service (Flask + Pandas)
 ```bash
 cd smart-suggestions
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python server.py
```
* Runs on http://localhost:8000

### 6. Setup .env File
```bash
MONGO_URL=MONGO_DB_CONNECTON_STRING
PORT=5000
```

### 🧪 Test Credentials
```bash
Email: test123@gmail.com  
Password: 123456
```
### 🌐 Live Demo

* Frontend: https://personal-finance-tracker-client-psi.vercel.app/login



