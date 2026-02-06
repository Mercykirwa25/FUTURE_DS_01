📈 Superstore Sales Performance Analytics
📊 Project Overview

This project analyzes the Superstore Sales Dataset from Kaggle [https://www.kaggle.com/datasets/vivek468/superstore-dataset-final]
 to provide actionable insights into sales, revenue, profit, and regional performance. By combining exploratory data analysis (EDA) in Python with interactive visualizations in Tableau, this project helps businesses understand top-performing products, profitable categories, and growth opportunities to maximize revenue and profitability.

🧠 Business Problem

Businesses often struggle to determine which products, categories, and regions contribute most to revenue and profit, or how sales trends evolve over time. Misaligned efforts and resource allocation can limit growth and profitability.

Project Goals:

Identify products that generate the highest revenue.

Analyze sales trends over time.

Determine the most profitable categories and regions.

Provide data-driven recommendations on where to focus for faster and sustainable growth.

🔉 Stakeholders

Sales and Marketing Teams: Promote top products and drive revenue growth.

Category and Product Managers: Optimize pricing and product portfolio decisions.

Regional Management: Improve sales and profitability in underperforming regions.

Executive Leadership: Make strategic decisions using data-driven insights.

📁 Project Workflow

Business Understanding

Define key business questions and objectives.

Data Understanding

- Explore the dataset structure and key features.

- Validate data quality (no missing values or duplicates).

Data Preparation

- Convert Order Date and Ship Date to datetime.

- Prepare data for visualization and dashboarding.

- Exploratory Data Analysis (EDA) and Insights

  - Revenue by Sub-Category

  - Top Products by Revenue

  - Sales Trend Over Time

  - Profit by Category and Region


Visualization and Dashboarding (Tableau)

KPI cards: Total Sales, Total Profit

Interactive dashboard with filters:

Revenue by Sub-Category (Bar)

Top Products by Revenue (Bar)

Sales Trend by Year (Line)

Profit by Category (Donut)

Profit by Region (Bar)

Business Recommendations

Focus on high-performing products and categories.

Optimize inventory and marketing in profitable regions.

Adjust pricing and discount strategies to improve margins.

⚙️ Tools Used

Languages: Python

Libraries: pandas, numpy

Visualization & Dashboarding: Tableau

Environment: Jupyter Notebook

✅ Key Results

- Top Sub-Categories by Revenue: Furniture and Technology dominate total sales.

- Top Products by Revenue: A few products account for a large share of total revenue.

- Sales Trends: Revenue shows an increasing trend from 2015–2017 with seasonal fluctuations.

- Profit Analysis: Technology category and West region generate the highest profitability.

- Regional Insights: West and East regions outperform others in sales and profit.

🔑 Key Insights

Revenue is concentrated in a small number of high-performing products and sub-categories.

Profitability varies across categories and regions, suggesting the need for targeted strategies.

Seasonal sales trends indicate opportunities for timely marketing campaigns.

Discount strategy should balance revenue growth vs margin erosion.

📝 Final Recommendations

- Focus on High Revenue Products

- Concentrate marketing and inventory investment on top-performing sub-categories.

- Expand High-Profit Categories

- Prioritize Technology and other high-margin categories for growth and sustainability.

- Increase Presence in Profitable Regions

- Expand operations and marketing in the West and East regions.

- Improve Strategy for Low-Profit Categories

- Review pricing, discounts, and supplier costs for low-margin categories.

- Implement targeted promotions for high-demand products.

💻 Getting Started
1. 📦 Clone the Repository
git clone https://github.com/Mercykirwa25/FUTURE_DS_01

2. 🐍 Set Up Python Environment

Make sure Anaconda
 is installed:

conda create -n superstore python=3.11
conda activate superstore

3. 📚 Install Required Packages
pip install pandas numpy

4. 📁 Load the Dataset

Ensure the dataset is in the following structure:

Data/
└── superstore_sales.csv


Load it in Python:

import pandas as pd
data = pd.read_csv("Data/superstore_sales.csv")

5. 📊 Open Tableau

Connect to superstore_sales.csv

Build KPIs, charts, and interactive dashboard following the workflow.

🫱🏽‍🫲🏽 Acknowledgements

Dataset contributors: Superstore Sales Dataset – Kaggle
