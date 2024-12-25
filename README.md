# Ecommerce Sales Prediction

This repository contains Python code and Jupyter Notebooks for analyzing and predicting ecommerce sales using various data analysis techniques and machine learning models.

## Overview

The project utilizes publicly available datasets from Kaggle to predict sales in the ecommerce sector. By analyzing data such as product categories, prices, discounts, customer segments, and marketing spend, the goal is to create a model that predicts the number of units sold and total sales.

## Project Structure

- **Jupyter Notebooks**: The main notebooks for data exploration, data cleaning, visualization, and model training.
- **Python Scripts**: Helper Python scripts for data processing, feature engineering, and model deployment.
- **Dataset**: The dataset used in this project is sourced from Kaggle, and it contains detailed information about sales, customer demographics, and marketing efforts.

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **scikit-learn**: For building machine learning models.

## Dataset

The dataset used in this project is sourced from Kaggle and contains the following columns:

- **Date**: The date of the transaction.
- **Product_Category**: The category of the product.
- **Price**: The price of the product.
- **Discount**: The discount applied to the product.
- **Customer_Segment**: The segment of the customer (e.g., Occasional, Premium).
- **Marketing_Spend**: The marketing spend for the product.
- **Units_Sold**: The number of units sold.

## Objective

The primary goal of this project is to predict the **Units_Sold** based on various factors such as price, discount, marketing spend, and customer segment. This will provide insights into which factors most significantly influence sales, helping ecommerce businesses optimize their strategies.

## Getting Started

### Prerequisites

To run this project locally, you'll need to install the required Python libraries. You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Ecommerce-Sales-Prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Ecommerce-Sales-Prediction
   ```

3. Open the Jupyter Notebooks to start exploring the data:

   ```bash
   jupyter notebook
   ```

4. Analyze the data, train the models, and generate sales predictions.

