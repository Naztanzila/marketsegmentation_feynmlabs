# marketsegmentation_feynnlabs
This repository contains Python code to perform customer segmentation, correlation analysis, and visualizations based on a dataset related to McDonald's customer responses. The dataset includes information about customer preferences and demographics.

#Dataset 
The dataset includes the following columns:

yummy, convenient, spicy, fattening, greasy, fast, cheap, tasty, expensive, healthy, disgusting: Binary columns indicating customer responses (Yes/No).
Like: A numeric score representing customer sentiment towards McDonald's.
Age: The age of the customer.
VisitFrequency: The frequency with which a customer visits McDonald's.
Gender: The gender of the customer.

#Installation
To run the code in this repository, you need to have Python 3.x installed along with the required packages. You can install the necessary packages using pip:
pip install pandas seaborn matplotlib scikit-learn

#Usage
1. Data Preprocessing
Convert the categorical responses (Yes/No) into numerical values, and encode the VisitFrequency column into numeric values.
2. Customer Segmentation
Apply K-Means clustering to segment customers based on their responses.
3. Correlation Analysis
Examine the relationships between variables like Age, VisitFrequency, and Like.
4. Visualizations
Visualize the mean VisitFrequency, Like, and Female Ratio by segment.

#Results
The results include customer segments, correlation coefficients, and visualizations that provide insights into customer behavior and preferences at McDonald's.

Customer Segments: Identified distinct customer profiles based on their responses.
Correlation Analysis: Examined how age and visit frequency correlate with customer sentiment (Like).
Visualizations: Bar plots showcasing differences between segments in terms of visit frequency, customer sentiment, and gender distribution.
