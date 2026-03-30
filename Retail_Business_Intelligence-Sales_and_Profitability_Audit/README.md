# Retail Business Intelligence: Sales & Profitability Audit (Power BI)

## 📌 Project Overview
This project analyzes the **Sample Superstore (USA)** dataset to evaluate **sales performance, profitability, discount impact, and regional inefficiencies** using **Power BI**.

The goal of the analysis is not just to visualize data, but to **identify profit drivers, loss-making areas, and actionable business insights** that can support better pricing and discount decisions.

---

## 🎯 Business Objectives
The analysis answers the following key questions:

- Is the business profitable overall?
- Which categories and sub-categories drive profit and losses?
- Which states and cities generate high sales but low or negative profit?
- How does discounting impact profitability?
- Where can the business improve margins without increasing sales volume?

---

## 🗂️ Dataset Information
- **Dataset:** Sample Superstore
- **Geography:** United States (50 states)
- **Granularity:** Order-line level transactions
- **Key Columns:**
  - Sales (post-discount)
  - Profit (post-discount and cost)
  - Quantity
  - Discount
  - Category / Sub-Category
  - Customer Segment
  - State / City
  - Order Date

⚠️ **Important Assumptions**
- `Sales` and `Profit` values are already **post-discount**
- `Discount` is analyzed for **impact**, not reapplied
- Cost, unit price, and list price are **not available** and are not derived

---

## 🛠️ Tools & Technologies
- **Power BI**
  - Power Query for data preparation
  - DAX for KPI calculations
- **GitHub**
  - Version control
  - Project documentation

---


## 📊 Key KPIs
- Total Sales
- Total Profit
- Profit Margin
- Order Count
- Total Quantity
- Average Discount

All KPIs are calculated using **DAX** and used consistently across visuals.

---

## 🔍 Key Insights
- The business is profitable overall, but profitability is **uneven**
- **Technology** and **Office Supplies** drive most of the profit
- **Furniture**, especially **Tables and Bookcases**, generates high sales but low or negative profit
- Several states and cities show **high sales with persistent losses**
- Heavy discounting (typically above ~30%) is strongly associated with negative profit
- High-volume customer segments are not always the most profitable

---

## 💡 Recommendations
### Short-Term
- Cap discounts on loss-making sub-categories
- Review pricing strategy in high-loss states and cities
- Shift focus from revenue-only metrics to profit-based KPIs

### Long-Term
- Implement discount governance at regional and city levels
- Prioritize high-margin categories over high-volume sales
- Track profitability trends alongside sales growth

---

## 📁 Repository Structure
```
├── data/ # Raw dataset
├── powerbi/ # Power BI (.pbix) file
├── images/ # Dashboard screenshots
├── presentation/ # PPT summary of analysis
├── README.md # Project documentation
```

---

## 📌 How to Use This Project
1. Download the `.pbix` file from the `powerbi/` folder
2. Open it in Power BI Desktop
3. Explore dashboards using slicers (Region, Segment, Date)
4. Review the presentation for summarized insights and recommendations

---

## 📈 Outcome
This project demonstrates:
- Business-first analytical thinking
- Proper use of Power BI for decision-making
- Strong understanding of profitability, discount impact, and regional performance

It is designed to reflect **real-world analytical reasoning**, not just dashboard creation.

---

## 👤 Author
**Anis Ahmed**  

---

## Dashboard Visual

![Sales and Profit Overview](Dashboard-Images/Sample%20Superstore_page-0001.jpg)

![Sales & Profit Analysis](Dashboard-Images/Sample%20Superstore_page-0002.jpg)

![State-wise Profit and Sales Analysis](Dashboard-Images/Sample%20Superstore_page-0003.jpg)



