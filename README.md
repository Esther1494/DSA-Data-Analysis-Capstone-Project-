# 📊 Amazon Product Review Analysis (Excel-Based Case Study)

Welcome to my Excel-based data analysis case study! This project showcases how **Microsoft Excel** was used to clean, analyze, and visualize Amazon product review data to generate valuable business insights.

> **🔧 Tools Used:** Microsoft Excel (Formulas, Pivot Tables, Charts, Slicers, Dashboards)  
> **📁 Dataset Format:** `.xlsx`  
> **📈 Focus Areas:** Customer behavior, product performance, discount effect, engagement analysis  

---

## 📌 Project Summary

In this case study, I worked as a **Junior Data Analyst** at *RetailTech Insights* and was tasked with analyzing a dataset of Amazon product reviews. The project objective was to explore how customer ratings, reviews, discounts, and pricing interact to impact product performance and customer satisfaction.

The goal was to create a **clean, interactive Excel dashboard** for non-technical stakeholders and derive **data-driven recommendations** for marketing and product teams.

---

## 🎯 Key Objectives

- 🔍 Clean and prepare the raw dataset for analysis
- ⭐ Calculate average ratings and review volumes
- 💰 Analyze the relationship between product discounts and ratings
- 📊 Segment data by product category and pricing tiers
- 🏆 Identify top- and bottom-performing products
- 🧠 Provide actionable insights to inform product pricing and promotional strategies

---

## 🧰 Tools, Features & Techniques

| Category           | Details                                                                 |
|--------------------|-------------------------------------------------------------------------|
| **Software**        | Microsoft Excel (2016+)                                                 |
| **Data Cleaning**   | `IF()`, `TRIM()`, `CLEAN()`, `ISBLANK()`, conditional formatting        |
| **Analysis**        | `AVERAGEIFS()`, `SUMIFS()`, `COUNTIFS()`, `RANK()`, `VLOOKUP()`         |
| **Pivot Tables**    | Dynamic summary of product categories, ratings, review counts           |
| **Charts**          | Bar charts, pie charts, KPI cards, trend lines                          |
| **Dashboard Design**| Slicers, drop-downs, interactive filters, visual hierarchy              |

---

## 🧹 Data Cleaning Process

The raw dataset required several cleaning steps, all completed in Excel:

1. **Removed blank rows, duplicates, and inconsistent text formats**
2. **Created derived fields**, including:
   - `Discount %` = `(Original Price - Discounted Price) / Original Price`
   - `Rating Bucket` = grouped into *Excellent*, *Good*, *Average*, *Poor*
   - `Review-to-Product Ratio` = proxy for engagement
3. **Standardized product categories and currency formats**
4. Used **conditional formatting** to highlight anomalies (e.g., zero ratings with high reviews)

---

## 📊 Analysis Highlights

| Insight | Description |
|--------|-------------|
| ⭐ **Top-Rated Products** | Mostly had moderate discounts (10–25%), indicating value-price sweet spot |
| 🚨 **Heavily Discounted Products** | (>40%) had lower average ratings, suggesting quality concerns or overstock issues |
| 📦 **High Engagement Categories** | Electronics and home goods had the most customer reviews |
| 📈 **Revenue Opportunity** | Mid-priced products ($25–$75) had the highest review volume and ratings—ideal for upselling |
| 🧩 **Category Gaps** | Some high-rated categories had low review volumes—potential under-marketed segments |

---

## 📊 Interactive Excel Dashboard

The final dashboard was designed to be used by non-technical stakeholders in product and marketing teams.

### 🧩 Features:
- ✅ KPI Cards for Average Rating, Discount %, and Total Reviews
- 📈 Pivot Charts for:
  - Product Ratings by Category
  - Reviews vs. Discount Levels
  - Top 10 Products by Rating and Review Count
- 🔘 Slicers for:
  - Category
  - Price Tier
  - Rating Bucket

> 📷 **Preview the Dashboard**:  
> ![Screenshot](https://drive.google.com/uc?export=view&id=1qpjENOJ1J1s-zBO9gx7z0IzzR5mWPa8p)


---

## 📁 Repository Structure

```bash
Amazon_Product_Review_Analysis/
│
├── 📄 Amazon_Review_Data.xlsx               # Cleaned dataset (Excel)
├── 📄 Amazon_Review_Analysis.md             # Step-by-step explanation of analysis
├── 📄 Dashboard_Screenshot_Amazon.png       # Screenshot of the final dashboard
└── 📄 README.md                              # Project documentation (this file)
