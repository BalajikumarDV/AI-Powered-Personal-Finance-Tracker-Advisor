 💰 AI-Powered Personal Finance Tracker & Advisor

An intelligent full-stack finance management platform that helps users track expenses, manage budgets, analyze spending patterns, and receive AI-powered financial recommendations. 
The application combines OCR technology, Natural Language Processing, and Artificial Intelligence to automate personal finance management and provide actionable insights.

📸 Screenshots

Add application screenshots here:


page 1:


![image alt](https://github.com/BalajikumarDV/AI-Powered-Personal-Finance-Tracker-Advisor/blob/742432b0fe52cf85fed46bfd70aadc55716d3f46/1.png)



page 2


![image alt](https://github.com/BalajikumarDV/AI-Powered-Personal-Finance-Tracker-Advisor/blob/742432b0fe52cf85fed46bfd70aadc55716d3f46/2.png)



page 3

![image alt](https://github.com/BalajikumarDV/AI-Powered-Personal-Finance-Tracker-Advisor/blob/742432b0fe52cf85fed46bfd70aadc55716d3f46/3.png)



page 4


![image alt](https://github.com/BalajikumarDV/AI-Powered-Personal-Finance-Tracker-Advisor/blob/742432b0fe52cf85fed46bfd70aadc55716d3f46/4.png)


page 5

![image alt](https://github.com/BalajikumarDV/AI-Powered-Personal-Finance-Tracker-Advisor/blob/742432b0fe52cf85fed46bfd70aadc55716d3f46/5.png)


---

 🚀 Features

 📊 Expense Management

* Add, update, and delete financial transactions.
* Categorize expenses and income automatically.
* Track spending across multiple categories.
* Maintain a complete transaction history.

 📷 OCR-Based Receipt Scanning

* Upload receipts and bills directly.
* Extract transaction details using **Tesseract OCR**.
* Automatically populate expense records.
* Reduce manual data entry and improve accuracy.

 🤖 AI-Powered Financial Advisor

* Analyze spending behavior using AI.
* Generate personalized savings recommendations.
* Identify unnecessary expenditures.
* Suggest budget optimization strategies.

 💬 Natural Language Financial Queries

Ask questions such as:

* "How much did I spend on groceries this month?"
* "What is my highest expense category?"
* "How much money did I save last quarter?"
* "Show my spending trend for the last six months."

The system processes natural language queries and provides intelligent responses based on user financial data.

📈 Interactive Analytics Dashboard

* Monthly spending trends
* Income vs Expense comparison
* Category-wise expense breakdown
* Budget utilization tracking
* Financial health indicators

Built using **Chart.js** for dynamic visualizations.

🔐 Secure Authentication

* JWT-based authentication
* User registration and login
* Protected API routes
* Secure financial data management

---

 🛠️ Tech Stack

Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Chart.js

 Backend

* Node.js
* Express.js
* REST APIs

 Database

* PostgreSQL

 AI & Machine Learning

* OpenAI API
* Natural Language Processing (NLP)

 OCR

* Tesseract.js

 Authentication & Security

* JWT (JSON Web Token)
* Password Hashing

---

 🏗️ System Architecture

```text
Frontend (React.js)
        │
        ▼
Backend APIs (Node.js + Express.js)
        │
 ┌──────┼─────────┐
 ▼      ▼         ▼
PostgreSQL   OpenAI API   Tesseract OCR
(Database)   (AI Engine)  (Receipt Scanner)
```

---

 📂 Project Structure

```text
AI-Powered-Personal-Finance-Tracker-Advisor/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   └── package.json
│
├── database/
│   └── schema.sql
│
├── screenshots/
│
├── README.md
└── .env
```

---

 ⚙️ Installation & Setup

 Prerequisites

* Node.js (v18+)
* PostgreSQL
* OpenAI API Key

 Clone Repository

```bash
git clone https://github.com/BalajikumarDV/AI-Powered-Personal-Finance-Tracker-Advisor.git

cd AI-Powered-Personal-Finance-Tracker-Advisor
```

 Backend Setup

```bash
cd server

npm install
```

Create a `.env` file:

```env
PORT=5000

DB_HOST=localhost
DB_PORT=5432
DB_NAME=finance_tracker
DB_USER=postgres
DB_PASSWORD=your_password

JWT_SECRET=your_jwt_secret

OPENAI_API_KEY=your_openai_api_key
```

Start backend server:

```bash
npm start
```

Frontend Setup

```bash
cd client

npm install

npm start
```

---

📊 Key Functionalities

Expense Tracking

* Manual transaction entry
* Category-based classification
* Monthly expense monitoring

Budget Management

* Set monthly budgets
* Track budget utilization
* Receive overspending alerts

AI Financial Insights

* Spending behavior analysis
* Personalized recommendations
* Financial health evaluation

 Receipt Automation

* OCR-based extraction
* Automatic transaction creation
* Reduced manual effort

---

🎯 Future Enhancements

* Multi-bank account integration
* UPI and payment gateway synchronization
* Predictive expense forecasting
* Investment portfolio tracking
* Mobile application support
* Voice-enabled financial assistant
* Advanced AI financial planning

---

📸 Screenshots

Add application screenshots here:

```text
screenshots/
├── dashboard.png
├── expense-tracker.png
├── ai-advisor.png
└── receipt-scanner.png
```

---

## 📈 Project Impact

* Reduced manual expense entry through OCR automation.
* Enabled intelligent financial decision-making using AI recommendations.
* Improved financial visibility with interactive analytics dashboards.
* Enhanced user experience through natural language financial queries.

---

## 👨‍💻 Author

**Balaji Kumar DV**

* GitHub: https://github.com/BalajikumarDV
* LinkedIn: https://www.linkedin.com/in/balajikumardv/
* Email: [balajikumardv02@gmail.com](mailto:balajikumardv02@gmail.com)

---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.
