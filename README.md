# Retail Data Analytics Project

This project focuses on analyzing retail sales data to extract valuable business insights. The dataset used in this analysis was obtained from the [Kaggle Retail Orders Dataset](https://www.kaggle.com/datasets/ankitbansal06/retail-orders). The project includes data cleaning, preparation, and several SQL-based analyses to generate meaningful reports.

## Project Overview
The goal of this project is to analyze retail orders to:
- Identify top-performing products and regions.
- Track month-over-month sales growth between 2022 and 2023.
- Determine the best-performing categories and subcategories.
- Extract insights on sales and profit trends.

## Technologies Used
- **Python:** Data cleaning, preparation, and integration with SQL Server.
- **Pandas:** Data manipulation and preprocessing.
- **SQLAlchemy:** Interaction with Microsoft SQL Server.
- **SQL:** Analytical queries on sales data.
- **Jupyter Notebook:** Development and execution of the project code.

## Data Preprocessing
1. **Dataset Source:** The dataset was sourced from Kaggle and downloaded via the Kaggle API.
2. **Data Cleaning:** Missing values were handled, and unnecessary columns were dropped to simplify the dataset.
3. **Loading Data into SQL Server:** The cleaned dataset was loaded into a Microsoft SQL Server database for further analysis.

## SQL Queries
The SQL script (`SQLQuery1.sql`) includes the following analyses:
1. **Top 10 Highest Revenue-Generating Products:** Identifying products with the highest sales.
2. **Top 5 Highest Selling Products in Each Region:** Ranking products by sales within each region.
3. **Month-Over-Month Sales Growth (2022 vs 2023):** Comparing sales between corresponding months across two years.
4. **Best Performing Month for Each Category:** Identifying the month with the highest sales for each category.
5. **Sub-Category with Highest Growth (2022 vs 2023):** Finding the sub-category with the highest sales growth year-over-year.

## Setup Instructions
1. **Clone the Repository:**
   ```bash
   https://github.com/AdityaDomala/Retail_Data_Analytics_Project.git
2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt

