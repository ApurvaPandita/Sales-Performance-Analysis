# Sales-Performance-Analysis
> A multi-page Power BI dashboard that turns raw sales, product, and customer feedback data into an interactive tool for tracking performance and spotting trends at a glance.

---

## 📋 Overview
This project is a multi-page Power BI (.pbix) dashboard built to help stakeholders monitor sales performance, analyze trends across channels and products, and track customer satisfaction. It combines KPI summary cards, trend charts and detailed tables/pivot tables across three report pages, with slicers for interactive filtering.

---

## ❓Problem Statement
Sales, product, and customer-feedback data typically live in separate tables and are hard to interpret manually. Decision-makers need a single, interactive view that can answer:

- Which products, channels, and regions are driving performance?
- How is performance trending against last year (sales, profit, cost, ratings)?
- Where are customers reporting complaints or leaving negative feedback, and why?

---

## 📁 Dataset
The underlying data model contains the following tables:

- **Sales Data** – core fact table (containing all the sales related data)
-	**Calendar** – date dimension (Month, Year) for time-based trend analysis
- **Products Details** – product dimension (Product Name, Product Class, Products Category, Brand Name)
- **Location Details** – geographic dimension (Country, Geographic Region)
- **Channel Type Details** – sales channel classification (Channel Type)
- **Sales Channel Details** – sales channel details
- **Discount Details** – discount type information

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – report design and data modeling
- **Power Query** – data cleaning and transformation
- **DAX (Data Analysis Expressions)** – calculated measures and columns (e.g. Profit %, YoY change metrics)
- **Data Model** – relationships between the Sales Data fact table and supporting dimension tables

---

## Methods
1.	Data preparation – Cleaned and structured raw data into using Power Query.
2.	Data modeling – Built relationships between the Sales Data fact table and supporting dimension tables.
3.	DAX measures – Created KPIs such as Total Sales, Total Cost, Total Profit, Profit %, and year-over-year change metrics.
4.	Report design – Built three report pages using cards, bar/clustered bar charts, area charts, maps, tables/pivot tables, and slicers for interactivity.
5.	Interactivity – Added slicers so users can filter entire report dynamically.

---

## 💡Key Insights:
**Total revenue** across all four years is $1.09M with $205.51K in total profit and 41,750 units sold.
- Top-performing products by revenue: Prod - H ($181K), Prod - C ($177K), and Prod - B ($172K) lead the range
- **Top countries** by revenue: United States ($341K) is by far the largest market, followed by Switzerland ($150K), China ($112K), and Australia ($110K). 
- **By region:** Europe ($435K) narrowly leads America ($341K) in total revenue, with Asia ($203K) and Oceania ($110K) trailing. 
- **By sales channel:** Online is the top channel ($361K), ahead of Referral program ($265K), Store ($232K), and Affiliate program ($231K) — a fairly balanced mix across channels. 
- **By product class:** Premium ($506K) is the top most product selling class, followed by Elite($333K) and Standard($179K) 
- **Customer base:** New customers (4,695) outnumber returning customers (3,349), indicating a stronger contribution from customer acquisition than repeat purchases.
- **Customer satisfaction:** Average customer rating is 4.11 / 5, and 90%+ of transactions have "No Complaints." Among actual complaints, Delivery Issues (228), Packaging Issues (201), and Products Damaged (151) are the most common reasons.

---
## 📸 Dashboard Screenshots

---
## ✅Results & Conclusion
This dashboard turns four years of transaction data into a clear strategic view, not just a set of charts. New customers outnumber returning ones by a wide margin, so the next phase of growth should focus more on retention than acquisition. Revenue is concentrated — a handful of products and two regions (US and Europe) drive most of the sales — making them the natural priority for continued investment over broader expansion. Customer satisfaction is solid overall, but the complaints that do exist are mostly logistics-related (delivery and packaging), pointing to an operations fix rather than a product one. Overall, the dashboard gives the business a filtered, always-current view to defend what's working, push where there's room, and fix what's quietly leaking value.

---

## 🙋 Author

**Apurva Pandita**  
[LinkedIn](https://www.linkedin.com/in/apurva-pandita-b51812272/) · [GitHub](https://github.com/ApurvaPandita) · apandita04@gmail.com
