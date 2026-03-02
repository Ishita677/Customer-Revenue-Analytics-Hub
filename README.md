# 🛒 E-Commerce Revenue & Customer Analysis

## 📌 Project Overview

This project analyzes the sales and revenue performance of an online retail business using transaction-level data. The objective is to extract meaningful business insights and provide strategic recommendations based on data-driven analysis.

The analysis focuses on:

* Revenue trends and seasonal patterns
* Country-wise revenue contribution
* Product-level performance
* Customer segmentation and revenue concentration
* Strategic business recommendations

---

## 📂 Dataset Overview

The dataset contains approximately **534,000 retail transactions** from an online retailer.

### Key Columns:

* Invoice Number
* Invoice Date
* Product Description
* Quantity
* Unit Price
* Customer ID
* Country

### Data Quality Observations:

* ~25% missing Customer IDs
* Negative quantities represent product returns
* Some duplicate records
* Certain rows contain invalid (≤ 0) prices

---

## 🧹 Section 2 — Data Cleaning & Preparation

The following preprocessing steps were performed to ensure accurate analysis:

* Removed duplicate records
* Eliminated rows where Price ≤ 0
* Retained negative quantities to account for product returns
* Converted `InvoiceDate` to proper datetime format
* Created a new column:

```
Revenue = Quantity × Price
```

These steps ensured the dataset was clean, structured, and business-ready.

---

## 📊 Section 3 — Revenue Overview & Key Business Metrics

### Key Performance Indicators:

* **Total Net Revenue:** ~9.75M
* **Unique Transactions:** 23,796
* **Total Units Sold:** ~5.57M
* **Return Impact:** ~-894K (~9.17% of net revenue)
* **Average Revenue per Transaction:** ~409.65
* **Average Units per Transaction:** ~234.17

These metrics establish a strong financial baseline for evaluating business performance.

---

## 📈 Section 4 — Monthly Revenue Trend Analysis

* Revenue remains relatively stable in early months.
* Significant growth observed in Q4.
* Peak revenue occurs in November.
* December decline is due to incomplete data (dataset ends on Dec 9).

The pattern highlights strong seasonal and holiday-driven demand.

---

## 🌍 Section 5 — Country-Level Revenue Analysis

* The **United Kingdom contributes 84%** of total revenue.
* Secondary markets: Netherlands, EIRE, Germany, France.
* Revenue drops sharply beyond top countries.

This indicates high geographic dependency and potential opportunity for international expansion.

---

## 🛍️ Section 6 — Product-Level Revenue Drivers

After excluding operational charges (e.g., POSTAGE, DOTCOM POSTAGE):

* **Top Revenue Product:** REGENCY CAKESTAND 3 TIER
* Products like JUMBO BAG RED RETROSPOT perform strongly in both volume and revenue.
* Some high-volume products (e.g., PAPER CRAFT, LITTLE BIRDIE) do not rank among top revenue generators.

This helps differentiate revenue drivers from volume drivers for better product strategy decisions.

---

## 👥 Section 7 — Revenue Distribution & Customer Segmentation

### Pareto Insight:

A small group of customers contributes a large portion of total revenue — a common retail pattern.

### Customer Segments Identified:

* High-frequency, high-revenue customers
* Low-frequency, low-revenue customers (long tail)

This supports targeted loyalty and retention strategies.

---

## 💡 Section 8 — Strategic Insights

* Revenue is highly concentrated among a small subset of customers.
* High-value customers drive both frequency and monetary performance.
* Long-tail customers collectively contribute meaningful revenue.
* Core products show strong product-market alignment.
* Geographic concentration presents both risk and growth opportunity.

---

## 🚀 Section 9 — Strategic Recommendations

* Implement loyalty programs for high-value customers.
* Promote top-performing products via bundling and cross-selling.
* Expand focus on secondary international markets.
* Develop campaigns to convert mid-tier and long-tail customers into repeat buyers.

---

## 🛠️ Skills Demonstrated

* Data Cleaning & Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Aggregation & Grouping
* Time-Series Analysis
* Customer Segmentation & Pareto Analysis
* Business Insight Generation & Storytelling

