# 📦 Logistics: Delivery Delay Root Cause Analysis (SQL Project)

## 📌 Project Overview
This is my **first end-to-end SQL analytics project**, focused on analyzing **delivery delays in a logistics / food-delivery system**.  
The goal of the project is to identify **where and why delivery delays occur** and propose **data-backed solutions**.

The project uses **simulated, public-style operational data** modeled on real-world delivery platforms.

---

## 🎯 Business Problem
Late deliveries negatively impact:
- Customer satisfaction
- Platform ratings
- Partner (restaurant & rider) performance

This project answers key questions such as:
- At which stage do deliveries get delayed?
- Are delays more common during peak hours?
- Do certain restaurants, zones, or riders contribute more to delays?
- How can platforms proactively reduce delivery delays?

---

## 🧠 Analysis Approach
I performed a structured SQL-based analysis covering:
- Order → Dispatch → Delivery time breakdown
- Delay calculation vs promised delivery time
- Peak-hour delay analysis
- Restaurant SLA performance
- Rider efficiency and workload impact
- Zone-based delay patterns

Each analysis directly maps to a **business problem and a proposed solution**.

---

## 🗂️ Dataset Description
- **Data Type:** Simulated / public-style operational logistics data  
- **Tables Used:**
  - `orders`
  - `customers`
  - `restaurants`
  - `riders`
  - `dispatch_details`
  - `delivery_details`
- **Key Columns:**
  - `order_datetime`
  - `dispatch_datetime`
  - `delivery_datetime`
  - `promised_datetime`
  - `distance_km`
- **Time Range:** Multi-month operational data

⚠️ *Note: This is not real company data and is used purely for learning and demonstration purposes.*

---

## 🛠️ Tools & Technologies
- **Database:** PostgreSQL  
- **SQL Concepts Used:**
  - JOINs
  - CTEs
  - Window Functions
  - Date & Time Functions
  - Aggregations
  - CASE statements
- **Visualization:** Exported SQL results into charts for insights

---

## 📊 Key Insights
- Peak hours (lunch & dinner) show the highest delivery delays
- Restaurant preparation delays significantly impact overall delivery time
- High rider workload correlates with increased delivery delays
- Certain zones consistently underperform during high demand

---

## 🚀 Proposed Solutions
- Delay prediction before order confirmation (dynamic ETA)
- Peak-hour rider surge planning
- Restaurant SLA monitoring & penalties
- Smart rider assignment based on distance & load
- Zone-based pricing and delivery radius control

---

## 🔮 Future Scope
- Apply **machine learning models** to predict delays in real time  
- Use **time-series forecasting** for rider demand planning  
- Introduce **real-time dashboards** for operations teams  
- Integrate weather and traffic data for more accurate ETAs

---


---

## 🙋‍♀️ About Me
Hi, I’m **Juhi Moudekar**, a data analytics learner passionate about using data to solve real-world business problems.

This project represents my **first step into applied SQL analytics**, and I’m continuously improving it as I learn more.

🔗 Connect with me on LinkedIn  
www.linkedin.com/in/juhi-moudekar

---



