# Food_Sales_Predictions
Data Science Course Project
## Preprocessing of Data and Creation of Sales Prediction Model

**Denis Ssendagire**: 

### Business problem:

A Food sales business would like to understand the properties of products and outlets that would play a crucial role in increasing sales.
Here is where you state the business problem you were trying to solve


### Data:
Data Source: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/. Data has properties of the products and sales outlets of a food sales entity. Below are the columns and data types representing the properties:

- Item_Identifier               object
- Item_Weight                  float64
Item_Fat_Content              object
Item_Visibility              float64
Item_Type                     object
Item_MRP                     float64
Outlet_Identifier             object
Outlet_Establishment_Year      int64
Outlet_Size                   object
Outlet_Location_Type          object
Outlet_Type                   object
Item_Outlet_Sales            float64
Data can include source and high-level description (e.g. # obs)


## Methods
Data Exploration is done using info(), shape(), unique() methods. Data is checked and addressed for: duplicates, missing values, incorrect data types, inconsistencies and incorrectiness.
- Duplicates one insitance of duplicate data is retained while the others are dropped.
- Incoconsistencies are standardised
- Ordinal data is encoded.
- Train-test split is performed on the data.
- Missing values imputed during preprocessing.
- Categorical data converted to numerical data during preprocessing.
- Data is prepared (preprocessed) for Machine Learning by using SimpleImputer, OneHotEncoder, Pipelines and Column Transformers.
- Models are built: Linear Regression and Regression Tree.

## Results

### Here are examples of how to embed images from your sub-folder


#### Visual 1 Title
![sample image](project1_sample_image.png)

> Sentence about visualization.

#### Visual 2 Title

## Model

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**l
