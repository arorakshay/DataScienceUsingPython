# Customer Segmentation on Banks Data
![image.png](Images/KM.png)

## INTRODUCTION
**This case is about a bank which has a growing customer base.The management wants to explore ways to improve its revenue using a machine learning model. This has encouraged the retail marketing department to devise campaigns to do better targeted marketing.**

**The department wants to build a model that will help them identify characteristics of groups of customers. This will increase their revenu while at the same time reduce the cost of the campaign.**

## DATA
| Column Name | Description |
| --- | --- |
| `ID`  | Customer ID |
| `Age`  |Customer's age in completed years |
| `Experience`  | #years of professional experience |
| `Income Annual`  | income of the customer (USD 1000) |
| `ZIPCode`  | Home Address ZIP code |
| `Family`  | Family size of the customer |
| `CCAvg Avg`  | spending on credit cards per month (USD 1000) |
| `Education`  | Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional |
| `Mortgage`  | Value of house mortgage if any. (USD 1000) |
| `Personal Loan`  | Did this customer accept the personal loan offered in the last campaign? |
| `Securities Account`  | Does the customer have a securities account with the bank? |
| `CD Account`  | Does the customer have a certificate of deposit (CD) account with the bank? |
| `Online`  | Does the customer use internet banking facilities? |
| `CreditCard`  | Does the customer uses a credit card issued by UniversalBank? |


#### Objectives:
 - **Cluster customers into segments using K-Means Clustering Algorithm.**
 - **Identify properties of each cluster semgent.**
 - **Propose actions for each cluster that help will the Bank increase its revenue with a minimal budget.**

### Conclusion
- We have used below three __ML algo__ for customer segmentation:
    - K-Means Clustering
- This notebook helps us classiying customers in diffrent groups to increase their revenue. Below 4 clusters have been created:
#### Cluster 0
 - **Age and Experinece is less** as compared to Cluster 1 and Cluster 2, but **this cluster has highest average income.**<br/>
 - **CCAvg is also high.** 
 - So, **we can offer them lucrative credit card schemes.**
 <br/>
 - Most of the customers did not accept a personal loan offer.
 - So, it is a waste of time pursuing customers to take a loan.
 
 #### Cluster 1 and Cluster 2
  - **Customers who accepted a personal loan offer mostly belong to these clusters.**<br/>
  - Their **income is better than Cluster 3.**
  - So we can **run a campaign to pursue other customers in these clusters to take a loan** so that the **Bank can earn money through interest.**

#### Cluster 3<br/>
 - **Age is less<br/>**
 - **Experience is less<br/>**
 - **Income is less<br/>**
 - **Family sizie is high<br/>**
 - Some customers in this cluster **also accepted personal loan offer.** 

[Jupyter Notebook](./Kmeans.ipynb)
