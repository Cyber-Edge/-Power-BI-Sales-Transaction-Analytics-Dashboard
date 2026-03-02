# 📊 Power BI Sales & Transaction Analytics Dashboard

A multi-page interactive Power BI report for analysing sales transactions, costs, profit, and country-level performance — built on the Frontier theme with rich slicing and drill-down capabilities.

# 📑 Table of Contents

📌 Project Overview

🗂️ Project Structure

⚙️ Tools

🗄️ Data Sources & Data Model

🔍 Key Observations & Business Recommendations


## 📌 Project Overview

This Power BI project delivers a 3-page executive sales dashboard that enables business users to monitor:

- 💰 Revenue, Profit, and Total Cost performance
- 🛒 Sales with and without discount (5%)
- 🌍 Country-level transaction breakdowns
- 📅 Time-based trends by Year, Month, Week, and Day
- 💳 Segmentation by Payment Mode and Sale Type
- 🚚 Operational costs — Transportation, Rent, and Tax

## ⚙️ Tools

| Tool | Version | Purpose |
|------|---------|---------|
| Power BI Desktop | Latest Version | open and edit the file |
| Power BI Service | 2023.11+ | Publish and share reports |
| Excel | Latest Version | Clean and modify data |

## 🗄️ Data Sources & Data Model

| Table | Type | Description | 
|-------|------|-------------|
| Transactions_Data | Fact Table | Core transaction records — sales, costs, discounts, taxes, payment modes, sale types | 
| Product_Data | Dimension | Product information linked to transactions | 
| Country_Data | Dimension | Country reference data used for geographic analysis |

## 🔍 Key Observations & Business Recommendations

| Data Area | Recommended Action | Priority |
|----------- |--------------------|----------|
| Discount Strategy | Evaluate whether the 5% discount is driving enough volume to justify the revenue loss. If discount sales are not significantly higher in volume, consider reducing or targeting discounts to specific sale types or countries only | 🔴 High |
| Transportation Cost | Audit logistics partners and shipping routes by country. Negotiate bulk shipping contracts or switch to regional fulfilment centres to reduce per-unit transportation costs | 🔴 High |
| Country Performance | Identify underperforming countries where Total Cost is high relative to sales. Consider reallocating marketing budget to high-performing markets or reviewing pricing strategy in low-margin regions | 🔴 High |
| Payment Mode Analysis | Analyse which payment modes correlate with higher order values or lower return rates. If one mode dominates, ensure payment infrastructure is optimised for it (e.g. card payment reliability, mobile payment adoption) | 🟠 Medium |
| Tax Burden Awareness | Review tax obligations by country to ensure compliance and identify any tax optimisation opportunities. High tax costs in specific regions could inform decisions about where to focus sales efforts | 🟠 Medium |
| Rent & Overhead Control | Compare rent costs against revenue per location or region. If rent is disproportionately high in low-revenue markets, consider renegotiating leases, downsizing, or shifting to remote/hybrid fulfilment models | 🟡 Low |
| Monthly Purchase Targets | Formalise procurement targets based on historical averages and seasonal demand. Set monthly purchase budgets in the data source so the gauge reflects real business targets rather than a proxy value | 🟡 Low |
