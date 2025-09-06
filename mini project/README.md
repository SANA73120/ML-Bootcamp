# 📊 Sales Data - Exploratory Data Analysis (EDA)

### 🔎 Project Motivation

Sales data holds valuable insights that can help businesses increase revenue, optimize inventory, and improve customer satisfaction.
The purpose of this project is to explore the sales dataset and answer real-world business questions through data analysis and visualization.<br>
By applying Exploratory Data Analysis (EDA) techniques, we:

- Identify best month for sales
- Find the most profitable regions
- Determine hourly sales patterns
- Identify the best-selling products
<hr>

### 📌 Objectives

1. The key objectives of this project are:
2. Data Cleaning & Preprocessing – Handling missing values, correcting datatypes, and removing duplicates.
3. Descriptive Analysis – Exploring dataset structure and computing summary statistics.
4. Visualization – Creating meaningful charts to spot trends, correlations, and outliers.
5. Insight Generation – Answering specific business questions using data.
<hr>

### 🗂️ Dataset Details
The dataset used (sales_data.csv) contains transactional sales information. Key columns include:

| Column Name          | Description                                   |
| -------------------- | --------------------------------------------- |
| **Order ID**         | Unique identifier for each order              |
| **Order Date**       | Date and time of the purchase                 |
| **Product**          | Name of the purchased product                 |
| **Quantity Ordered** | Number of units bought                        |
| **Price Each**       | Price per unit                                |
| **Purchase Address** | Customer’s address (helps extract City/State) |

<hr>

### 🧩 EDA Workflow

1. Data Cleaning
    - Removed missing values & duplicates
    - Converted date columns to datetime format
    - Extracted Month, Hour, and City from raw data

2. Exploratory Analysis
    - Distribution of sales across months & hours
    - Product-wise quantity vs. revenue
    - Sales contribution by region/city
    - Correlation between price and demand

3. Data Visualization
    - Line plots for monthly sales trend
    - Bar charts for top products and revenue by city

<hr>

### 📷 Example Visualizations

#### Sales by Hour
<img width="592" height="429" alt="Capture" src="https://github.com/user-attachments/assets/b1b6e5cc-e124-4257-952a-25d20c45c8a3" />

#### Revenue by Product
<img width="568" height="622" alt="Screenshot (135)" src="https://github.com/user-attachments/assets/16cd685a-860c-404f-bb33-7800e6867fff" />

<hr>

### 📈 Key Insights
**✔️ Peak Sales Month** – December showed the highest sales due to holiday shopping.<br>
**✔️ Best Sales Hours** – Orders peaked around 7 PM – 9 PM, indicating after-work purchases.<br>
**✔️ Top Products** – Headphones and laptops generated the most revenue.<br>
**✔️ Regional Sales** – Major cities like San Francisco and Los Angeles contributed significantly to revenue.<br>
**✔️ Price vs Demand** – Cheaper products sold in higher quantities, while expensive items had lower demand but higher profit per unit.

