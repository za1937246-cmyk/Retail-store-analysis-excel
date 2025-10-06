
# 🛍️ Retail Store Sales Analysis
## 📌 Project Overview

This project analyzes retail store sales data to extract meaningful insights and improve business decision-making. The workflow covers **data cleaning**, **processing**, **statistical analysis**, **automation**, and **dashboard creation** using **Microsoft Excel**.

## 🔧 Tools & Techniques Used

- **Microsoft Excel**

- **Data Cleaning:** Remove duplicates, blanks

- **Data Processing:** Calculated fields like delivery time, revenue, profit, costs

- **Data Analysis ToolPak:** Descriptive Statistics, Hypothesis Testing

- **Macros & VBA:** Data Entry Form)

- **KPI calculations:** formulas: SUM, AVERAGE, IF, etc.

- **Dashboard:** Pivot Tables, Charts, Slicers, KPIs.

## 📂 Project Workflow
### 1️⃣ Data Cleaning

- Removed duplicates and blank records.

- Standardized columns Customer Name, Order Date, Delivery Date, Quantity, Unit Price, Status, Country, etc.

### 2️⃣ Data Processing

Created new calculated fields:

Delivery Time = Delivery Date – Order Date

Total Cost = Quantity × Unit Price

Sales Revenue = Selling Price × Quantity

Net Profit = Revenue – Cost

Extracted Year, Month, Day from dates.

### 3️⃣ Statistical Analysis

- **Used Excel Data Analysis ToolPak:**

Descriptive Statistics → Found mean, median, mode, variance, skewness, kurtosis for sales, profit, quantity, etc.

Hypothesis Testing (T-Test) →

H₀: Delivery time does not affect order returns.

H₁: Longer delivery time increases return likelihood.

✅ Result: Rejected null hypothesis. Orders with longer delivery times (~2 days more) are significantly more likely to be returned.

### 4️⃣ Data Entry Form (Automation)

Created a user-friendly data entry form using Excel Developer & VBA.

Automated process to add new records directly to the dataset.

### 5️⃣ KPIs & Dashboard

The interactive Excel dashboard was designed with KPIs, charts, and slicers to provide a complete sales overview.

## 🔹 Key Performance Indicators (KPIs)

**Total Revenue:** $775,811

**Total Costs:** $504,186

**Net Profit:** $271,625

**Total Orders:** 562

**Orders Status:** 52% Completed, 48% Returned

## 🔹 Dashboard Charts & Visuals

- Revenue by Country (Map Chart) → Shows revenue contribution by region, highlighting top and underperforming markets.

- Revenue, Cost & Profit by Category (Clustered Column Chart) → Compares financial performance across Apparel, Books, Electronics, Groceries, and Home Décor.

- Monthly Revenue, Cost & Profit Trends (Line Chart) → Displays seasonal fluctuations and profitability trends over the year.

- Daily Revenue Trends (Bar Chart) → Analyzes weekday sales patterns (highest on Wednesday, lowest on Tuesday).

- Orders by Status (Doughnut Chart) → Visualizes completed vs. returned orders.

- % of Orders by Payment Method (Pie Chart) → Highlights customer payment preferences (Bank Transfer, Mobile Money, Credit Card, Cash).

- Slicers (Filters) → Allow filtering by Country and Category for deeper exploration.

## 📊 Dashboard Preview:

### 💡 Key Insights

- **High Return Rate:** Nearly 48% of orders are returned, highlighting major customer satisfaction or logistics issues.

- **Category Trends:** Electronics and Apparel dominate sales, while Home Décor performs poorly.

- **Geographic Performance:** Significant revenue concentration in one country (~12x higher than lowest country).

- **Customer Payment Preferences:** Majority prefer digital (Bank Transfer & Mobile Money).

- **Delivery Impact:** Late deliveries strongly increase return probability (validated with t-test).

## 🚀 Recommendations

Investigate product quality/logistics issues causing high returns.

Improve delivery efficiency — focus on reducing >7-day deliveries.

Expand marketing efforts in underperforming countries.

Leverage midweek promotions to capitalize on peak sales days.

Encourage digital payments with discounts or cashback offers.

## 📫 Connect With Me

GitHub: YourUsername

LinkedIn: Your LinkedIn Profile
# Retail-store-analysis-excel
