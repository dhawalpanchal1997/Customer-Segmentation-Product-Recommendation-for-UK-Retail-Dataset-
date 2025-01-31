# ML Capstone 1 - Part 1: E-Commerce Customer Segmentation

## Project Overview
This project focuses on customer segmentation for an online retail business using transactional data from a UK-based retailer. The dataset, spanning transactions from 2010 to 2011, is analyzed to enhance marketing strategies and boost sales. Using K-Means clustering, we categorize customers into distinct segments and develop a recommendation system for personalized product suggestions.

## Features
- **Data Cleaning & Transformation**: Handle missing values, duplicates, and outliers.
- **Feature Engineering**: Create new customer-centric features.
- **Data Preprocessing**: Perform feature scaling and dimensionality reduction.
- **Customer Segmentation**: Use K-Means clustering for targeted marketing.
- **Cluster Analysis**: Evaluate cluster quality and customer profiles.
- **Recommendation System**: Suggest best-selling products to customers within each segment.

## Technologies Used
- **Python**
- **Pandas, NumPy** (for data manipulation and preprocessing)
- **Matplotlib, Seaborn, Plotly** (for data visualization)
- **Scikit-Learn** (for clustering and machine learning tasks)

## Installation
Ensure Python and necessary dependencies are installed:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

## Dataset
Download the dataset from [here](https://drive.google.com/file/d/1Kyi1Akx299BFhdo77T2MmWg7fLRtMaXm/view?usp=sharing) and save it in your working directory.

## Usage
1. Load and explore the dataset:
```python
import pandas as pd

df = pd.read_csv("ecommerce_data.csv", encoding='cp1252')
print(df.head())
```
2. Clean and preprocess data by handling missing values, duplicates, and outliers.
3. Engineer features and perform exploratory data analysis (EDA).
4. Use K-Means clustering to segment customers.
5. Analyze clusters and generate insights for marketing strategies.
6. Implement a recommendation system to suggest top-selling products.

## Data Flow
1. **Load Data**: Read dataset and explore its structure.
2. **Preprocessing**: Clean and transform the dataset.
3. **Feature Engineering**: Create derived features to enhance analysis.
4. **Clustering**: Apply K-Means clustering for segmentation.
5. **Analysis & Visualization**: Profile customer segments using visualizations.
6. **Recommendation System**: Suggest relevant products to customers.

## Visualizations & Insights
- **Customer purchase behavior**
- **Spending patterns over time**
- **Cluster characteristics and comparisons**
- **Recommendations for increasing sales**

## Future Enhancements
- Integrate a more advanced recommendation system using collaborative filtering.
- Automate real-time data processing and analysis.
- Incorporate deep learning techniques for customer behavior prediction.

## Contribution
Feel free to contribute by forking this repository and submitting pull requests.


