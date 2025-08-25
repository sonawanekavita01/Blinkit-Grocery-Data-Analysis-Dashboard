# Blinkit-Grocery-Data-Analysis-Dashboard


📖 Project Summary

This project focuses on analyzing the sales and operational data of Blinkit (an Indian quick-commerce grocery delivery platform) using interactive dashboards and exploratory data analysis techniques. The goal is to extract key insights on product performance, outlet types, customer preferences, and pricing strategies using Python or Power BI/Tableau, enabling data-driven business decisions.

🎯 Objectives

Analyze sales distribution across item types, outlet types, and locations.

Identify top-performing product categories and outlets.

Explore the relationship between product visibility, MRP, and sales.

Build a user-friendly interactive dashboard for decision-makers.

Provide actionable business insights with visual storytelling.

📊 Dataset Description

A publicly available dataset (commonly from Kaggle or Blinkit-inspired mock data) was used.

Feature Name	Description
Item_Identifier	Unique ID for each product
Item_Weight	Weight of the product (in kg)
Item_Fat_Content	Fat content: Low Fat / Regular
Item_Visibility	% of total display area allocated to the product
Item_Type	Category (e.g., Dairy, Snacks, Soft Drinks)
Item_MRP	Maximum Retail Price (₹)
Outlet_Identifier	Unique ID for each outlet
Outlet_Establishment_Year	Year when the outlet was established
Outlet_Size	Small / Medium / High
Outlet_Location_Type	Tier-1, Tier-2, Tier-3
Outlet_Type	Grocery Store / Supermarket Type 1, 2, 3
Item_Outlet_Sales	Total sales of the product in that outlet
🧠 Tools & Technologies Used

🐍 Python: Pandas, NumPy, Matplotlib, Seaborn, Plotly

📈 Power BI / Tableau: For interactive dashboards

📊 MS Excel: Data cleaning & pivot analysis (optional)

📄 Jupyter Notebook: For step-by-step EDA

🔍 GitHub: For version control and project sharing

🧼 Data Cleaning & Pre-processing

Handling missing values (Item_Weight, Outlet_Size).

Encoding categorical variables (Item_Fat_Content, Outlet_Type).

Normalizing inconsistent values (e.g., LF, low fat → Low Fat).

Outlier detection using boxplots and z-scores.

Feature engineering (e.g., age of outlet = current year − establishment year).

🔎 Exploratory Data Analysis (EDA)

Key visualizations included:

🔹 Distribution of sales by Item_Type

🔹 Sales vs. Item_MRP (to observe pricing impact)

🔹 Average sales per Outlet_Type

🔹 Top 10 items by sales

🔹 Correlation heatmap of numerical variables

🔹 Sales by Outlet_Location_Type (Tier-wise)


📊 Dashboard Features (Power BI)

✅ Interactive filters (by outlet type, item type, tier, year)

✅ KPI cards: Total Sales, Avg MRP, Total Items

✅ Donut chart: Sales share by Item_Type

✅ Map / bar chart: Sales by Outlet_Location_Type

✅ Trend line: Sales over time or outlet age

🎨 Sample Dashboard Layout


<img width="1920" height="1080" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/d8486514-b21e-4648-bcd0-7d08ca033785" />


<img width="1920" height="1080" alt="Screenshot (154)" src="https://github.com/user-attachments/assets/23685ea8-5224-4b8d-95f5-255046b08d54" />

🧩 Key Insights

📌 Top-performing item categories: Fruits & Vegetables, Snack Foods, Dairy.

📌 Supermarket Type 1 generated the highest sales volume.

📌 Tier-3 locations performed better than Tier-1 in average sales.

📌 Products with higher visibility had slightly higher sales.

📌 Outlets with longer operational history had stronger sales performance.

🏁 Conclusion

This analysis helps stakeholders at Blinkit (or similar quick-commerce companies) to:

🧭 Focus on high-performing categories

🛍 Optimize outlet locations and sizes

💰 Adjust pricing strategies based on MRP vs. sales behavior

📦 Improve product placement and visibility in stores
