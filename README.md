# Zeotap Assignment

## Overview
This project involves customer data analysis and segmentation using clustering techniques. It is divided into three main tasks: **Exploratory Data Analysis (EDA)**, **Lookalike Model** creation, and **Customer Segmentation** using clustering algorithms. The objective is to derive business insights from the data, build a recommendation system, and segment customers for targeted marketing or analysis.

## Tasks Breakdown

### Task 1: **Exploratory Data Analysis (EDA) and Business Insights**
   - **Objective**: Perform exploratory data analysis (EDA) on the customer and transaction data.
   - **Business Insights**: 
     - Derive at least 5 business insights based on the EDA.
   - **Deliverables**:
     - Jupyter Notebook/Python script containing the EDA code.
     - PDF report summarizing the business insights.

### Task 2: **Lookalike Model**
   - **Objective**: Build a Lookalike Model that recommends 3 similar customers based on their profile and transaction history.
   - **Features**:
     - Use both customer and product information to recommend similar customers.
     - Calculate a similarity score for each recommendation.
   - **Deliverables**:
     - A CSV file containing the recommendations for the first 20 customers.
     - Jupyter Notebook/Python script explaining the model development.

### Task 3: **Customer Segmentation / Clustering**
   - **Objective**: Segment customers using clustering techniques on both demographic and transaction data.
   - **Clustering Algorithms**:
     - Flexibility to choose between KMeans, DBSCAN, Hierarchical Clustering, etc.
   - **Metrics**: 
     - Calculate the **Davies-Bouldin Index (DBI)** to evaluate clustering performance.
   - **Deliverables**:
     - A report on clustering results, including the number of clusters and DB Index.
     - Jupyter Notebook/Python script with the clustering code and visualizations.

## Requirements

To run this project, the following Python libraries are required:

- pandas
- numpy
- scikit-learn
- scipy
- matplotlib

To install the required libraries, run the following command:

```bash
pip install -r requirements.txt
