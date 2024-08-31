# 📱 Smartphone Market Insights Analysis

## 📝 Project Description

This project, **"Smartphone Market Insights Analysis,"** is aimed at delivering a comprehensive analysis of the smartphone market using SQL queries. The analysis covers a wide range of factors, including prices, features, user ratings, and technical specifications of different smartphone models. The project leverages a detailed dataset that includes information about each smartphone's price, battery life, camera quality, processor type, and other relevant attributes.

---

## 💻 Technologies Used

- **SQL**: For querying the dataset to extract valuable insights.
- **Python**: For connecting to the SQL database using `mysql.connector` and performing further analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.

---

## 🎯 Goals of the Project

1. **Categorize Smartphones by Price Range**: Identify and analyze the distribution of smartphones across different price segments.
2. **Average User Ratings by Brand**: Calculate and compare the average user ratings for various smartphone brands to determine customer satisfaction.
3. **Processor Type Evaluation**: Assess user ratings based on different processor types to understand performance preferences.
4. **Price and Memory Card Support Analysis**: Examine the relationship between smartphone prices and the availability of memory card support.
5. **Battery Capacity and Processor Speed Analysis**: Analyze average ratings and prices based on different processor speed ranges.
6. **Top Budget-Friendly Models**: Identify top-rated, affordable smartphone models for budget-conscious consumers.
7. **Market Share Analysis**: Evaluate the market share of different smartphone brands.
8. **Display Resolution Distribution**: Analyze the distribution of smartphone display resolutions in the market.
9. **Camera Megapixel Trends**: Track the evolution of camera megapixel trends over time.
10. **Memory Card Support Comparison**: Compare memory card support across various brands.
11. **Camera Setup Analysis**: Analyze the impact of different camera setups on smartphone prices and ratings.
12. **High Ratings and Low Price Models**: Identify smartphone models that offer high user ratings at relatively low prices.

This analysis provides valuable insights to consumers for making informed purchasing decisions and helps manufacturers understand market trends and consumer preferences to develop better products.

---

## 📂 Table of Contents

1. **Categorize Smartphones by Price Range**
2. **Average User Ratings by Brand**
3. **Processor Type Evaluation**
4. **Price and Memory Card Support Analysis**
5. **Battery Capacity and Processor Speed Analysis**
6. **Top 5 Budget-Friendly Models**
7. **Market Share Analysis by Brand**
8. **Distribution of Display Resolutions**
9. **Evolution of Camera Megapixel Trends**
10. **Memory Card Support Comparison Across Brands**
11. **Camera Setup and Price Analysis**
12. **High Ratings and Low Price Models**

---

## 🛠️ Project Setup and Implementation

### 1. **Importing Libraries**

```python
import pandas as pd
import numpy as np
import warnings
warnings.filterwarnings('ignore')
import matplotlib.pyplot as plt
import seaborn as sns
```

## 2. **Use SQL Connector in the Project**

In this project, we use an SQL connector to interact with our database. The SQL connector allows us to establish a connection between our Python scripts and the database, execute SQL queries, and fetch results for analysis. This helps us efficiently retrieve and manipulate the data needed for our analysis of the smartphone market.

```python
import mysql.connector

mydb = mysql.connector.connect(
  host="localhost",
  user="root",
  password="**********",
  database="project_02"
)

mydb
```

## 3. Show All Tables in the Database

```python
df = pd.read_sql_query(
    """
    SHOW TABLES
    """, mydb)
df
```

## 4. Describe the 'smartphone' Table

```python
df = pd.read_sql_query(
    """
    DESCRIBE smartphone
    """, mydb)
df
```
---

## 🎨 Contributions

In this project, I:

- Developed SQL queries to analyze the smartphone dataset.
- Connected to the SQL database using Python's `mysql.connector`.
- Utilized Pandas for data manipulation and cleaning.
- Created data visualizations using Matplotlib and Seaborn to present insights.
- Conducted thorough analysis to draw meaningful conclusions about the smartphone market.
- Documented findings and presented them in a clear and organized manner.

---

## 📂 Project Resources

- **Smartphone Dataset**: The dataset used in this analysis in CSV format.

---

## 🚀 See More Projects

- [SQL Projects](#)
- [Data Analysis Projects](#)

---

## 🧑‍💻 Project Development and Author Information

- **Developed By**: Bhushan Gawali
- **Role**: Data Analyst

---

## 📞 Contact Information

- [LinkedIn Profile](#)
- [GitHub Profile](#)
- **Email**: example@example.com
- [WhatsApp](#): Contact via WhatsApp
- [Instagram Profile](#)
- [Facebook Profile](#)
- [Google Maps Location](#)
- [Resume](#)

---

## 🗓️ Date

25/06/2024

---

## 📢 Project Summary

This project was developed by Bhushan Gawali. Leveraging expertise in data analysis and visualization, I utilized MySQL for data extraction and Python libraries such as Pandas, Matplotlib, and Seaborn to analyze and visualize the smartphone market data. The project aims to provide valuable insights into smartphone prices, features, and user ratings, helping consumers make informed purchasing decisions and aiding manufacturers in product development.



