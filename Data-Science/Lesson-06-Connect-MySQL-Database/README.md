# Lesson 06 – Connect MySQL Database

## Project Overview
This project demonstrates connecting a MySQL database to Python and performing automobile data analysis using Pandas, NumPy, Matplotlib, and Seaborn.

## Dataset
- **Name:** Automobile Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/10/automobile)
- **Records:** 205
- **Attributes:** 26
- **Database:** MySQL
- **Database name:** automobile_db
- **Table:** automobile_raw

## Tools and Technologies
- Python
- MySQL and MySQL Workbench
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- mysql-connector-python

## Project Steps
1. Created a MySQL database named automobile_db.
2. Created the automobile_raw table.
3. Imported the automobile dataset into MySQL.
4. Connected MySQL to Python.
5. Retrieved 205 records using Pandas.
6. Cleaned missing values and converted numeric columns.
7. Created visualizations to analyze automobile prices.
8. Generated key findings and exported the cleaned dataset.

## Visualizations
1. Top 10 Car Manufacturers by Average Price – Bar Chart.
2. Engine Size vs Automobile Price – Scatter Plot.

## Key Findings
- The dataset contains 205 automobile records.
- It includes 22 different manufacturers.
- Jaguar has the highest average automobile price at 34,600.
- Engine size and automobile price have a correlation of 0.87, indicating a strong positive relationship.

## Conclusion
The project demonstrates how Python can connect to MySQL, retrieve and clean data, perform analysis, and create visualizations. The results indicate that automobiles with larger engine sizes generally tend to have higher prices in this dataset.

## Project Files
- `Automobile_Database_Analysis.ipynb` – Python analysis notebook.
- `cleaned_automobile_data.csv` – Cleaned automobile dataset.
- `README.md` – Project documentation.