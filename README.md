🍔📊 Food Delivery Data Analysis Hackathon
📌 Project Overview

This project was built as part of a Data Analysis Hackathon to simulate a real-world data engineering + analytics workflow.
Multiple datasets in different formats were integrated, cleaned, and analyzed to extract actionable business insights for a food delivery platform.

📁 Dataset Description

The project uses three heterogeneous data sources:

orders.csv
Transaction-level data

order_id

user_id

restaurant_id

order_date

total_amount

users.json
User master data

user_id

name

city

membership_type (Gold / Regular)

restaurants.sql
Restaurant master data

restaurant_id

cuisine

rating

🛠️ Tech Stack

Language: Python 3.x

Libraries:

Pandas – data manipulation

SQLite3 – SQL-based data extraction

Matplotlib / Seaborn – data visualization

Environment: Jupyter Notebook

⚙️ Implementation Workflow
1️⃣ Data Loading & Extraction

Loaded CSV files using Pandas

Parsed structured JSON into DataFrames

Executed SQL script using in-memory SQLite to extract restaurant data

2️⃣ Data Integration

Left Join: orders ⟵ users on user_id

Left Join: merged result ⟵ restaurants on restaurant_id

Preserved all 10,000 order records to avoid data loss

3️⃣ Exploratory Data Analysis (EDA)

Key business metrics analyzed:

Total revenue by city

Average Order Value (AOV) by cuisine

Gold vs Regular member performance

Quarterly and seasonal revenue trends

📊 Key Insights

Top Revenue City: Chennai (Gold members dominate revenue)

Best Performing Cuisine: Mexican cuisine has the highest AOV

Membership Impact: Gold members contribute ~50% of total orders

Seasonality: Revenue peaks in Q3 (July–September)

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https:https://github.com/prasadnikam2005/Food-Delivery-Hackathon
cd Food-Delivery-Hackathon

2️⃣ Install dependencies
pip install pandas matplotlib seaborn

3️⃣ Project structure
Food-Delivery-Hackathon/
│
├── orders.csv
├── users.json
├── restaurants.sql
├── hackathon_solution.ipynb
└── README.md

4️⃣ Run the notebook

Open hackathon_solution.ipynb in Jupyter Notebook and execute all cells.

📌 Business Value

Demonstrates real-world data integration

Combines SQL + Python analytics

Shows clear business-driven insights

Hackathon-ready and placement-friendly project

👤 Author

Prasad Nikam
B.Tech CSE (AI & ML) | VIIT Pune
Google Student Ambassador
