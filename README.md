# Sales Analytics Dashboard (Power BI)

A Power BI project analyzing sales performance across customers, orders, products, and campaigns — built on a multi-table dataset spanning orders, payments, shipments, inventory, and customer data.

---

## 📌 Project Overview

This dashboard tracks core sales performance metrics to support business decisions around revenue growth, profitability, and order behavior. It brings together order, customer, product, and campaign data into a single connected model.

**Key questions answered:**
- What's our profit margin, and how does it vary over time?
- How is revenue growing year-over-year?
- What's the average order value, and what drives it?

---

## 🧱 Process

**1. Data Cleaning**
Each source table was cleaned individually as it was brought into the model — handling nulls, standardizing formats, and removing duplicates before integration.

**2. Dimension Tables**
Built dimension tables first (customers, products, dates, etc.) to establish clean, deduplicated lookup entities.

**3. Fact Tables**
Built fact tables (orders, invoices, payments, shipments) to hold transactional/measurable data.

**4. Data Modeling**
Connected dimension and fact tables into a star-schema-oriented model, defining relationships to support accurate filtering and aggregation across the report.

**5. DAX Measures**
Built core measures including:
- **Profit Margin** — profitability as a % of revenue
- **YoY Growth** — year-over-year revenue/sales comparison
- **Average Order Value (AOV)** — average revenue per order

