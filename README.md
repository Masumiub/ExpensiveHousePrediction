# ExpensiveHousePrediction
Expensive House Prediction using KNN and OLS.

In this assignment, we will implement K-Nearest Neighbour (KNN) and Ordinary Least Square (OLS) regression methods. Download the excel file. The dataset contains 11 columns: "bedrooms", "bathrooms", "sqft_living", "sqft_lot", "floors", "condition", "grade", "sqft_above", "sqft_basement", "age"and "price". Use pd.read_excel() to read the file and make prediction of whether a given house is likely to be expensive based on the features related to the house.

Use KNN and OLS regression independently to determine and compare their performance in terms of accuracy and confusion matrix.

To accomplish this task, you will have to convert the values under "price" into one of two possible values: 1 and 0 denoting "expensive" and "cheap" respectively. For this, if the price of the house is less than 450000, it is "cheap"; otherwise it is "expensive" .

Note:This conversion must be done before training for KNN, and after conversa for OLS regression, on each predicted "price".
