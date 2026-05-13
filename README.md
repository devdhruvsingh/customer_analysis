# Customer Shopping Behavior Analysis

An end-to-end data analytics project focused on cleaning, processing, and visualizing customer transaction data to uncover actionable business insights.

## 🚀 Project Overview
This project analyzes a dataset of 3,900 customer records to understand purchasing patterns, loyalty segments, and the impact of discounts on customer satisfaction. The workflow moves from raw data cleaning in Python to structured storage in PostgreSQL and final visualization in Tableau.

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, NumPy), SQL
- **Database:** PostgreSQL (SQLAlchemy as the bridge)
- **Visualization:** Tableau Public, Seaborn/Matplotlib
- **Tools:** VS Code, Git/GitHub

## 📋 Key Features & Analysis
- **Data Preprocessing:** Handled missing values, normalized column names, and engineered new features like `age_group` and `purchase_frequency_days`.
- **Customer Segmentation:** Created a SQL View to categorize customers into 'NEW', 'RETURNING', and 'LOYAL' based on purchase history.
- **Discount Impact:** Analyzed whether discounted purchases correlate with higher review ratings.
- **Seasonal Trends:** Identified peak purchasing categories for each season to optimize inventory strategy.
- **Database Integration:** Automated the transfer of cleaned DataFrames into a PostgreSQL relational database.

## 📊 Visualizations
The Tableau Dashboard includes:
1. **Sales Performance:** Revenue breakdown by Category and Gender.
2. **Geographic Heatmap:** Total spending mapped across US states.
3. **Pareto Analysis:** Identifying the top 20% of products driving 80% of revenue.
4. **Subscription Value:** Comparing spending habits of subscribers vs. non-subscribers.

## 📁 Repository Structure
- `customer_shopping_analysis.ipynb`: Main Jupyter notebook with data cleaning and EDA.
- `customer_shopping_behavior_cleaned.csv`: The processed dataset.
- `.gitignore`: Ensures environment files (`venv/`) are not uploaded.
- `README.md`: Project documentation.

## ⚙️ How to Run
1. **Clone the repo:** `git clone <repo-url>`
2. **Install dependencies:** `pip install pandas sqlalchemy psycopg2-binary openpyxl`
3. **Setup Database:** Ensure PostgreSQL is running and update the connection string in the notebook with your credentials.
4. **Tableau:** Connect Tableau to the exported CSV or the PostgreSQL server.

---
