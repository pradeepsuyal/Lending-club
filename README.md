![Screenshot (179)](https://user-images.githubusercontent.com/86251750/133406846-9c08e20f-ee2d-45b3-ac95-25bd089c4717.png)

Lending Club connects people who need money (borrowers) with people who have money (investors).  It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. At its height, LendingClub was the world's largest peer-to-peer lending platform before abandoning the peer-to-peer lending model in the fall of 2020. Lending club had a very interesting year in [2016](https://en.wikipedia.org/wiki/LendingClub#2016) . In April 2016, a LendingClub employee reported to Laplanche that the dates on approximately $US 3 million in the firm's loans appeared to have been altered


more about Lending club at [wikipedia](https://en.wikipedia.org/wiki/LendingClub)

**OBJECTIVE**
--------------------------
We will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full. 

**Dataset**
---------------------------
This datset has been taken from [kaggle](https://www.kaggle.com/wendykan/lending-club-loan-data)

**About the Dataset**
--------------------------
Here are what the columns represent:

• credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.

• purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").

• int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.

• installment: The monthly installments owed by the borrower if the loan is funded.

• log.annual.inc: The natural log of the self-reported annual income of the borrower.

• dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).

• fico: The FICO credit score of the borrower.

• days.with.cr.line: The number of days the borrower has had a credit line.

• revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).

• revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).

• inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.

• delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.

• pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

**Model Accuracies:**
-------------------------
I have used three models for this classification dataset-

| Model        | Accuracy       |
| ------------- |:-------------:|
| Decision Tree | 0.84620       |
| Random forest | 0.84620       |  
| KNN           | 0.82985       | 

we got some accuracy for Random forest and Decission tree model.

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)   ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)



