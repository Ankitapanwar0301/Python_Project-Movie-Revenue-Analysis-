# Python_Project-Movie-Revenue-Analysis-
Movie Revenue Analysis
Project Overview

This project focuses on analyzing movie industry data to understand the key factors influencing box office revenue. The analysis explores relationships between budget, gross earnings, genre, company, and other variables using Python and data visualization techniques.

Objectives
To analyze the relationship between movie budget and gross revenue
To identify highly profitable movies
To explore trends based on genre, year, and production companies
To determine key factors that impact movie success

Tools & Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

Dataset

The dataset contains information about movies including:
Name
Budget
Gross Earnings
Genre
Director
Star Cast
Votes
Runtime
Company
Year

Key Steps Performed
1. Data Cleaning
Checked and handled missing values
Removed duplicates
Ensured relevant columns (budget & gross) are clean
2. Exploratory Data Analysis (EDA)
Used .head(), .shape(), .dtypes() for understanding data
Identified distributions and trends
3. Correlation Analysis
Generated correlation matrix
Used heatmap to visualize relationships
Found strong correlation between budget and gross revenue
4. Feature Engineering
Created a new column:
Profit = Gross - Budget
5. Data Visualization
Scatter plots (Budget vs Gross)
Regression plots
Bar charts (Top movies)
Histograms (Budget, Gross, Profit)
6. Group-Based Analysis
Year-wise revenue trends
Genre-wise performance
Company-wise earnings
Top actors and directors

Key Insights
Movies with higher budgets tend to generate higher revenue
Certain genres consistently perform better
Top production companies dominate box office earnings
Profitability varies significantly across movies
Popularity (votes) shows some relationship with revenue

Project Structure
Movie_Revenue_Analysis.ipynb → Main analysis notebook
movies.csv → Raw dataset
cleaned_movies.csv → Processed dataset


Future Improvements
Add advanced statistical analysis
Build predictive models (Machine Learning)
Create interactive dashboards (Power BI / Tableau)

Conclusion
This project highlights how data analysis can uncover meaningful insights in the movie industry and support better decision-making.
