# 🛍️ UK Online Retail Store — Business Analytics (2010–2012)

**Author:** Aditya Saji

An end-to-end sales analysis of a UK-based wholesale online retailer, covering data cleaning, pivot analysis, RFM customer segmentation, and an interactive Excel dashboard.

---

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Revenue (2010–2012) | £8,911,408 |
| Top Market | United Kingdom (82%) |
| Top Customer Revenue Share | 17.26% (top 10 customers) |
| Top Product Revenue Share | 9.9% (top 10 products) |
| Champion Segment Revenue Share | 56.9% |

---

## 📁 Project Structure

```
├── data.csv              # Raw transaction data
├── step_5.xlsx           # Cleaned data + pivot tables + dashboard
├── Final.pdf             # Exported dashboard & analysis report
└── README.md
```

---

## 🔧 Process

### Step 1 — Data Cleaning
- Removed rows with missing Customer IDs
- Removed returned/cancelled transactions
- Removed rows with negative quantity or price
- Added a computed **Revenue** column (`Quantity × Unit Price`)

### Step 2 — Pivot Tables
Built pivot tables for:
- Monthly Revenue
- Top 10 Products by Revenue
- Top 10 Customers by Revenue
- Sales by Country
- RFM Segmentation scores

### Step 3 — Charts
Created visualizations for all pivot tables and consolidated them into a single **Dashboard** sheet.

### Step 4 — Dashboard
Finalized the dashboard with all charts, KPIs, and segment breakdowns.

---

## 📈 Insights

1. **No sales on Saturdays** — zero revenue recorded across the entire period.
2. **Thursday is peak day** — highest revenue of any weekday.
3. **82% of revenue from the UK** — heavy regional concentration; international diversification is an opportunity.
4. **Top 10 customers = 17.26% of total revenue** — moderate key-account dependency.
5. **Top 10 products = 9.9% of total revenue** — relatively distributed product performance.
6. **Champion segment drives 56.9% of revenue** — retaining high-value customers is critical.

---

## 👥 RFM Customer Segmentation

Customers were scored on **Recency**, **Frequency**, and **Monetary** value (1–3 scale each), then segmented:

| Segment | Count | Share |
|---|---|---|
| Potential Loyalist | 1,007 | 23% |
| Lost | 805 | 19% |
| Champion | 692 | 16% |
| At Risk | 636 | 15% |
| Loyal Customer | 557 | 13% |
| Needs Attention | 403 | 9% |
| Recent Customer | 239 | 6% |
| **Total** | **4,339** | |

---

## 🌍 Revenue by Country (Top 10)

| Country | Revenue (£) |
|---|---|
| United Kingdom | 7,308,392 |
| Netherlands | 285,446 |
| Ireland | 265,546 |
| Germany | 228,867 |
| France | 209,024 |
| Australia | 138,521 |
| Spain | 61,577 |
| Switzerland | 56,444 |
| Belgium | 41,196 |
| Sweden | 38,378 |

---

## 🛠️ Tools Used

- **Microsoft Excel** — data cleaning, pivot tables, charts, dashboard
- **CSV** — raw data source
