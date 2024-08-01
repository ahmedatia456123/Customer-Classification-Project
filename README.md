[Original works](https://www.kaggle.com/code/fabiendaniel/customer-segmentation) I just edited it and improved model performance
# Customer Classification Project

## Overview

This project focuses on classifying customers based on their purchasing behaviors. By analyzing the transaction data, we categorize customers into distinct groups to better understand their preferences and improve targeted marketing strategies. The classification is performed using various machine learning algorithms implemented in Python, specifically utilizing the scikit-learn library.

## Project Structure

### 1. Data Analysis
We start by examining the dataset, which includes transaction details over a period of 10 months. The analysis involves:
- Descriptive statistics of the dataset
- Visualization of customer purchase patterns
- Identification of key attributes for classification

### 2. Product Classification
To simplify the customer classification, products are first grouped into five main categories. This categorization helps in understanding which types of products are most commonly purchased together.

### 3. Customer Segmentation
Customers are segmented into eight categories based on:
- Types of products they buy
- Number of visits
- Total amount spent

The segmentation provides insights into different customer profiles and their shopping behaviors.

### 4. Classifier Implementation
Several classifiers are trained to categorize customers from their first purchase. The classifiers tested include:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines

A custom class is created to streamline the training and evaluation process of these classifiers.

### 5. Model Evaluation
The performance of the classifiers is evaluated using a test set comprising the last two months of data. The metrics used for evaluation include accuracy, precision, and recall. Our best model achieved an accuracy of 95%, correctly classifying customers into their respective segments.

## Key Features

- **Product Categorization**: Grouping products into major categories for simplified analysis.
- **Customer Segmentation**: Clustering customers based on spending habits and product preferences.
- **Machine Learning Models**: Implementation and comparison of various classifiers to predict customer categories.
- **Visualization**: Use of radar charts and other visual tools to present classification results.

## Technical Stack

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Jupyter Notebook**: For interactive data analysis and visualization

## Conclusion

This project demonstrates the ability to handle large datasets, perform complex data analysis, and apply machine learning techniques to solve real-world business problems. The classification model can significantly enhance targeted marketing efforts by accurately predicting customer categories from their initial purchase.
