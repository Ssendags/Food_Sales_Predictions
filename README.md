# Food_Sales_Predictions
Data Science Course Project
## Preprocessing of Data and Creation of Sales Prediction Model

**Denis Ssendagire**: 

### Business problem:

A Food sales business would like to understand the properties of products and outlets that would play a crucial role in increasing sales.

### Data:
Data Source: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/. Data has properties of the products and sales outlets of a food sales entity. Below are the columns and data types representing the properties:

- Item_Identifier               object
- Item_Weight                  float64
- Item_Fat_Content              object
- Item_Visibility              float64
- Item_Type                     object
- Item_MRP                     float64
- Outlet_Identifier             object
- Outlet_Establishment_Year      int64
- Outlet_Size                   object
- Outlet_Location_Type          object
- Outlet_Type                   object
- Item_Outlet_Sales            float64


## Methods
Data Exploration is done using info(), shape(), unique(), duplicated() methods. Data is checked and addressed for: duplicates, missing values, incorrect data types, inconsistencies and incorrectiness.
- For duplicates one insitance of duplicated data is retained while the others are dropped.
- Inconsistencies are standardised
- Ordinal data is encoded.
- Train-test split is performed on the data.
- Missing values imputed during preprocessing.
- Categorical data converted to numerical data during preprocessing.
- Data is prepared (preprocessed) for Machine Learning by using SimpleImputer, OneHotEncoder, Pipelines and Column Transformers.
- Models are built and evaluated: Linear Regression and Regression Tree.

## Results

### Here are examples of how to embed images from your sub-folder


#### Explanatory Data Analysis:

![image](https://user-images.githubusercontent.com/109603891/189351893-a837a708-3df7-4c4c-8a29-e4d7b0cee491.png)

Outlet Sales by Outlet Type.

![image](https://user-images.githubusercontent.com/109603891/189352239-e20554c6-e6f7-4004-9316-7aa021370bcf.png)

Outlet Sales by Outlet Location Type.

From the above visualisations it is evident that Outlet sales have a pattern with each of Outlet Type and Outlet Location Type.

#### Best Fitting Model:
![image](https://user-images.githubusercontent.com/109603891/189347042-6396daba-b8cb-4c6a-9692-70fd825f8b37.png)
![image](https://user-images.githubusercontent.com/109603891/189347767-e0840868-d31e-4d8c-960b-67f3be793de7.png)


## Model

From the 3 models considered above the regression tree model has given better values (training = 60% and testing = 60%) making it the best fit, this as compared to R^2 which was found to be too low (Training = 1 and Testing = 0.00022) and RMSE which was found to be too high (Training = 8.32 and testing = 72.39x10**12).

## Recommendations:

In this case the tuned (max_depth = 5) regression tree model shall be considered for deployment.

## Limitations & Next Steps

Given that the best fit attained is 60%, it is in consideration to develop and evaluate other models until the highest best fit is achieved.


### For further information

For any additional questions, please contact **ssendags@gmail.com**l
