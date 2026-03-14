# Customer Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior to identify patterns in purchasing habits, product preferences, and spending trends.

The analysis combines **Python-based data analysis and visualization with an interactive Power BI dashboard** to extract meaningful business insights.

The goal of this project is to demonstrate an **end-to-end data analytics workflow**, including data cleaning, exploratory data analysis (EDA), visualization, and dashboard reporting.

---

## Problem Statement

Businesses generate large volumes of customer transaction data, but it is often underutilized.

This project aims to analyze customer purchase data to answer important business questions such as:

- What are the customer purchasing trends?
- Which product categories generate higher spending?
- How do discounts affect purchase behavior?
- What are the most common shipping preferences?
- How does customer review rating relate to purchase amounts?

The insights can help businesses **improve marketing strategies, optimize pricing, and understand customer behavior.**

---

## Dataset Description

The dataset used in this project contains customer shopping information.

### Key attributes include:

- Customer demographics  
- Product category  
- Purchase amount  
- Discount applied  
- Shipping type  
- Review ratings  
- Purchase frequency  

This data helps identify patterns in **customer purchases and overall shopping behavior.**

---

## Tools & Technologies Used

### Programming & Data Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn
- Power BI

### Development Environment
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Loaded the dataset using **Pandas**
- Inspected dataset structure
- Verified column types and dataset dimensions

### 2. Data Cleaning
- Handled missing values
- Checked for duplicates
- Corrected inconsistent data types
- Prepared data for analysis

### 3. Exploratory Data Analysis (EDA)

EDA was performed to understand:

- Distribution of purchase amounts
- Customer purchase frequency
- Product category popularity
- Discount impact on sales
- Shipping preferences

### Visualizations used:
- Bar charts
- Histograms
- Distribution plots
- Correlation analysis

### 4. Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize insights from the dataset.

### Dashboard highlights include:

- Customer purchase distribution
- Category-wise spending analysis
- Discount vs non-discount purchase behavior
- Shipping type analysis
- Overall purchase trends

The dashboard allows users to **interactively explore customer data and identify patterns quickly.**

---

## Project Structure

```
customer_behavior_analysis
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── Customer_behaviour_dashboard.pbix
└── README.md
```

---

## File Description

### Customer_Shopping_Behavior_Analysis.ipynb
Contains the full Python workflow including:

- Data preprocessing  
- Exploratory data analysis  
- Data visualization  
- Key insights  

### customer_shopping_behavior.csv
Dataset containing customer purchase data used for analysis.

### Customer_behaviour_dashboard.pbix
Power BI dashboard used to visualize insights interactively.

### README.md
Project documentation.

---

## Key Insights

Some important insights derived from the analysis include:

- Certain product categories contribute significantly to overall purchases.
- Discounts influence customer buying behavior.
- Shipping preferences vary among customers.
- Purchase amount distribution reveals spending patterns.

These insights help businesses **make data-driven decisions and improve customer experience.**

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Riddhi-Patil/customer_behavior_analysis.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run the Jupyter Notebook

Open the notebook:

```
Customer_Shopping_Behavior_Analysis.ipynb
```

Run all cells to reproduce the analysis and visualizations.

### 4. View the Dashboard

Open the file:

```
Customer_behaviour_dashboard.pbix
```

using **Power BI Desktop** to explore the interactive dashboard.

---

## Business Value

This project demonstrates how businesses can:

- Understand **customer purchase patterns**
- Improve **targeted marketing strategies**
- Optimize **discount strategies**
- Analyze **product demand trends**
- Make **data-driven business decisions**
