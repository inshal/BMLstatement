# 🦅 Hermes — Personal Finance Dashboard

> A beautiful, **100% client-side** transaction dashboard. Upload your bank CSV and instantly get insights, charts, and leaderboards. **No server, no database, privacy-first.**

![Hermes Dashboard Preview](https://user-images.githubusercontent.com/.../preview.png)

## ✨ Features
- **No Backend Required**: Everything runs inside your browser via JavaScript.
- **Banking Support**: Supports HSBC / Standard Format (`Date, Value Date, Type, Ref, Description, Name, Channel, Debit, Credit, Balance`).
- **Financial Insights**: Total net worth, income, expenses, and average monthly spending.
- **Interactive Charts**:
  - 💰 Monthly Cashflows & Savings Rates (Dual Y-Axis)
  - ⏲️ Income vs. Expenses
  - 🍩 Spending by Transaction Type
  - 🏆 Top 15 Contacts (Senders & Receivers)
  - 🏪 **Merchant Spending (New!)**: Where you spend, category detection, and visit frequency.
- **Smart Filtering**: Filter by Date range, Transaction Type, Name, and Amount.
- **Detailed Overlays**: Click any contact or merchant to see their full history and breakdown.
- **Export**: Export filtered data to CSV or JSON.

## 🚀 How to Use
1. Download your bank statement in **CSV format**.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Upload the CSV file.
4. Explore the charts and click on any leaderboard item for more details.

## 🔒 Privacy & Security
This dashboard is entirely **client-side**. Your financial data is **never uploaded to any server**. All calculations and charts are generated locally in your browser's memory.

## 📁 File Structure
```text
hermes-dashboard/
├── README.md        # This file
├── LICENSE          # MIT Open Source License
├── index.html       # The entire dashboard (Single-file app)
└── .gitignore       # Hides local CSVs to prevent accidental leaks
```

## 🛠 Tech Stack
- **HTML5** (Semantic structure)
- **CSS3** (Flexbox, Grid, Custom Properties, Responsive Design)
- **Vanilla JavaScript** (ES6+, No heavy frameworks)
- **Chart.js** (For beautiful, responsive data visualization)

## 📜 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.