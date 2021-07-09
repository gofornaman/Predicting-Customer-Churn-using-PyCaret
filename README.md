# Predicting-Customer-Churn-using-PyCaret
A step-by-step guide on how to predict customer churn the right way using PyCaret that actually optimizes the business objective and improves ROI. 

Link to NBViewer - http://tiny.cc/os3auz

#### 1. Objective 

* Customer Attrition or Churn refers to a decision made by the customer about ending the business relationship.
* Customer loyalty and customer churn always add up to 100%. If a firm has a 60% of loyalty rate, then their loss or churn rate of customers is 40%.
* The primary objective of the customer churn predictive model is to retain customers at the highest risk of churn by proactively engaging with them. For example: Offer a gift voucher or any promotional pricing and lock them in for an additional year or two to extend their lifetime value to the company.

-----------

#### 2. Approach

* One of the ways to calculate a churn rate is to divide the number of customers lost during a given time interval by the number of active customers at the beginning of the period. For example, if you got 1000 customers and lost 50 last month, then your monthly churn rate is 5 percent.
* We need the model to predict churn in advance and for that we need to define a cut-off date. 
* The period before the cut-off date is called as an "Event"
* For your target variable, you want to predict if the customer will churn within the next quarter, and so you will iterate through all the active customers as of your event cut-off date and check if they left the company in the next quarter or not (1 for yes, 0 for no). The quarter in this case is called Performance Window

-------------


![S1](https://github.com/gofornaman/Predicting-Customer-Churn-using-PyCaret/blob/main/img/c1.PNG)

![S2](https://github.com/gofornaman/Predicting-Customer-Churn-using-PyCaret/blob/main/img/c4.PNG)

![S3](https://github.com/gofornaman/Predicting-Customer-Churn-using-PyCaret/blob/main/img/c2.PNG)

![S4](https://github.com/gofornaman/Predicting-Customer-Churn-using-PyCaret/blob/main/img/c3.PNG)

-------------
