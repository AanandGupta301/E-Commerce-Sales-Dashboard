# 🛒 E-Commerce Sales Analysis Dashboard

An interactive **E-Commerce Sales Analysis Dashboard** built using **Power BI** and **PostgreSQL** to analyze sales performance, revenue, orders, customers, products, and payment information.

## 📊 Dashboard Preview

![E-Commerce Sales Dashboard](ecommerce_analysis.png)

## 🎯 Project Objective

The main objective of this project is to analyze e-commerce sales data and create an interactive dashboard that helps understand:

- Overall revenue performance
- Total number of orders
- Total customers
- Average Order Value
- Product and category performance
- Customer distribution
- Sales trends and business performance

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and data visualization
- **PostgreSQL** – Database and data management
- **DAX** – Measures and calculations
- **Power Query** – Data transformation and cleaning
- **GitHub** – Project documentation and version control

## 📁 Dataset / Data Model

The Power BI data model contains the following tables:

### Customers
- customer_id
- customer_name
- city
- state
- signup_date

### Orders
- order_id
- customer_id
- order_date
- price
- product_id
- quantity
- status

### Products
- product_id
- product_name
- category
- sub_category

### Payments
- payment_id
- order_id
- payment_method
- payment_status

## 🔗 Data Model

The project uses relationships between Customers, Orders, Products, and Payments to create an integrated e-commerce analysis model.

## 📌 Key KPIs

The dashboard includes important business KPIs such as:

- **Total Revenue:** 56.55M
- **Total Orders:** 2K
- **Total Customers:** 297
- **Average Order Value:** 37.70K

## 📈 Dashboard Features

- KPI cards for key business metrics
- Interactive Power BI visualizations
- Customer and order analysis
- Product and category analysis
- Revenue analysis
- Payment analysis
- Interactive filtering and cross-filtering
- Relational data model using multiple tables

## 💡 Key Insights

The dashboard provides a single view of e-commerce performance and helps identify patterns in:

- Revenue generation
- Customer activity
- Order performance
- Product performance
- Category-level sales
- Payment behavior

## 📂 Project Files

| File | Description |
|------|-------------|
| `Ecommerce_analysis.pbix` | Power BI dashboard file |
| `ecommerce_analysis.png` | Dashboard preview image |
| `README.md` | Project documentation |

## 🚀 How to Use

1. Download the `Ecommerce_analysis.pbix` file.
2. Open it using **Microsoft Power BI Desktop**.
3. If required, configure the PostgreSQL data source.
4. Refresh the data.
5. Use the dashboard filters and visuals for analysis.

## 📚 Skills Demonstrated

- Data Analysis
- Data Cleaning
- Data Modeling
- DAX
- Power BI Visualization
- PostgreSQL
- SQL
- Business Intelligence
- Dashboard Development
- Data Storytelling

## 👨‍💻 Author

**Aanand Gupta**

Data Analyst | Power BI | SQL | PostgreSQL | Excel


