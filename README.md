# 📊 E-Commerce Sales Dashboard – Power BI Project
This project presents an interactive Power BI dashboard built to analyze and visualize sales and customer behavior for an e-commerce platform using real-world inspired datasets.

🗂️ Datasets Used

customer_details.csv – Customer demographics (Age, Gender, Location, Purchase Amount)

E-commerece_sales_data_2024.csv – Transaction-level data (Product, Date, User ID, Reviews, Orders)

🔗 Data Model

A One-to-Many relationship was created between:

customer_details[Customer ID] → E-commerce_sales_data[user id]

This ensures smooth integration of customer insights with transactional sales data.

🧠 Key DAX Measures

Total Purchase Amount

Average Purchase Value

Total Customers

Repeat vs New Customers

Average Review Rating

🧩 Dashboard Features

✅ KPI Cards (Top Row)

💰 Total Purchase Amount

👥 Total Customers

⭐ Average Rating

🔁 Repeat vs New

🛒 Total Orders

Styled with icons, custom color themes, and transparent backgrounds.

🌍 Geo Visualization

Filled Map showing Total Purchase Amount by City

Helps identify high-performing locations

📈 Customer & Sales Insights
Bar Chart: Purchase Amount by Age Group

Donut/Pie Chart: Gender-based Purchase Distribution

Bar Chart: New vs Repeat Customers

Top 10 Cities by Purchase Volume

🎛️ Slicer Panel (Interactive Filters)
Includes filters for:

Gender

Location

Age Group

Product Category

Customer Type (New vs Repeat)

Optional toggle button with bookmark enables a collapsible filter panel for a clean layout.

🎨 Design Approach
Clean, modern grid-based layout

Icons and transparent button overlays

Dashboard optimized for user-friendly analysis

📁 Files Included

.pbix Power BI file

Sample CSV datasets

README documentation

🚀 Outcomes

Business-ready Power BI dashboard

Helps identify top customers, locations, and product segments

Actionable insights into customer behavior and sales trends


