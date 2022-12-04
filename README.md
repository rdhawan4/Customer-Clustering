# Clustering without Target Variables
### Clustering on Bank Customer data <br>
- In this problem set, we are trying to find out the best clusters for this dataset. <br>
Different clustering mehtods were evaluated using the Silhoutte and Inertia Scores for different values of K. <br>

<img width=500 src='https://user-images.githubusercontent.com/112804900/205485314-bb9be68b-ac93-4b7d-9145-c49564c4fd5c.jpg'>

The Following are the input parameters for the clustering: <br>

|Feature Name| Description|
|:--|:--------|
|CUSTID | Identification of Credit Card holder (Categorical)|
|BALANCE | Balance amount left in their account to make purchases (|
|BALANCEFREQUENCY | How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)|
|PURCHASES | Amount of purchases made from account|
|ONEOFFPURCHASES | Maximum purchase amount done in one-go|
|INSTALLMENTSPURCHASES | Amount of purchase done in installment|
|CASHADVANCE | Cash advance given to the user|
|PURCHASESFREQUENCY | How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)|
|ONEOFFPURCHASESFREQUENCY | How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)|
|PURCHASESINSTALLMENTSFREQUENCY | How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)|
|CASHADVANCEFREQUENCY | How frequently the cash in advance being paid|
|CASHADVANCETRX | Number of Transactions made with "Cash in Advanced"|
|PURCHASESTRX | Number of purchase transactions made|
|CREDITLIMIT | Limit of Credit Card for user|
|PAYMENTS | Amount of Payment done by user|
|MINIMUM_PAYMENTS | Minimum amount of payments made by user|
|PRCFULLPAYMENT | Percent of full payment paid by user|
|TENURE | Tenure of credit card service for user|
<br>

## Silhouette & Inertia Scores
![image](https://user-images.githubusercontent.com/112804900/205485161-8fdce77f-c914-4031-8005-4cc5dc3fd456.png)

![image](https://user-images.githubusercontent.com/112804900/205485170-0d7bb3d1-40e7-4cf2-b4c9-8554e4c2f91d.png)

## Evaluating separation of K Clusters

![image](https://user-images.githubusercontent.com/112804900/205485175-6d95b027-45ee-4e40-82a1-551a38547ec8.png)

![image](https://user-images.githubusercontent.com/112804900/205485193-515df4a8-5dce-47b0-acb0-d668b57eeb22.png)

# Note
- Main Testcode : BankCustomer_Clustering.ipynb
- Datasets available in Data folder
