# Rainfall-Prediction

## 1. Project Description

.This is machine learning project to predict next-day rain by training classification 
        models on the target variable **RainTomorrow** .

.It includes data preprocessing, feature engineering, model training, evaluation ,and 
        deployment steps.

.I make some EDA for good understanding to dataset.

.The first challenge is to handle null values with the best way ,in this project i used 
       models to predict null values based on all feature exist in dataset i used  **LinearRegression**
       for numerical values ,and **LogisticRegression** for catigorical values.
         
.the second challenge is to handel outlier i used a lot of techniques such as : IQR , 
       sqrt ,log transformation , BOX-COX , power transformation (you can search for them ) 
       then i finally used **RobustScaler transformation** .

.Then i use encode my categorical feature using **LabelEncoder** .

.then i split my data into traning and testing 80% -20% 
.then i select the best model for my dataset i used RandomForest because my data is low implanced ,
       you can use any ensampling model .

.first the model make overfitting ,i make hyperparameter tuning to select the best hyperparameter 
       for my model .

.I also used nueral network model ,and the final accuracy is 88.5 % , this is the best accuracy 
       comparing with the original data .

       
## 2. Table of Contents

[Dataset](https://github.com/elnemr19/Rainfall-Prediction/blob/main/README.md#3-dataset)

[Analysis]()

[Model Overview](https://github.com/elnemr19/Rainfall-Prediction/blob/main/README.md#4-model-overview)

[Results](https://github.com/elnemr19/Rainfall-Prediction/blob/main/README.md#5-results)

[Deployment]()

        
## 3. Dataset

-Source : Kaggle - [Rain in Australia](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

-Description : all description exist on first cell of the code .

-Loading the data: "The dataset is loaded directly from Kaggle using the Kaggle API."


## 4. Analysis

-I make EDA for good understand to data using python ,all details on the code .
-I also mske analysis using **power pi**
![image](https://github.com/user-attachments/assets/6700ab96-f8b8-430a-adfe-f7250590f2c5)
![image](https://github.com/user-attachments/assets/05d7cce1-d3de-45e8-b531-98a8416117e7)
![image](https://github.com/user-attachments/assets/36a15bf5-9340-4a67-a7af-8afbcbc6a0c8)


## 4. Model Overview

 - I use **RandomForest** model ,as he is good for implanced data all details exist on the code .
 - First the model is overfitting ,then i used hyperparameter tuning (search for it) to know
   what are the best hyperparameter for my model .



 -I use **NN model** with 5 hidden layers , and i use activation function such as **relu** for input 
   and hidden layers ,and **sigmoid** for output layer.
   

## 5. Results







































        
