# Customer Segmentation for Automobile Company Using RFM-analysis

## About this Project
I found this dataset from https://github.com/adiag321/Customer-Segmentation-for-Automobile-Company

This project aims to improve customer understanding and potentially increase revenue using a dataset from the Automobile industry. The dataset includes customer demographics and 2017 transaction data.

# This Project folowing this step
## 1.Understand data
This dataset include

Transaction 2017: This file contains transaction data from the year 2017, including details about customer purchases across various states in Australia.

CustomerDemographic: This file contains details about the customers, such as age, gender, job

NewCustomerList: This file contains details about the new customers. It likely includes additional features beyond those found in CustomerDemographics.

CustomerAddress: This file stores the addresses of the customers.

## 2.Prepare data
This step focus in clean data make it to ready use

- identify missing values in each column and choose the best approach to handle them. In this data set i dropping rows or columns with a high percentage of missing values

- Explore the distribution of numerical features and identify outliers

- Tranfrom feature type into a suitable format such as date
  
- create new features that might be helpful for the analysis. For example, calculate age from the birth date, create full-name from first name and last name

## 3.RFM analysis
Calculate RFM from each customer including

1.Recency  : Calculate the number of days since the last transaction for each customer.

2.Frequency: Calculate the number of transactions each customer had in 2017.

3.Monery   : Calculate both calculations for the monetary 

             - Average Spending (Mean): Calculate the average amount spent by each customer in 2017.
             
             - Total Spending (Sum): Calculate the total amount spent by each customer in 2017.

Once I have calculated RFM scores for each customer, I can segment them using 3 methods:

### Kmean
Use K-Means clustering to segment customer data based on their RFM (Recency, Frequency, Monetary Value) scores. 
The optimal number of clusters (k) will be determined using the Elbow Method.

### Hierachical
Use Hierachical clustering to segment customer data based on their RFM (Recency, Frequency, Monetary Value) scores.

### Rule Based
Use Rule Based clustering to segment customer data based on their RFM (Recency, Frequency, Monetary Value) scores.

compare result from each method

## 4.Build Dashbord
1. Create Dashboard from Transaction 2017 to present how transaction be in 2017

https://app.powerbi.com/links/LnjlNpLVxb?ctid=8c1832ea-a96d-413e-bf7d-9fe4d608e00b&pbi_source=linkShare
![image](https://github.com/TongtaiM/Customer-Segmentation-for-Automobile-Company-Using-RFM-analysis/assets/159317591/b04a13a9-6e44-444f-9317-fba6328cc90e)
   


This is my first attempt at building a dashboard! (My university doesn't cover this yet, but that's okay).  I know there might be some initial mistakes, but I'm excited to learn and improve with each iteration.



I learned about RFM analysis on this website. Thank you!
https://predictive.co.th/en/blog/rfm-analysis/
https://doctorease.co/what-is-rfm/
