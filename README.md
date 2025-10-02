# 🛒 Olist E-commerce Dashboard (Python + Tableau)

This project showcases an end-to-end data engineering workflow using the Brazilian Olist e-commerce dataset.

## 🗂️ Dataset

This project uses the **Brazilian Olist E‑commerce Dataset**, a publicly available dataset widely used for data analytics and engineering case studies. It contains real e‑commerce transaction data from **2016–2018** for multiple marketplaces in Brazil.  

The dataset includes **100k+ orders** from **3k+ sellers** across dozens of product categories, with information on:

- Orders – purchase timestamps, approval, shipping, and delivery dates  
- Customers – unique customers and their locations (state-level data)  
- Order Items – products ordered, sellers, prices, freight costs  
- Payments – payment methods, installment plans, and payment values  
- Reviews – customer review scores and comments  
- Products & Sellers – product metadata and seller details  
- Geolocation – ZIP code-level location data  
- Category Translations – Portuguese-to-English product category names  

📥 [Download Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 📦 Project Structure

- **Python ETL Pipeline**: Cleaned & merged orders, payments, reviews, and product data
- **Feature Engineering**: Delivery delays, shipping duration, review scores
- **Dashboard**: Built in Tableau Public with KPIs, histograms, scatter plots

## 📊 Tableau Dashboard

🔗 [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/aditya.ravindra.chitnis/viz/OlistE-commerceDashboardSalesShippingSatisfaction/E-commerceFunnelDashboard?publish=yes) 

<img width="1920" height="908" alt="image" src="https://github.com/user-attachments/assets/cb6e2f42-a065-4165-9b90-72451798b3ee" />

## 📁 Files

- `olist_etl_pipeline.ipynb` – Jupyter notebook (ETL & feature creation)
- `output/olist_cleaned_for_tableau.csv` – Dataset used in Tableau
- `README.md` – Overview of the project

## 🛠 Tools Used

- Python (Pandas)
- Jupyter Notebook
- Tableau Public
- Git & GitHub
