# Customer_Segmentation_Using_Kmeans
This is a repository consisting of an unsupervised Machine learning Algorithm known as KMeans
![download](https://user-images.githubusercontent.com/83602292/194211834-4f1f87dd-5224-4dec-929f-a87effe91742.jpg)
# **Introduction**
***

Customer clustering analysis is the use of a mathematical model to discover groups of similar customers based on finding the smallest variations among customers within each group. These homogeneous groups are known as “customer archetypes” or “personas”.

## **Overview**
***
### **Problem Statement**

 In order to comprehend the behavior of their customers, I will analyze the customer data from a retail company. Hopefully, a wealth of information will be uncovered that will assist the business in planning its upcoming campaigns by identifying the most valuable clients and identifying the target market for a new product.

### **Success Metrics**
***
Achieving clusters with profiles that are cohesive to the EDA done on the dataset

### **Context**
***
The dataset holds data from a marketing campaign and was collected between 2012 and 2014. The data has customer behavioral data for a retail outlet.


#### **Relevance and Validation**
***
The original dataset, that can be found in  <a href="https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis"> this kaggle dataset</a>. It contains information of 2240 customers, with 29 attributes each. These attributes are: 
 
#### **Column Descriptions**
***
- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise

**Products**

- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years

**Promotion**

- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

**Place**

- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to company’s website in the last month
