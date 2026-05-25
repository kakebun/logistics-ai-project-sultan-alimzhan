# AI-Driven Smart Logistics & Supply Chain Intelligence System

## Project Description

This project is a final exam project for the course **AI for Logistics & Supply Chains**.

The main goal of this project is to build an AI-driven logistics and supply chain intelligence system using **Python, machine learning, and Power BI**. The system helps analyze demand, delivery performance, inventory levels, supplier performance, transportation efficiency, and supply chain risks.

The project includes data cleaning, exploratory data analysis, demand forecasting, delivery delay prediction, inventory optimization, supplier analytics, and Power BI dashboard development.

## Group Members

- Sultan Mykhtybayev
- Alimzhan Tursynov

## Dataset

**Dataset Name:** Supply Chain Analysis Dataset  
**Source:** Kaggle  
**Dataset Link:** https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis

The dataset includes supply chain information such as:

- Product type
- SKU
- Price
- Availability
- Number of products sold
- Revenue generated
- Stock levels
- Lead times
- Order quantities
- Shipping times
- Shipping costs
- Supplier name
- Location
- Transportation modes
- Routes
- Manufacturing costs
- Defect rates

## Tools and Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Power BI
- GitHub

## Machine Learning Models Used

The project uses several machine learning and analytical methods:

### 1. Demand Forecasting

We used regression models to predict future product demand.

Models used:

- Linear Regression
- Random Forest Regressor

The target variable was **Number of products sold**.  
The model helped estimate future demand and future inventory requirements.

### 2. Delivery Delay Prediction

We used classification models to predict whether a delivery may be delayed.

Models used:

- Logistic Regression
- Random Forest Classifier

The output includes delay prediction, delay probability, and feature importance.

### 3. Inventory Optimization

We used:

- ABC Analysis
- K-Means Clustering

ABC Analysis was used to classify products by revenue importance.  
K-Means Clustering was used to group products based on inventory and demand patterns.

### 4. Supplier and Transportation Analytics

We analyzed supplier reliability, lead time, defect rate, transportation modes, shipping costs, route bottlenecks, and supply chain risk.

## Repository Structure

```text
logistics-ai-project-sultan-alimzhan/
│
├── data/
│   ├── supply_chain_data.csv
│   ├── cleaned_supply_chain_data.csv
│   ├── powerbi_main_dataset.csv
│   └── logistics_powerbi_export.xlsx
│
├── notebook/
│   └── logistics_final_exam_Sultan_&_Alimzhan.ipynb
│
├── dashboard/
│   ├── page1_executive_dashboard.png
│   ├── page2_demand_forecasting.png
│   ├── page3_logistics_transportation.png
│   ├── page4_inventory_intelligence.png
│   ├── page5_supplier_analytics.png
│   ├── page6_ai_insights.png
│   ├── page7_risk_sustainability.png
│   └── page8_strategic_recommendations.png
│
├── presentation/
│   └── Logistics_Final_presentation.pdf
│
├── report/
│   └── final_report_text.txt
│
└── README.md
