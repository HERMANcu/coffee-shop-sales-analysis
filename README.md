# ☕ Coffee Shop Sales Analysis

A complete end-to-end sales data analysis project using **Python** and **Excel**.
Covers revenue trends, customer traffic patterns, product performance,
and store comparisons across 6 months of real transaction data.

---

## 📁 Project Structure

```
coffee-shop-sales-analysis/
├── data/
│   ├── Coffee Shop Sales.xlsx          # Raw transaction dataset
│   └── Coffee_Shop_Sales_Analysis.xlsx # Processed Excel workbook (6 sheets)
├── charts/
│   ├── chart_01_dashboard.png
│   ├── chart_02_scatter_bubble.png
│   ├── chart_03_poll_survey.png
│   ├── chart_04_stacked_bar.png
│   ├── chart_05_box_violin.png
│   ├── chart_06_histograms.png
│   ├── chart_07_area_charts.png
│   ├── chart_08_correlation.png
│   ├── chart_09_waterfall.png
│   ├── chart_10_store_comparison.png
│   ├── chart_11_heatmaps.png
│   ├── chart_12_donut_pie.png
│   ├── chart_13_product_ranking.png
│   ├── chart_14_traffic.png
│   └── chart_15_insights_infographic.png
├── analysis/
│   ├── coffee_shop_full_analysis.py    # Main analysis script (15 charts)
│   └── coffee_shop_sales_analysis.py  # Beginner-friendly guided script
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Overview

| Field | Detail |
|---|---|
| Source | Coffee Shop Sales (NYC) |
| Period | January – June 2023 |
| Transactions | 149,116 rows |
| Stores | 3 locations — Astoria, Hell's Kitchen, Lower Manhattan |
| Columns | transaction_id, date, time, quantity, store, product, price, category |

---

## 🔍 What This Project Covers

### Revenue Analysis
- Monthly revenue trends and month-over-month growth
- Total revenue breakdown by store and product category
- Cumulative and daily revenue time series
- Waterfall chart showing category contribution build-up

### Product Insights
- Top 15 products ranked by revenue
- Price vs demand scatter and bubble charts
- Average order value per product (lollipop chart)
- 100% stacked bar showing category share per month

### Customer Traffic Patterns
- Busiest hours of the day (polar/radar chart)
- Busiest days of the week
- Weekday vs weekend order comparison
- Revenue heatmap: day of week × hour of day

### Statistical Analysis
- Revenue distribution with histogram and KDE curve
- Box plots and violin plots by store, category, and day
- Correlation matrix between price, quantity, revenue, and time
- Price sensitivity poll-style chart

---

## 📈 Key Findings

| Metric | Result |
|---|---|
| Total Revenue | $698,812 |
| Revenue Growth (Jan → Jun) | +103.8% |
| Best Month | June 2023 |
| Top Store | Hell's Kitchen |
| Top Product | Barista Espresso |
| Peak Hour | 10:00 AM |
| Busiest Day | Friday |
| Top Category | Coffee (38.6% of orders) |

---

## 📈 Chart Preview

| # | Chart | Types Used |
|---|---|---|
| 01 | Executive KPI Dashboard | Line, Bar, Donut, Heatmap |
| 02 | Price vs Demand | Scatter, Bubble, Trend Line |
| 03 | Customer Preference Poll | Horizontal Bar, Grouped Bar |
| 04 | Monthly Category Breakdown | Stacked Bar, 100% Stacked |
| 05 | Revenue Distributions | Box Plot, Violin Plot |
| 06 | Price & Order Distributions | Histogram, KDE Curve |
| 07 | Daily Revenue Over Time | Area, Stacked Area |
| 08 | Correlation Analysis | Heatmap Matrix, Scatter |
| 09 | Category Revenue Build-up | Waterfall |
| 10 | Store Monthly Comparison | Multi-Line, Grouped Bar |
| 11 | 3-View Heatmap Suite | Heatmap × 3 |
| 12 | Revenue Share Breakdown | Donut × 2, Pie |
| 13 | Product Ranking | Ranked Bar, Lollipop |
| 14 | Traffic Deep Dive | Bar, Dual-Axis, Polar/Radar |
| 15 | Insights Infographic | KPI Cards + Mini Charts |

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, aggregation |
| `matplotlib` | Chart rendering and layout |
| `seaborn` | Heatmaps, violin plots, correlation matrix |
| `openpyxl` | Excel workbook creation and formatting |
| `numpy` | Numerical operations |

---

## ▶️ How to Run

**1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/coffee-shop-sales-analysis.git
cd coffee-shop-sales-analysis
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the full analysis**
```bash
python analysis/coffee_shop_full_analysis.py
```

All 15 charts will be generated and saved automatically as PNG files.

---

## 💡 Ideas to Extend This Project

- Predict July revenue using linear regression with `scikit-learn`
- Build an interactive dashboard using `Plotly` or `Streamlit`
- Add customer segmentation by purchase behaviour
- Automate a PDF report export using `reportlab`
- Compare performance across two different 6-month periods

---

## 📚 Great For

- Data analysis students learning pandas and matplotlib
- Anyone building a data portfolio project
- Practising different chart types on real-world data
- Understanding how to go from raw data to business insights

---

## 📜 License

This project is open source and free to use under the **MIT License**.
Feel free to fork, modify, and share it.
