# HOUSE-PRICE-PREDICTOR

# Problem Statement

Prices of real estate properties are sophisticatedly linked with our economy. Despite this, we do
not have accurate measures of housing prices based on the vast amount of data available.
Therefore, the goal of this project is to use machine learning to predict the selling prices of
houses based on many economic factors. 

# Data Set Preview

![image](https://user-images.githubusercontent.com/85097320/181282785-87b7b9d6-b255-4a10-9248-33cb5246caba.png)

# Idea

To build a predictive model that can predictive House price using ML algorithms(Linear Regression, Random Forest, Xgboost).

# Implementation

The Prediction was done in 2 Steps

# Step 1 -> Data Preprocessing

Steps performed in Preprocessing:

1. Exploring the target and independent variables.
2. Treating the outliers and missing values in independent and target variables.
3. Transforming the categorical variables into numerical variables using dummy encoding.

The file Data Preprocessing.ipynb contains the code for Preprocessing.

The preprocessing was performed on Housing Prices.csv (initial dataset) and was transformed to Transformed Housing Data.csv.
The Dataset [Housing Prices.csv.csv] looks like this on preprocessing
![image](https://user-images.githubusercontent.com/85097320/181287402-42ef7545-923d-4dbd-b082-86a4fcded6e3.png)

# Step-2 -> Building and making the Model Predictive

Steps performed in Model Building:
1. Importing the libraries and Transformed Data.
2. Scaling the dataset
3. Checking and Removing Multicollinearity.
4. Creating test and training partitions
5.    Implementing the Models
      a. Multiple Linear Regression
      b. Random Forest Regression
      c. XGBoost Regression
4.    Generating predictions over the train and test dataset for the above models 
5.    Evaluating the models.
6.    Preparing the Residual plot.
7.    Predicting Sales Price

Model Building and Prediction.ipynb contains the code for Model Prediction.
On Trainig and Testing the data with the three algorithms mentioned, Random Forest appeared as the best fit for the model.

The Residual plots obtained where as follows:

# Multiple Linear Regression
![image](https://user-images.githubusercontent.com/85097320/181289239-eaa1962f-e0b8-46ee-b1be-525429cac87f.png)
![image](https://user-images.githubusercontent.com/85097320/181289285-88082395-f702-4427-b721-a85bcbf150dd.png)

# Random Forest
![image](https://user-images.githubusercontent.com/85097320/181289528-a7b006c9-abe7-4598-914d-0b803f6b64b4.png)
![image](https://user-images.githubusercontent.com/85097320/181289581-f418e4f2-b36d-487d-a33b-0663e5458fa8.png)

# Xgboost
![image](https://user-images.githubusercontent.com/85097320/181289737-dd07a795-bd8b-4c70-88fa-6024d5b06747.png)
![image](https://user-images.githubusercontent.com/85097320/181289782-c08c2b03-6019-4664-84f0-cd389faeb1e6.png)

![image](https://user-images.githubusercontent.com/85097320/181352475-4745df98-fbde-4f2a-8e0d-bbd709364260.png)



As Random Forest was more accurate, the price prediction was done using the same.

# Predicted Result

![image](https://user-images.githubusercontent.com/85097320/181352456-2d864aae-799a-475c-af5c-222cae9171f0.png)


