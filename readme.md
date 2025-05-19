# Brazil E-commerce Data Analysis Project

## Project Overview

This project analyzes the Olist Brazilian E-commerce Public Dataset to extract business insights and support decision-making. The workflow covers data preparation, cleaning, merging, exploratory analysis, machine learning, and dashboarding.

## Dataset

* Dataset: [Brazilian E-commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
* Time Period: 2016 - 2018
* Total Orders: +-100,000 orders
* Data Includes: Order information, customer information, payment details, product details, and seller information.

## Power BI Dashboard

* Most of the detailed analysis is available in the Jupyter notebooks. For a summary of the main findings and interactive visualizations, please see the Power BI dashboard [click to access](https://app.powerbi.com/view?r=eyJrIjoiNWQ5ZDlmZGYtMGJiNC00YmM1LTliYWItN2FkZGRjYzg5ODEwIiwidCI6IjFiYzVlY2E4LTEzNjAtNDhhMy05NWRiLTM5ZmRmNDRiMWEzNiJ9).

## Project Structure

```
├── 01_data_preparation_and_merge.ipynb
├── 02_analysis_and_modeling.ipynb
├── data/
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
|     └── processed_dataset/
|         └── merged_data_clean.csv
|         └── merged_data.csv
├── dashboard_files/
│   └── EcommerceDashboard.pbix
├── requirements.txt
```

## Project Tasks

### 1. Data Preparation

* Data Import
* Data Cleaning
* Data Standarization
* Relational Model Creation SQLite Database
* Exeport Celan Dataset

### 2. Exploratory Data Analysis

* Monthly Order Volume Analysis
* Delivery Time Distribution
* Freight vs. Distance Analysis
* Top Product Categories by Revenue
* Average Order Value by State

### 3. Business Problem Solving

* Customer Retention Analysis
* Delay Prediction Model
* Customer Segmentation
* Customer Satisfaction Analysis

### 4. Data Visualization and Dashboarding with Power BI

* Sales Dashboard
* Heatmap of Sales Concentration by Region
* Customer Satisfaction Analysis
* Seller Performance Dashboard

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/adlerabf/brazil-ecommerce-analysis.git
   cd brazil-ecommerce-analysis
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute the notebooks in the following order:

   * Data Preparation
   * Exploratory Data Analysis
   * Business Problem Solving
   * Data Visualization and Dashboarding

## Technologies Used

* Python (Pandas, NumPy, Sqlite3, Matplotlib, Plotly, Scikit-learn)
* SQLite Database
* Jupyter Notebook
* Power BI
