# US Business Formation Analysis

**business_formation_trends.ipynb**: An exploratory data analysis of new business formation trends in the United States, focusing on patterns across time and regions.

**predict_business_formations.ipynb**: A notebook that builds and evaluates machine learning models to predict the number of new business applications using historical data.

**modeling_utils.py**: A Python script containing helper functions for preprocessing and training scikit-learn models used in the prediction notebook.

# Business Applications Prediction Model

## Project Motivation
This project aims to predict the number of business applications in the US using historical data. Understanding these patterns helps government agencies allocate resources and provides economic insights.

## Libraries Used
- pandas: Data manipulation
- numpy: Numerical operations
- scikit-learn: Machine learning models
- matplotlib/seaborn: Visualization

## Repository Contents
- `Business_Applications_Model.ipynb`: Jupyter notebook with full analysis
- `output.csv`: Dataset containing business applications data
- `README.md`: This file
- Images folder: Contains visualizations from the analysis

## Summary of Results
- The linear regression model achieved 74.5% accuracy (R²) on test data
- Strong seasonal patterns exist in business applications:
  - March, January, and August show the highest positive impact
  - April and February show significant negative impact
- There's an upward trend of approximately 7,000 more applications per year
- Previous month's applications have a moderate influence on current month

## Acknowledgments
- Data provided by [source of your data]
- Project completed as part of the Udacity Data Science Nanodegree

---

**Data Source**: [US Census Bureau – Business Formation Statistics](https://www.census.gov/econ/bfs/)

This project is part of the Udacity Data Scientist Nanodegree.


## Medium Blog Post
As part of this project, I also wrote a blog post that walks through the full data science process — from exploration to modeling and insights. In the post, I highlight key findings, explain my modeling approach, and reflect on what the data tells us about entrepreneurship trends in the U.S.

 [Decoding America’s Entrepreneurial Pulse](https://medium.com/@tianyizhang0092/decoding-americas-entrepreneurial-pulse-what-business-application-data-reveals-about-our-economic-e839d4edf8fc)

Feel free to check it out for a more narrative and visual explanation of the project!