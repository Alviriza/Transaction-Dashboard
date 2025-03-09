# 📊 Looker Studio Sales Dashboard

🚀 **Unlock Actionable Insights from Sales Data with Looker Studio**  

## 📌 Overview  
This project presents a **comprehensive Looker Studio Dashboard** designed to analyze sales transactions, customer behavior, and product performance. The dashboard transforms raw sales data into **interactive visualizations** that help businesses make **data-driven decisions** with ease.  

## 🔥 Key Features  
✅ **Revenue & Profit Analysis** – Track total revenue and profit before and after discounts.  
✅ **Customer & Transaction Insights** – Monitor unique customer engagement and transaction volume.  
✅ **Product & Category Performance** – Identify top-selling products and high-performing categories.  
✅ **Payment Method Usage** – Analyze customer preferences for different payment options.  
✅ **Discount vs. Profit Impact** – Evaluate how discounts influence revenue and profitability.  

## 📂 Dataset Used  
The dataset consists of transactional sales records with key attributes such as:  

- **Order Information**: `order_id`, `customer_id`, `order_date`, `payment_id`, `payment_method`  
- **Product Details**: `sku_id`, `sku_name`, `category`, `price`, `qty_ordered`  
- **Financial Metrics**: `before_discount`, `discount_amount`, `after_discount`, `profit`, `cogs`  
- **Customer Registration Date**: `registered_date`  

## 📊 Dashboard Visualizations  

### 🏆 Scorecards:  
- **Total Revenue** (`SUM(before_discount)`)  
- **Total Profit** (`SUM(profit)`)  
- **Total Quantity Sold** (`SUM(qty_ordered)`)  
- **Unique Customers** (`COUNT DISTINCT(customer_id)`)  
- **Total Transactions** (`COUNT DISTINCT(payment_id)`)  

### 📈 Charts & Tables:  
- 📉 **Revenue Trend (Line Chart)** – Sales trends over time.  
- 💳 **Payment Method Usage (Column Chart)** – Customer preference for payment methods.  
- 🥧 **Value Per Payment Method (Pie Chart)** – Contribution of each payment method to total revenue.  
- 📑 **Transaction Per Category (Table)** – Transaction volume by product category.  
- 📊 **Value Per Category (Column Chart)** – Total revenue by category.  
- 💰 **Profit vs. Discount Per Category (Column Chart)** – Impact of discounts on profitability.  
- 👥 **Customer Summary (Table)** – Revenue, quantity ordered, and discounts per customer.  
- 📦 **Product Summary (Table)** – Sales performance of each product.  

## 🎯 Why This Dashboard Matters  
💡 **Data-Driven Decision Making** – Make informed business decisions based on real data.  
📊 **Real-Time Insights** – Track performance instantly with interactive dashboards.  
📈 **Trend Identification** – Discover seasonal trends and customer buying behavior.  
💰 **Revenue & Profit Optimization** – Fine-tune pricing and discount strategies.  
💳 **Payment Behavior Analysis** – Understand and improve payment method preferences.  

## 🛠 How to Use the Dashboard  
1. 📥 **Data Preparation:** Ensure the dataset is structured correctly and uploaded to Google Sheets or a data warehouse.  
2. 🎨 **Looker Studio Integration:** Connect the data source and set up the dashboard in Looker Studio.  
3. 📊 **Explore Insights:** Interact with the dashboard to analyze trends and optimize business strategies.  

## 🚀 Future Enhancements  
🔹 Adding **predictive analytics** to forecast future sales trends.  
🔹 Integrating **customer segmentation** for personalized marketing strategies.  
🔹 Expanding the dashboard with **real-time data streaming**.  

## 🤝 Contributions & Feedback  
Contributions are welcome! If you have any suggestions, feel free to open an issue or submit a pull request. Let’s collaborate to make data analytics more powerful!  

📩 **Connect with me on [LinkedIn](https://www.linkedin.com/in/alviriza) to discuss more about this project!**  
