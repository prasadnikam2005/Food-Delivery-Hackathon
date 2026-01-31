# 🍔 Food Delivery Data Analysis Hackathon 📊

---

## 📌 Project Overview
This project was developed as part of a **Data Analysis Hackathon** to simulate a **real-world data engineering and analytics workflow**.  
The objective was to **integrate multiple data sources**, perform **end-to-end analysis**, and extract **actionable business insights** for a food delivery platform.

---

## 📁 Dataset Description
The analysis is based on **three heterogeneous datasets**:

### 🧾 orders.csv
Transactional **order-level data** including:
- **Order ID**
- **User ID**
- **Restaurant ID**
- **Order Date**
- **Total Amount**

### 👤 users.json
User **master data** including:
- **User ID**
- **User Name**
- **City**
- **Membership Type** (**Gold / Regular**)

### 🍽️ restaurants.sql
Restaurant **reference data** including:
- **Restaurant ID**
- **Cuisine Type**
- **Rating**

---

## 🛠️ Tech Stack
- **Programming Language**: **Python 3.x**
- **Libraries Used**:
  - **Pandas** – data manipulation
  - **SQLite3** – SQL data extraction
  - **Matplotlib / Seaborn** – data visualization
- **Environment**: **Jupyter Notebook**

---

## ⚙️ Implementation Workflow

### 🔹 Step 1: Data Loading & Extraction
- Loaded **CSV files** using **Pandas**
- Parsed **JSON data** into structured DataFrames
- Executed **SQL script** using an **in-memory SQLite database**

---

### 🔹 Step 2: Data Integration
- Performed **Left Join** between **orders** and **users** on `user_id`
- Merged the result with **restaurants** on `restaurant_id`
- Ensured **100% data retention** (**10,000 order records preserved**)

---

### 🔹 Step 3: Exploratory Data Analysis (EDA)
Analyzed key **business metrics**, including:
- **Total revenue by city**
- **Average Order Value (AOV) by cuisine**
- **Gold vs Regular membership performance**
- **Quarter-wise and seasonal revenue trends**

---

## 📊 Key Insights
- 🏆 **Top Revenue City**: **Chennai** leads in revenue from **Gold members**
- 🌮 **Highest AOV Cuisine**: **Mexican cuisine**
- ⭐ **Membership Impact**: **Gold members contribute ~50% of total orders**
- 📈 **Seasonality Trend**: **Peak revenue in Q3 (July–September)**

---

## 🚀 How to Run the Project

 1️⃣ Clone the Repository
```bash
git clone https://github.com/prasadnikam2005/Food-Delivery-Hackathon
2️⃣ Install Required Libraries
pip install pandas matplotlib seaborn

3️⃣ Project Structure
Food-Delivery-Hackathon/
│
├── orders.csv
├── users.json
├── restaurants.sql
├── hackathon_solution.ipynb
└── README.md

4️⃣ Run the Notebook

Open hackathon_solution.ipynb in Jupyter Notebook and execute all cells.

💼 Business Value

Demonstrates real-world data integration

Combines SQL + Python analytics

Focuses on business-driven insights

Ideal for hackathons, portfolios, and placement interviews

👤 Author

Prasad Nikam
B.Tech CSE (AI & ML)
VIIT Pune
Google Student Ambassador
