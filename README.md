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

1. Load data
2. Data informatin:data type,discribtion, size, Nan,Checking Numerical Columns
3. Data Cleanning
4. unique
5. Visualization
6. Removing Outlier
7. Merging Dataframes
8. Machine learning Model and after Balancing dataset the machine learning model prediction.
    1. Logistic Regression
    2. Decision Tree classification
    3. Random Forest classification
    4. Support Vector Machine classification
    5. K Nearest Neighbor classification
    6. XGBoost classification
 

### Load data
 
load the data CSV data into Jupiter notebook using pandas library
Table 1

 ![image](https://user-images.githubusercontent.com/80365882/139561296-b590a1d6-0b15-4dca-b56c-ac7bb63fe1c3.png)

 ### Data informatin:data type,discribtion, size, Nan,Checking Numerical Columns
 Data processing is very important for further analysis of using the models. Even though we check the dataset on a spreadsheet before cleaning, it is good looking at the data type, the shape of the data, the Nan or no data, after that making some modifications on the dataset based on the observation. such as if necessary, converting days to years.
  
   
 ### data cleaning

Table 2 data Cleaning

![image](https://user-images.githubusercontent.com/80365882/139561360-8dc1a380-e1a4-49fe-9ff3-e2a8810c9da0.png)

### Checking the unique Value
Checking unique value help us to see right information in the columns.

### Removing Outlier

Table 1.
![image](https://user-images.githubusercontent.com/80365882/139747655-80741242-f02c-43bf-a97e-70c2c6afc44f.png)

Table 2. 
![image](https://user-images.githubusercontent.com/80365882/139747706-e45e5468-cc2b-4b83-a628-630e6243c8f6.png)

Table 3.
![image](https://user-images.githubusercontent.com/80365882/139747817-148c6ae3-c515-4a1f-9985-9e572f5b250a.png)
Table 4.
![image](https://user-images.githubusercontent.com/80365882/139747854-d1a5ea63-e572-448c-8be8-f3f579bf2d51.png)

Table 5.
![image](https://user-images.githubusercontent.com/80365882/139747896-94a622b4-81b8-48e0-bcba-9be5441c60ef.png)

Table 6.
![image](https://user-images.githubusercontent.com/80365882/139748309-eb93dd17-eb3d-4d84-b6d0-a6f854d6188d.png)


### Removing Outlier

![image](https://user-images.githubusercontent.com/80365882/139748036-0f224f6b-9cd9-401b-8e91-ecb908793b50.png)

### Merging Dataframes
Merging the two dataframe(Application and Credit)
![image](https://user-images.githubusercontent.com/80365882/139749078-4763d673-598f-43b0-9ffd-dd96ce2aaca6.png)

### Machine learning Model and after Balancing dataset the machine learning model prediction




