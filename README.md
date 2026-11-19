# 🛒 Apex Retail Group - First Quarter Performance Analysis
An interactive Power BI dashboard designed to analyze Q1 retail sales performance, customer behavior, gross margins, and root causes behind key performance gaps—now expanded with a dedicated **Investigation Dashboard**.

---

## 📷 Dashboard Preview (In Order)

![Main Dashboard](Screenshot%20Apex%20Main%20Dashboard.png)

![Investigation Dashboard](Screenshot%20for%20Apex%20Investigation%20Dashboard.png)

![Key Insights](Screenshot%20Apex%20Key%20Insights.png)

---

## 🔍 Investigation Dashboard Highlights

### 1. February Revenue Dip (Root Cause)
- **Finding:** February sales dropped to **$97.16K** (302 invoices) compared to January (**$116.35K**, 353 invoices) and March (**$109.46K**, 345 invoices)[cite: 4].
- **Root Cause:** Driven by fewer active days (**28 days** vs. 31 and 30) and a lower daily transaction rate (**10.79 invoices/day**), while average invoice value remained steady (**$321.72**), confirming lower traffic rather than smaller order sizes[cite: 5, 6].

### 2. Sales Team Gap (Samira vs. Top Performers)
- **Finding:** Samira recorded the lowest quarterly sales (~$8K) due to low transaction volume (19 of 1,000 invoices, or 1.9%) rather than low average invoice values or late onboarding[cite: 6].
- **Action:** Focus on daily/weekly deal targets, peer coaching from top performers (such as Samy at ~$128K), and reviewing low-rated orders or data completeness[cite: 6].

---

## 🎯 Business Problems & Solutions

### 1. Mid-Quarter Sales Drop (February Slump)
- **Problem:** Revenue fell to **$97.2K** in February compared to **$116.3K** in January.
- **Solution:** Targeted daily-traffic promotions during shorter calendar months to lift transaction frequency while maintaining average order value.

### 2. High Revenue vs. Low Margin Risk
- **Problem:** Total Q1 revenue reached **~$322.91K–$322.97K** against **$307.53K** COGS (**~$15.38K** gross income), resulting in a **4.76%** average gross margin.
- **Solution:** Focus on higher-margin product lines and tighten cost controls across categories.

### 3. Sales Team Performance Disparity
- **Problem:** Significant gap between top performer Samy (~$128K), Sally & Ahmed (~$93K each), and Samira (~$8K).
- **Solution:** Structured coaching, clear activity targets, and performance tracking by individual rep.

---

## 📊 Key Metrics & Features
- **Financial KPIs:** Total Revenue, COGS, Gross Income, and Gross Margin %.
- **Monthly & Daily Metrics:** Active Days, Total Invoices, Average Invoice Value, Average Daily Sales, and Average Invoices per Day[cite: 5].
- **Customer & Branch Breakdown:** Performance across Yangon, Mandalay, and Naypyitaw, customer type (Members vs. Normal), gender, and product lines.
- **Interactive Filtering:** Dynamic slicers and cross-filtering across months, branches, product lines, and sales reps.

---

## 💡 Strategic Insights
- **Top Product Lines:** Food & Beverages and Electronic Accessories lead gross income generation.
- **Customer Segments:** Revenue is nearly balanced between Members ($164K) and Normal customers ($159K), as well as Female ($168K) and Male ($155K) shoppers, creating a clear opportunity to convert normal buyers into repeat members.

---

## 🛠️ Tools & Technologies
- **Data Cleaning & Transformation:** Power Query & Microsoft Excel
- **Data Modeling & Calculations:** Power BI & DAX (`SUM`, `DISTINCTCOUNT`, `DIVIDE`, etc.)
- **Visualization & Reporting:** Power BI Interactive Dashboards & Investigation Views.

---

## 📦 Repository Structure
```text
Apex-Retail-Group-Q1-Analysis/
├── README.md
├── Apex_Retail_Group_Q1_Dashboard.pbix
└── assets/
    ├── 01-main-dashboard.png
    ├── 02-investigation-dashboard.png
    └── 03-key-insights.png
