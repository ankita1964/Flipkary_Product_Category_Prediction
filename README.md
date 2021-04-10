# Flipkary_Product_Category_Prediction
Predicts the category of a product based on the description

## About: 
The objective of this repository is to predict the category of the product based on the description. 
The data used in this repo has been taken from Kaggle: https://www.kaggle.com/PromptCloudHQ/flipkart-products
The dataset consists information about 20000 products with features like description, retail price, discounted price etc.

## Steps Involved:
1. Exploratory Data Analysis

2. Data visualisation (Most Common Words, Max comment length)

3. Preprocessing the text

4. Model Building (Logistic regression, Naive Bayes, Random Forest, SVM)

5. Testing

## Data preprocessing: 
Initially, there was a product category tree. After processing, the primary category was figured out for all the rows. The category mentioned for a lot of products did not lie in 
in one of the primary categories. After visulation, correct category was alloted to such products. After the preprocessing, 18 primary categories were left.

![Primary Categories](https://drive.google.com/drive/u/0/my-drive)
