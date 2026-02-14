# 📊 Northwind Traders – Sales Analytics Project

## 📌 Project Overview

This project presents a comprehensive end-to-end Sales Analytics analysis for **Northwind Traders**, using structured SQL analysis and Power BI visualization.

The objective of this project is to evaluate business performance across sales, customers, products, workforce, pricing strategy, and supplier operations using a **MECE (Mutually Exclusive, Collectively Exhaustive)** analytical framework.

This project demonstrates:

- Data cleaning and transformation
- Relational data modeling
- SQL-based exploratory data analysis
- DAX-based business metrics
- Power BI dashboard development
- Structured executive reporting

---

# 🎯 Business Objective

To analyze Northwind Traders’ business performance and answer key questions such as:

- What drives revenue growth?
- Which products and categories perform best?
- How do customers behave?
- Are pricing and demand aligned?
- How efficient are shipping operations?
- Are supplier risks diversified?

---

# 🗂 Dataset

The dataset consists of 8 core relational tables:

- Customers
- Orders
- Order Details
- Products
- Categories
- Employees
- Suppliers
- Shippers

The data was originally provided in CSV/Excel format and transformed for analytical modeling.

---

# 🧹 Data Cleaning & Transformation (Power Query)

Data preparation steps included:

- Replacing null values (Region, Postal Code, Fax, etc.)
- Removing unnecessary columns (images, homepage links, photos)
- Creating consistent headers
- Formatting date columns
- Handling missing ShippedDate using average fulfillment lag logic
- Ensuring referential integrity across tables

---

# 🏗 Data Modeling

A relational star-schema style model was built in Power BI:

- Fact Table: Order Details
- Dimension Tables: Customers, Products, Employees, Suppliers, Shippers, Categories
- Proper primary and foreign key relationships established
- Single-direction filtering applied

---

# 🧮 SQL Analysis (EDA)

SQL was used to answer 14 structured business questions, including:

1. Average number of orders per customer
2. High-value repeat customers
3. Customer clustering by spend and category
4. Revenue contribution by product and category
5. Order frequency and purchase intervals
6. Employee distribution by region and title
7. Hiring trends
8. Product pricing vs stock vs performance
9. Monthly product demand trends
10. Sales anomaly detection
11. Supplier pricing and regional analysis
12. Supplier concentration risk

Each SQL query was structured with aggregation, ranking, and window functions where required.

---

# 📈 Power BI Analysis & Visualization

Power BI was used to create structured visuals answering business-focused questions:

### Key Visuals Created:

- Revenue Trends (Line Chart)
- Top 5 Products by Sales Volume (Bar Chart)
- Revenue by Country (Column Chart)
- Late Shipment Percentage (Operational KPI)
- Category Contribution (Treemap)
- Employee Reporting Hierarchy (Matrix)
- Order Value Distribution (Histogram)
- Pricing vs Units Sold (Scatter Plot)

DAX measures created:

- Order Value
- Total Orders
- Average Order Value
- Total Quantity Sold
- Late Shipment %
- Customer Contribution %

---

# 🧠 MECE Analytical Framework

The project was structured into five mutually exclusive analytical categories:

1. **Sales Performance**
2. **Customer Analysis**
3. **Product & Category Analysis**
4. **Operations & Logistics**
5. **Supplier & Procurement Analysis**

This framework ensures structured storytelling and non-overlapping insights.

---

# 📊 Final Deliverables

- Power BI Report (.pbix)
- SQL Query Scripts
- MECE Framework Document
- Executive PPT Presentation
- 1080p Analytical Visual Framework
- Video Presentation (4–5 mins)

---

# 🔍 Key Insights

- Revenue is concentrated among a limited set of high-performing products.
- Customer revenue is skewed toward repeat high-value buyers.
- Certain regions dominate revenue contribution.
- Shipping delays vary by shipper.
- Pricing does not always negatively correlate with demand.
- Supplier pricing differs significantly by country.
- Some product categories show supplier concentration risk.

---

# 🛠 Tools & Technologies

- SQL (PostgreSQL / pgAdmin)
- Power BI Desktop
- DAX
- Power Query
- Excel
- GitHub

---

# 📁 Repository Structure

- /SQL
     northwind_queries.sql
- /PowerBI
    Northwind_Sales_Analytics.pbix
- /PPT
    Northwind_Traders_Sales_Analytics.pptx
- /MECE
    Northwind_MECE_Framework.pdf
- README.md



---

# 🚀 Project Highlights

✔ End-to-end analytics workflow  
✔ Business-focused structured insights  
✔ Clean relational modeling  
✔ Executive-ready visualization  
✔ Portfolio-grade documentation  

---

# 👤 Author

[G S Shreyas]

Data Analytics Project – Sales Performance Case Study
