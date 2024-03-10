# RFM Analysis Project

## Introduction
This project focuses on conducting RFM (Recency, Frequency, Monetary) analysis on customer purchase data to segment customers and identify key marketing strategies.

## Environment Setup
To run this project, you will need to install the following Python packages:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Lifetimes

You can install these packages using `pip`:

    pip install pandas numpy matplotlib seaborn scikit-learn lifetimes

## Data Cleaning and Preparation
The data is loaded from an online CSV file and requires certain cleaning steps, including:
- Renaming unnamed columns
- Converting the 'Date' column to datetime format
- Creating a 'Total' column representing total spending per transaction

## Running RFM Analysis
The RFM analysis is conducted by grouping the data by customer ID and calculating the recency, frequency, and monetary metrics. Further data visualization is carried out to understand the distribution of these metrics.

## Customer Segmentation
K-means clustering is applied to the standardized RFM data to segment the customers into meaningful groups.

## Insights and Marketing Strategies
Based on the analysis, insights are derived about customer behavior, and appropriate marketing strategies are suggested for different customer segments.

## How to Use This Repository
1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Run the `module_1_rfm.ipynb` notebook to perform the RFM analysis.

## Contributors
- Alberto Diaz

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
