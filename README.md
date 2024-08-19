# Rainfall-Prediction

## 1. Project Description

      .This is machine learning project to predict next-day rain by training classification 
        models on the target variable  RainTomorrow .

      .It includes data preprocessing, feature engineering, model training, evaluation ,and 
        deployment steps.

      .I make some EDA for good understanding to dataset.

      .The first challenge is to handle null values with the best way ,in this project i used 
       models to predict null values based on all feature exist in dataset i used  LinearRegression
       for numerical values ,and LogisticRegression for catigorical values.
         
      .the second challenge is to handel outlier i used a lot of techniques such as : IQR , 
       sqrt ,log transformation , BOX-COX , power transformation (you can search for them ) 
       then i finally used RobustScaler transformation .

      .Then i use encode my categorical feature using LabelEncoder .

      .then i split my data into traning and testing 80% -20% 
      .then i select the best model for my dataset i used RandomForest because my data is low implanced ,
       you can use any ensampling model .

      .first the model make overfitting ,i make hyperparameter tuning to select the best hyperparameter 
       for my model .

      .I also used nueral network model ,and the final accuracy is 88.5 % , this is the best accuracy 
       comparing with the original data .

       
## 2. Table of Contents

     [Dataset]
     [Model Overview]
     [Results]
     [Contribution]

        

      






        
