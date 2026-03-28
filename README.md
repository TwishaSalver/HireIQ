# Expense Analyzer

A web application that converts unstructured expense data into meaningful insights and visual summaries.

---

## Overview

Expense Analyzer allows users to paste raw expense text (such as notes or messages) and transforms it into structured data. It helps users understand spending patterns, category-wise distribution, and total expenses.

---

## Features

* Smart parsing of unstructured expense text
* Automatic categorization of expenses
* Summary of total spending
* Visual representation using charts
* Simple and user-friendly interface

---

## Example

**Input:**
Paid 450 to Zomato, 199 Netflix, 210 Ola, 600 groceries

**Output:**

* Total: ₹1459
* Categories: Food, Transport, Entertainment, Groceries
* Insights on spending patterns

---

## Tech Stack

* Frontend: React.js
* Backend: Node.js, Express.js
* Authentication: Google OAuth (optional)
* Visualization: Chart.js or similar libraries

---

## Project Structure

expense-analyzer/
│── frontend/
│── backend/
│── README.md
│── package.json

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/expense-analyzer.git
cd expense-analyzer
```

2. Install dependencies

```bash
npm install
```

3. Run the application

```bash
npm start
```

---

## Environment Variables

Create a `.env` file and add:

```env
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_secret
```

---

## Future Improvements

* AI-based categorization
* Budget tracking
* Export reports
* Mobile version

---

## License

MIT License
