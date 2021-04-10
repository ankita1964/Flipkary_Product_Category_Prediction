# Flipkary_Product_Category_Prediction

<img width="660" alt="Screenshot 2021-04-10 at 11 17 18 AM" src="https://user-images.githubusercontent.com/58811776/114275679-01e0e600-9a41-11eb-8984-6d08bd0fd29e.png">

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
Since the dataset had 2 outliers, balancing was done and balanced dataset was obtained to further work upon.

<img width="1018" alt="Screenshot 2021-04-10 at 8 34 31 PM" src="https://user-images.githubusercontent.com/58811776/114275474-30aa8c80-9a40-11eb-8d5a-e0fed4562012.png">

<img width="348" alt="Screenshot 2021-04-10 at 9 06 30 PM" src="https://user-images.githubusercontent.com/58811776/114275789-7451c600-9a41-11eb-8648-75d0a656403f.png">

After Data preprocessing:



## Text Pre-processing:
The descriptions were cleaned(removal of stop words, changing to lowercase etc.) and most common words for each category as well as whole dataset were plotted.

## Model Building:
Logistic Regression, Naive Bayes, Random Forest and SVM was tried. Random Forest outperformed amongst all the models with an accuracy of ~99% while other SVM did not perform at par with the others.

