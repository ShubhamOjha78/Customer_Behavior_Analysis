# 🧠 Customer Behavior Analysis

## 📋 Overview  
This project focuses on analyzing customer behavior using data analytics.  
It covers the complete workflow — from data cleaning and exploration in Python, SQL integration through MySQL, dashboard creation in Power BI, and business reporting using Gamma.  
The goal is to uncover insights into customer purchasing patterns and help businesses make data-driven decisions.

---

## 📊 Dataset  
- **Source:** Sample customer transactional dataset  
- **Format:** CSV / Excel  
- **Size:** ~5,000 records  
- **Key Fields:**  
  `customer_id`, `age`, `gender`, `purchase_amount`, `product_category`, `region`, `purchase_date`
### Dataset Used
-<a href="https://github.com/ShubhamOjha78/Customer_Behavior_Analysis/blob/main/customer_shopping_behavior.csv">Dataset</a>

---

## 🛠️ Tools & Technologies  

| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database | MySQL Workbench / MySQL Server |
| Visualization | Power BI |
| Reporting | Gamma App |
| Version Control | Git & GitHub |

---

## ⚙️ Steps Followed  

### 1. **Data Loading**
- Imported dataset into Python using `pandas`.
- Inspected dataset using `.info()`, `.describe()`, and `.head()`.

### 2. **Data Cleaning**
- Removed missing values and duplicates.  
- Renamed inconsistent columns (e.g., `CustomerId → customer_id`).  
- Created derived columns such as age groups and total spending.

### 3. **Exploratory Data Analysis (EDA)**
- Analyzed customer demographics, purchase frequency, and spending patterns.  
- Visualized insights using `Matplotlib` and `Seaborn`.

### 4. **SQL Integration**
- Connected Python to MySQL using `mysql.connector`.  
- Created and populated database tables.  
- Executed SQL queries for segmentation, aggregation, and ranking.

### 5. **Dashboard Creation**
- Loaded the cleaned dataset into Power BI.  
- Built interactive visuals showing:  
  - Sales by product category and region  
  - Customer segmentation by age and gender  
  - KPIs like total sales and repeat purchases  

### 6. **Reporting**
- Created a formal **business report** summarizing key insights.  
- Designed a **presentation using Gamma** for stakeholder review.

---

## 📈 Dashboard Preview  
Power BI Dashboard includes:  
- 💰 Total Sales & Revenue KPIs  
- 👥 Customer Demographics Overview  
- 🛒 Product Category Performance  
- 🌍 Regional Purchase Heatmap  

- Dashborad Interaction
-<a href="https://github.com/ShubhamOjha78/Customer_Behavior_Analysis/blob/main/Dashboard.PNG">View Dashboard</a>


---
- Dashboard Image
<img width="939" height="458" alt="Dashboard.PNG" src="https://github.com/ShubhamOjha78/Customer_Behavior_Analysis/blob/main/Dashboard.PNG" />

---

## 🧾 Results & Insights  
- Identified top 3 customer segments contributing the most to sales.  
- Found patterns between age groups and product preferences.  
- Suggested personalized marketing strategies for better retention.  

---


