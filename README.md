# Synent-Technology-Task6-Superstore-Data-Visualization
## Overview

This project focuses on customer segmentation using the Mall Customer Dataset. The primary objective is to group customers based on their purchasing behavior and annual income using the K-Means Clustering algorithm.

Customer segmentation helps businesses understand different customer groups and create targeted marketing strategies to improve customer satisfaction, retention, and revenue.

---

## Project Objective

The objective of this project is to analyze customer behavior and identify distinct customer segments using machine learning techniques.

### Tasks Performed

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Selection
* Data Scaling using StandardScaler
* Determining Optimal Clusters using the Elbow Method
* Applying K-Means Clustering
* Visualizing Customer Segments
* Generating Business Insights

---

## Dataset Information

### Dataset

Mall Customer Dataset

### Features

| Feature                | Description                       |
| ---------------------- | --------------------------------- |
| CustomerID             | Unique customer identifier        |
| Gender                 | Customer gender                   |
| Age                    | Customer age                      |
| Annual Income (k$)     | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending behavior score  |

### Dataset Size

* Total Records: 200
* Total Features: 5

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Project Workflow

### 1. Data Loading

The dataset was loaded into a Jupyter Notebook environment using Pandas.

### 2. Data Preprocessing

* Checked for missing values
* Verified data types
* Selected relevant features
* Scaled numerical data using StandardScaler

### 3. Finding Optimal Clusters

The Elbow Method was used to determine the optimal number of clusters by analyzing Within-Cluster Sum of Squares (WCSS).

### 4. K-Means Clustering

The K-Means algorithm was applied to group customers based on:

* Annual Income (k$)
* Spending Score (1-100)

### 5. Cluster Visualization

Customer groups were visualized using scatter plots, where each cluster represented customers with similar purchasing behavior.

---

## Customer Segments Identified

### Cluster 1 – Premium Customers

Characteristics:

* High Income
* High Spending

Business Strategy:

* Loyalty programs
* Premium memberships
* Exclusive offers

---

### Cluster 2 – Potential Customers

Characteristics:

* High Income
* Low Spending

Business Strategy:

* Personalized promotions
* Targeted advertising
* Product recommendations

---

### Cluster 3 – Budget Shoppers

Characteristics:

* Low Income
* Low Spending

Business Strategy:

* Discount campaigns
* Value-focused products

---

### Cluster 4 – Impulsive Buyers

Characteristics:

* Low Income
* High Spending

Business Strategy:

* Limited-time offers
* Retention campaigns

---

### Cluster 5 – Average Customers

Characteristics:

* Moderate Income
* Moderate Spending

Business Strategy:

* General marketing campaigns
* Customer engagement programs

---

## Key Insights

* Customer behavior varies significantly across different income levels.
* High-income customers do not always spend more.
* Distinct customer groups can be targeted with customized marketing strategies.
* Segmentation enables businesses to improve customer retention and maximize revenue.
* Data-driven marketing can significantly improve business performance.

---

## Business Recommendations

### Recommendation 1

Focus on retaining premium customers through loyalty rewards and exclusive benefits.

### Recommendation 2

Encourage high-income low-spending customers to increase purchases through personalized campaigns.

### Recommendation 3

Design separate marketing strategies for each customer segment.

### Recommendation 4

Monitor customer behavior regularly to update segmentation models.

### Recommendation 5

Use customer segmentation insights for targeted promotions and product placement.

---

## Results

The project successfully grouped customers into meaningful segments using K-Means Clustering. The generated customer profiles provide valuable insights for marketing, sales, and customer relationship management.

The segmentation model helps businesses better understand their customers and make informed strategic decisions.

---

## Repository Structure

```text
├── Mall_Customers.csv
├── Customer_Segmentation_Pro_Internship_Project.ipynb
├── Customer_Segmentation_Report.pdf
├── README.md
```

---

## Learning Outcomes

Through this project, the following skills were developed:

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Machine Learning
* K-Means Clustering
* Customer Analytics
* Business Intelligence

---

## Author

**Aksh Daraniya**

Computer Engineering Student

Internship Project – Customer Segmentation using Machine Learning

---

⭐ If you found this project useful, consider giving the repository a star.
