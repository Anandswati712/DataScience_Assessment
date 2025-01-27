This repository contains the deliverables for the eCommerce Transactions Analysis and Modeling assignment. The project involves three tasks: Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation using clustering techniques. The dataset consists of three CSV files: Customers.csv, Products.csv, and Transactions.csv, which provide information on customers, products, and transactions respectively.

Dataset Description

1. Customers.csv

CustomerID: Unique identifier for each customer.

CustomerName: Name of the customer.

Region: Continent where the customer resides.

SignupDate: Date when the customer signed up.

2. Products.csv

ProductID: Unique identifier for each product.

ProductName: Name of the product.

Category: Product category.

Price: Product price in USD.

3. Transactions.csv

TransactionID: Unique identifier for each transaction.

CustomerID: ID of the customer who made the transaction.

ProductID: ID of the product sold.

TransactionDate: Date of the transaction.

Quantity: Quantity of the product purchased.

TotalValue: Total value of the transaction.

Price: Price of the product sold.

Tasks

Task 1: Exploratory Data Analysis (EDA) and Business Insights

Perform EDA on the provided dataset.
Derive business insights from the analysis.

Deliverables:

Swati_Anand_EDA.ipynb: Jupyter Notebook containing EDA code.

Swati_Anand_EDA.pdf: PDF report summarizing the insights

Task 2: Lookalike Model

Build a Lookalike Model that recommends 3 similar customers based on their profile and transaction history. The model considers both customer and product information and provides a similarity score for each recommendation.

Deliverables:
Swati_Anand_Lookalike.ipynb: Jupyter Notebook explaining the model development.
Swati_Anand_Lookalike.csv: CSV file mapping customer IDs to the top 3 lookalikes with similarity scores.

Task 3: Customer Segmentation / Clustering

Perform customer segmentation using clustering techniques, leveraging both customer profile and transaction information. Evaluate the clusters using the Davies-Bouldin (DB) Index and visualize the results.

Deliverables:
Swati_Anand_Clustering.ipynb: Jupyter Notebook containing clustering code and visualizations.
Swati_Anand_Clustering.pdf: PDF report summarizing clustering results.

|-- README.md
|-- Data/
|   |-- Customers.csv
|   |-- Products.csv
|   |-- Transactions.csv
|-- EDA/
|   |-- Swati_Anand_EDA.ipynb
|   |-- Swati_Anand_EDA.pdf
|-- LookalikeModel/
|   |-- Swati_Anand_Lookalike.ipynb
|   |-- Swati_Anand_Lookalike.csv
|-- Clustering/
|   |-- Swati_Anand_Clustering.ipynb
|   |-- Swati_Anand_Clustering.pdf
