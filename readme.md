# Expense-Tracker-CLI
# 💰 Expense Tracker CLI

A simple and powerful **Command Line Expense Tracker** built with Python.
Track your income and expenses, generate monthly summaries, export data, and visualize spending — all from the terminal.

---

## 🚀 Features

✅ Add income & expense entries
✅ Monthly financial summary
✅ Export transactions to CSV
✅ Pie chart visualization
✅ SQLite database storage
✅ Clean CLI menu system

---

## 🛠️ Tech Stack

* **Python**
* **SQLite3**
* **Pandas**
* **Matplotlib**

---

## 📂 Project Structure

```
expense-tracker/
│
├── expense_tracker.py
├── expenses.db          # auto-created
├── exports/
│   ├── expenses_export.csv
│   └── expense_chart.png
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/expense-tracker.git
cd expense-tracker
```

### 2️⃣ Install dependencies

```bash
pip install pandas matplotlib
```

---

## ▶️ Usage

Run the program:

```bash
python expense_tracker.py
```

You will see:

```
====== Expense Tracker CLI ======
1. Add Entry
2. Monthly Summary
3. Export to CSV
4. Generate Chart
5. Exit
```

---

## 📊 Functionality

### ➕ Add Entry

* Enter date (or press Enter for today)
* Enter category
* Enter amount
* Choose type: income/expense

---

### 📅 Monthly Summary

Shows:

* Total Income
* Total Expense
* Net Balance

---

### 📁 Export CSV

Exports all transactions to:

```
exports/expenses_export.csv
```

---

### 📈 Generate Chart

Creates pie chart:

```
exports/expense_chart.png
```

---

## 🗄️ Database Schema

The app automatically creates a SQLite table:

```sql
transactions (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    date TEXT,
    category TEXT,
    amount REAL,
    type TEXT
)
```

---

## 🎯 Future Improvements (Portfolio Booster 🚀)

* [ ] Add user login system
* [ ] Add GUI (Tkinter / Streamlit)
* [ ] Add AI spending prediction 🤖
* [ ] Add budget alerts
* [ ] Add category-wise charts
* [ ] Deploy web version 🌐

---

## 👨‍💻 Author

**Amninder Singh**
🎓 B.Tech AI & ML — CGC University Mohali
💡 Passionate about Python, AI, and building real-world projects

---

## ⭐ Support

If you like this project:

👉 Star the repo
👉 Fork it
👉 Share with friends
