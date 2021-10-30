# Approval-of-a-credit-card-application
The project is basedon a company wants to automate the Credit Card eligibility process based on customer detail provided while filling online application form & Credit history of customer.

Data Sources:https://www.kaggle.com/rikdifos/credit-card-approval-prediction

### Introduction (Sources--https://www.kaggle.com/rikdifos/credit-card-approval-prediction)

Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.
 
Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.
 
At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.


Data Sources:https://www.kaggle.com/rikdifos/credit-card-approval-prediction

            :https://www.kaggle.com/vinaykhujat/credit-card-approval-prediction

### Outline

1. Import data
2. Data informatin:data type,discribtion, size, Nan,Checking Numerical Columns
3. Data Cleanning
4. unique
5. Visualization
6. Removing Outlier
7. Merging Dataframes
8. Machine learning Model and after Balancing dataset the machine learning model pridiction.
    1. Logistic Regression
    2. Decision Tree classification
    3. Random Forest classification
    4. Support Vector Machine classification
    5. K Nearest Neighbor classification
    6. XGBoost classification
 
 1. import data
 
load the data CSV data into Jupiter notebook using pandas library
Table 1

 ![image](https://user-images.githubusercontent.com/80365882/139561296-b590a1d6-0b15-4dca-b56c-ac7bb63fe1c3.png)

  2. Data informatin:data type,discribtion, size, Nan,Checking Numerical Columns
 Data processing is very important for further analysis of using the models. Even though we check the dataset on a spreadsheet before cleaning, it is good looking at the data type, the shape of the data, the Nan or no data, after that making some modifications on the dataset based on the observation. such as if necessary, converting days to years.
  
   
  4. data cleaning

Table 2 data Cleaning

![image](https://user-images.githubusercontent.com/80365882/139561360-8dc1a380-e1a4-49fe-9ff3-e2a8810c9da0.png)

