# NBA_MVP_Prediction_S21-22

Goal: 

To predict the next NBA Most Valuable Player Season 2021-2022 

Data: 
Official NBA players data between 1980 and 2021 

Methods: 

Step 1: Select potential MVP candidates' pool [Binary Classification]

Step2: Predict MVP share: MVP is the candidate with highest share [Regression]


1.1 Data Preprocessing 

Drop Redundant Features
Drop Highly Correlated Features
Missing Value Imputation
Standard Scaler
Label Encoder


1.2 Train-Test Split 
 Train: Before S2015
 Test: After S2015
 
1.3 Deal with imbalance data 
  Apply SMOTE 
  
1.4 Feature Reduction 
  Apply pca 
  
  
  
 2.1 Model-Binary Classification 
 Logistic Regression (L2) -> Random Forest -> Support Vector Machine 
 
 Cross Validation: 10-fold CV 
 
 2.2 Model-Regression 
 Linear Regression -> Random Forest -> XGBoost -> KNN 
 
 Cross ValidationL Leave one out CV
 
 3.1 Future improvement 
 - Could use NLP to study the media opinions on the MVP selection process 
 -Potential usecase: NBA All-Star prediction, NBA Trade Result

  
