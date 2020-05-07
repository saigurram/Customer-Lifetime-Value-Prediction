# Marketing_CLTV
![alt text](https://169nk53l5vat1xy1vt3r9fwt-wpengine.netdna-ssl.com/wp-content/uploads/2019/02/customer-lifetime-value.png)

The dataset used in this analysis can be obtained from https://www.kaggle.com/olistbr/brazilian-ecommerce#olist_customers_dataset.csv 
 

## Problem definition

An organization has an ecommerce webiste and tracked the data for two years. The data collected is in order, customer, product tables. Identifying current revenue trends and predicting future revenue will help the organization estimate net profitability. 
Retaining existing customers and acquiring new customers is every organzation's mission. Understanding customer retention and customer acquisition numbers will aid Marketing department in redirecting their efforts. 
Identifying various product categories and their revenue contributions will help in product bundling/new product development efforts. 
Predicting the volume of products will aid Supply Chain department in optimizng their operaions. 
In this problem the objective is to predict the future revenue of a transaction thereby understanding product distribution and customer behavior.

## Dataset

After combining all the dataframes and removing duplicates the dataset has 112650 rows by 6 columns
 
## Feature Engineering

Created new features Recency, Category count and user type. 
Used K-means clustering(elbow method) to identify the optimal cluster count and created Recency cluster and product category cluster. 

## Model

Created a base decision tree model and predicted revenue numbers.
Created an XGBoost ensemble to improve the prediction and used gridsearchCV to obtain best parameters. 
Checked for overfitting and predicted final revenue numbers on test set. 

## Presentation 

Summarized all the findings in the Customer_Lifetimevalue_Prediction.pdf/ Customer_Lifetimevalue_Prediction.pptx file. 


