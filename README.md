# 📊 E-Commerce Data Analyzer & Dashboard — Python + Pandas + Matplotlib

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange)
![Excel](https://img.shields.io/badge/Output-Excel-217346?logo=microsoft-excel)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📌 Description

A Business Analyst tool that processes e-commerce sales data, computes KPIs, generates **4 professional charts**, and exports a formatted **Excel dashboard** — all automatically with one command.

---

## 🎯 KPIs Computed

| KPI | Description |
|-----|-------------|
| Total Revenue | Sum of all monthly revenues |
| Total Orders | Total number of orders placed |
| Avg Order Value | Revenue / Orders per month |
| Return Rate % | Returns / Orders × 100 |
| Best / Worst Month | Highest and lowest revenue months |
| Revenue by Category | Breakdown per product category |

---

## 📈 Charts Generated

| Chart | Insight |
|-------|---------|
| Revenue Trend | Monthly revenue evolution with annotations |
| Orders vs Customers | Dual-axis comparison |
| Revenue by Category | Bar + Pie chart breakdown |
| Return Rate | Monthly return rate vs 5% threshold |

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Pandas** — Data manipulation & KPI computation
- **Matplotlib** — Chart generation
- **openpyxl** — Excel dashboard export

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/fatimazahrary/ba-data-analyzer.git
cd ba-data-analyzer
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the analyzer
```bash
python data_analyzer.py
```

### 4. Check the output
```
output/
├── charts/
│   ├── revenue_trend.png
│   ├── orders_vs_customers.png
│   ├── category_revenue.png
│   └── return_rate.png
└── reports/
    └── dashboard_20240315_143022.xlsx
```

---

## 📁 Project Structure

```
ba-data-analyzer/
│
├── data_analyzer.py     # Main script
├── requirements.txt     # Dependencies
├── README.md
└── output/              # Auto-generated on run
    ├── charts/
    └── reports/
```

---

## 👩‍💻 Author

**Fatima zahra RIYAD**  
Junior Business Analyst | Data Analysis | Reporting  
📧 [fatimazahrary.12@gmail.com]  
🔗 [linkedin.com/in/fatimazahrary]

---

## 📄 License

MIT License — free to use and modify.
