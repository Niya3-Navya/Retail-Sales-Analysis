 


🛒 Retail-Sales-Analysis
A comprehensive data analysis project on a retail superstore dataset — covering exploratory data analysis, profit/loss insights, sales trend forecasting, and an interactive dashboard built in Python.

Retail sales analysis using SQL + Python + Pandas |  Business Intelligence Dashboard | Superstore Dataset | 


📌 Project Overview
This project dives deep into a superstore's transactional data to uncover what's driving sales, where profits are bleeding, and how performance varies across regions, categories, and time. The goal: turn raw retail data into actionable business intelligence.

📂 Dataset

Source: Sample Superstore Dataset (Kaggle Public)
Records: ~10,000 orders
Features: Order Date, Ship Mode, Customer Segment, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit


🔍 What's Inside
1. Exploratory Data Analysis (EDA)

Distribution of sales, profit, and discount across categories and regions
Correlation analysis between discount rates and profit margins
Identification of top and bottom performing sub-categories
Customer segment breakdown (Consumer, Corporate, Home Office)

2. Profit & Loss Analysis

Sub-categories with consistent negative profit (e.g., Tables, Bookcases)
Impact of high discounting on profit erosion
Regional profitability comparison — West vs East vs Central vs South
Profit margin heatmaps by category × region

3. Sales Forecasting

Time-series decomposition of monthly sales trends
Forecasting future sales using statistical modelling
Seasonality patterns and year-over-year growth analysis

4. Dashboard

Interactive visual dashboard built in Python (Matplotlib / Seaborn / Plotly)
KPI summary: Total Sales, Total Profit, Avg. Discount, Order Count
Filterable views by Region, Category, and Segment


🛠️ Tech Stack
ToolPurposePython 3.xCore languagePandasData wranglingNumPyNumerical operationsMatplotlib & SeabornStatic visualizationsPlotlyInteractive chartsStatsmodelsTime-series forecastingJupyter NotebookAnalysis environment

📊 Key Findings

Technology is the most profitable category; Furniture consistently underperforms
Tables and Bookcases operate at a net loss — high discounts are the primary culprit
The West region leads in both sales and profitability
Consumer segment accounts for ~50% of total revenue
Discount rates above 20% almost always result in negative profit margins
Sales show clear seasonality, peaking in Q4 (October–December)


📁 Project Structure
Retail-Sales-Analysis/
│
│── superstore.csv
│── Superstore_Sales_Analysis.ipynb
├── dashboard.png
└── README.md

🚀 Getting Started
1. Clone the repository
bashgit clone https://github.com/Niya3-Navya/superstore-sales-analysis.git
cd superstore-sales-analysis
2. Install dependencies
pip install pandas numpy matplotlib seaborn plotly statsmodels jupyter
3. Run the notebooks
Open Jupyter and run notebooks in order (01 → 04).
bashjupyter notebook

📈 Sample Visualizations

Sales vs Profit scatter by Sub-Category · Regional Profit Heatmap · Monthly Sales Forecast · Discount vs Profit correlation

(See /visuals folder or run the notebooks to generate all plots)

🙋‍♀️ Author
Niyati
Final Year Student | Data Science & Analytics Enthusiast

Dashboard
<img width="2685" height="1477" alt="dashboard" src="https://github.com/user-attachments/assets/2e6c1926-59b6-4062-aad2-21d3455ca2af" />


📄 License
This project is open-source and available under the MIT License.
