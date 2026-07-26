# 🛒 Retail Sales Intelligence App

An interactive, web-based analytics dashboard designed for retail business stakeholders to track, analyze, and gain actionable insights into store sales performance across multiple operating regions.

---

## 🌟 Live Demo & Resources

- **Live Application:** [Deploy Link on Cloudflare Pages / Vercel]
- **GitHub Repository:** [https://github.com/vasanthravichanderan/stackai](https://github.com/vasanthravichanderan/stackai)
- **Built With:** Google AI Studio App Builder

---

## 🚀 Key Features

### 1. Data Integration & File Upload
- **Dynamic File Parsing:** Upload two Excel spreadsheet datasets directly into the dashboard:
  - `retail_weekly_sales.xlsx` (Weekly transaction and sales records)
  - `store_master.xlsx` (Store metadata and target reference data)
- **Instant Client-Side Processing:** Automatically joins datasets and updates all KPIs, charts, and insight cards upon file submission.

### 2. Global Interactive Filters
Filter all dashboard views synchronously using the sidebar controls:
- **Time Period:** Week
- **Geographic:** Region, City
- **Store-Level:** Store Name / Store ID, Store Format
- **Product-Level:** Product Category

### 3. Key Performance Indicator (KPI) Summary Cards
Prominently displays core retail metrics at a glance:
- **Net Sales ($):** Total revenue generated after discounts and returns.
- **Target Achievement (%):** Comparison of actual sales against store master targets.
- **Average Transaction Value ($):** Mean revenue per transaction.
- **Return Rate (%):** Calculated as `(return_amount / net_sales) * 100`.
- **Discount Rate (%):** Total promotional discounts as a percentage of gross sales.
- **Stockout Indicators / Risk Count:** Real-time tally of products/stores with inventory risk.

### 4. Interactive Data Visualizations
- **Weekly Sales Trend:** Line chart tracking sales progression over time.
- **Sales by Region:** Comparative bar chart highlighting performance across regions.
- **Category Performance:** Donut / horizontal bar chart showing category distribution.
- **Store Leaderboard:** Top and bottom store rankings.
- **Stockout Risk Grid:** Visual indicator table mapping critical stock levels.

### 5. Automated Business Insights
Auto-generates actionable, plain-language summaries based on current filters:
- **Regional Highlights:** Outlines top and underperforming geographical zones.
- **Target Tracking:** Flags stores failing to meet sales benchmarks.
- **Quality Alert:** Pinpoints product categories experiencing elevated return rates.

### 6. Export & Report Sharing
- One-click option to export filtered summaries and business insight reports.
- Fully responsive layout optimized for desktop, tablet, and mobile views.

---

## 🛠️ Tech Stack & Prerequisites

- **Frontend Framework:** React / HTML5 / Tailwind CSS
- **Chart Library:** Chart.js / Recharts
- **Data Parsing:** SheetJS (`xlsx`) for client-side Excel processing
- **Hosting & CI/CD:** GitHub + Cloudflare Pages / Vercel

---

## 💻 Local Setup & Development

Follow these steps to run the application locally:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/vasanthravichanderan/stackai.git](https://github.com/vasanthravichanderan/stackai.git)
   cd stackai
