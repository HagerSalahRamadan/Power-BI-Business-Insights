# 📊 Business Insights Dashboards  
## From Data to Insights: Power BI Business Dashboard  

---
### 📊 Presentation Slides
📄 [View Full Presentation (PDF)](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/Presentation_Sales%20Analysis%20Project.pdf)


### 📊 Documentation Slides
📄 [View Full Documentation (PDF)](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/Documentation_Sales%20Analysis.pdf)

---

## 🚀 Project Overview  
This project analyzes **Sales, Operations, and Marketing data** to deliver actionable business insights using **Power BI** dashboards.  
The goal was to transform raw data into meaningful **KPIs, trends, and recommendations** that support decision-making at the executive, operational, and marketing levels.  

---

## 📂 Dataset  
The dataset includes:
- **Products & Subcategories** (Camcorders, Projectors, Home Theater, etc.)
- **Stores & Employees** (306 stores, ~11,000 employees)
- **Sales & Orders** (revenue, profit, cost, order details)
- **Promotions & Discounts** (0%, 5%, 10%, 15%, 20%)
- **Marketing Metrics** (Clicks, Impressions)

---

## 🎯 Objectives  
- Track **C-Level KPIs** (Sales, Profit, Growth, Discounts).  
- Monitor **Operations & Stores** performance (Orders, Employees, Closures).  
- Evaluate **Marketing & Promotions** (Clicks, Impressions, Discount Effectiveness).  
- Identify **Seasonality, Weaknesses, and Growth Opportunities**.  

---

## 🛠️ Process  

### 1️⃣ Data Understanding  
- Explored dataset tables & columns.  
- Identified fact & dimension tables (Sales, Orders, Marketing vs Products, Stores, Promotions).  

### 2️⃣ Data Modelling  
- Built a **Snowflake Schema** in Power BI.  
- Created relationships between **Products, Stores, Promotions, and Marketing Data**.  

#### 🧩 Data Model  
The project uses a **Snowflake Schema** in Power BI to organize data efficiently.  
Below is a visual of the data model connecting Products, Stores, Promotions, and Marketing data.

![Data Model](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/model.jpg)

---

### 3️⃣ KPIs & Measures (DAX)  
- `Total Sales`, `Total Profit`, `Profit Margin %`  
- `Orders Count`, `Quantity Sold`, `Avg. Order Value`  
- `YTD vs LY Sales`, `Target Achievement %`  
- `Total Clicks`, `Impressions YTD`, `Promotions by % Discount`  

### 4️⃣ Dashboard Development  
Created **3 interactive dashboards**:

#### 🖥️ Dashboards Overview  

1. **C-Level Executive** → KPIs, yearly targets, subcategories, KPI achievements. 
![Dashboard Screenshot](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/1.C-Level%20Executive%20Dashboard.jpg)

2. **Sales & Operations** → Sales by country, stores, employees, pipeline, store closures. 
![Dashboard Screenshot](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/2.Operations%20%26%20Sales%20Team%20Dashboard.jpg)

3. **Marketing & Promotions** → Clicks over time, impressions, discounts analysis.  
![Dashboard Screenshot](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/3.Marketing%20%26%20Promotions%20Dashboard.jpg)


---

## 🌟 Key Highlights & Features  

### 📊 Multi-Dashboard Structure  
- **Sales Performance Overview** — showing KPIs (Actual vs. Target), trends, and period comparisons.  
- **Marketing Analysis** — exploring promotions, discounts, and campaign effectiveness.  
- **Product & Category Insights** — deep dive into sales by product, subcategory, and region.  

---

### ⚙️ Advanced Power BI Functionalities Used  
- **Dynamic Tooltips** → Display detailed KPI lists when hovering (e.g., over-target vs. under-target KPIs).  
- **Drill-through Pages** → Allow users to explore data at a more granular level.  
- **Button-based Date Selection** → Users can toggle between **YTD**, **Custom Time Range**, or **Manual Periods** dynamically.  
- **Visual Interaction & Highlighting** → When selecting a specific month, it’s highlighted with a different color while keeping other months visible for context.  

---

### 🔒 Row-Level Security (RLS)  
- **User A** → Access to all “TV and Video” category data.  
 ![RLS Test Screenshot](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/RLS%20A%20USER.jpg)

- **User B** → Access limited to “Car Video” subcategory.  
 ![RLS Test Screenshot](https://github.com/HagerSalahRamadan/Power-BI-Business-Insights/blob/main/RLS%20B%20user.jpg)

---

### 📈 KPIs Tracking  
Two main KPI cards show:
- ✅ **KPIs achieving the target**  
- ⚠️ **KPIs under target**  
Each card includes **tooltips** listing exact KPI names and values for quick insight.  

---

## 🎯 Dashboard Objectives  
✔️ Provide clear visibility into KPI performance and progress toward targets.  
✔️ Enable decision-makers to monitor promotions and discount effectiveness.  
✔️ Allow dynamic exploration of data through user interactivity and secure access.  
✔️ Support data-driven marketing and sales strategies.  

---

### 5️⃣ Insights Extraction  
- Seasonal sales trends (**Q1 weak, December peaks**).  
- Market leaders (**US, China, Germany, France**).  
- Product winners (**Camcorders, Projectors**).  
- Declining clicks (–14%), underutilized discounts (5–15%).  

---

### 6️⃣ Recommendations  
- Built strategies from insights to improve forecasting, product focus, market expansion, and marketing efficiency.  

---

## 📊 Key Insights  
- **Executive** → $8.34B sales, 60% profit margin (solid performance, weak Q1).  
- **Operations** → US (96% NA sales), China (63% Asia). 83% store closures = relocations.  
- **Marketing** → Clicks ↓14% (2023→2025). Discounts focus on 10–20%, missing mid-range.  

---

## ✅ Recommendations  
- Improve **forecasting & stock planning**.  
- Expand in **China & Canada**, strengthen US base.  
- Focus on **top products** (Camcorders, Projectors).  
- Reposition **Home Theater Systems** with better features.  
- Launch **seasonal campaigns** (Ramadan, Black Friday, Summer).  
- Revive **mid-range discounts (5–15%)**.  
- Boost **online channel (22%)** with UX/UI improvements.  
- Use **flash deals & targeted promotions** for engagement.  

---

## 📌 Final Note  
This project demonstrates the **end-to-end data analysis lifecycle**:  
From **data exploration** → **data modelling** → **DAX measures** → **dashboards** → **insights** → **recommendations**.  

It highlights how **data storytelling** can transform raw data into strategic business actions.  

## Contact
For any questions Contact via email **hagersalah.r39@gmail.com**.
