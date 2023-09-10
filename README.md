# BharatIntern_MachineLearning_Internship
All tasks completed in Bharat Intern Machine Learning Internship.
Excited to share my first project under the Machine Learning Internship at Bharat Intern! 🤖🌐
Project Overview:
In this case study, I explored the fascinating world of housing data and used Linear Regression to predict house prices. It was a challenging and rewarding journey, and I'm thrilled to share some highlights with you!

📈 Key Findings:
Explored essential factors that influence house prices.
Identified significant trends in the housing market.
Developed a reliable predictive model for house price estimation.
Extracted valuable insights into the relationships between variables.

🏠 𝑷𝒓𝒐𝒋𝒆𝒄𝒕 1: 𝑯𝒐𝒖𝒔𝒆 𝑷𝒓𝒊𝒄𝒆 𝑷𝒓𝒆𝒅𝒊𝒄𝒕𝒊𝒐𝒏
I developed a machine learning model using linear regression to predict house prices. Check out the Jupyter notebook code for this project.

I like to express my gratitude to Bharat Intern for providing this opportunity 
Delighted to share the completion of the first task of my Machine Learning Internship at Bharat Intern.

1) Overview of the Dataset: Started by taking a look at the dataset's structure and the data types of each column.
2) Visualizing the Data: Used plotting techniques to visualize the data and plotted a correlation Heatmap. From there one thing was clear that Bathrooms , Area and Air conditioning were the making the highest impact on the pricing of Houses.
3) Prepared the data for training and testing by splitting it.
4) Used Regression techniques like Linear Regression, Random Forest, Lasso Regression, and PLS Regression. Other techniques such as k neighbors, Support Vector Regression were giving low accuracy score as compared to these techniques.
 RESULTS: 
Accuracy of PLS Regression was 62.7%
Accuracies of Linear Regression and Lasso Regression were the same 62.66%.
and Accuracy of RandomForest Regression was 55.32%

Now using Linear Regression gives one of the highest accuracy but it also had a very high Mean Absolute Error: 826960.5885819972
which is because of the outliers in the dataset. Same problem was faced with all the other Regression techniques. This means that while predicting the value of house my model's predictions for house prices are off by approximately $826,960.59 when compared to the true prices. This suggests that Regression might not be the optimal technique for this dataset.


Task Title : "𝐇𝐨𝐮𝐬𝐞 𝐏𝐫𝐢𝐜𝐞 𝐏𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐨𝐧"

Project Description : The project involved data exploration using Pandas and data visualization with Seaborn and Matplotlib to gain insights into the dataset. After selecting relevant features and splitting the data into training and testing sets, I employed scikit-learn to build a Linear Regression model for predicting house prices.

# Task 2- "Wine Prediction model using Linear Regression"

# Objectives: 

 To Predict the wine quality using Linear Regression Model.

 # Dataset:

I analyzed a comprehensive dataset containing the physiochemical tests results such as 'fixed acidity', 'volatile acidity', 'citric acid','residual sugar','chlorides','free sulfur dioxide','total sulfur dioxide','density','pH','sulphates','alcohol' etc. and quality on the scale of 1 to 10 of wines of the Vinho Verde variety.

Attribute Information:

Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable (based on sensory data):
12 - quality (score between 0 and 10)

# Steps:

Data pre-processing, Data cleaning, Data Visualization and Model Training and Model Prediction are the key fundamentals of this task.

1. Exploratory Data Analysis: Exploratory Data Analysis (EDA) helpedto gain insights into the dataset. Visualizations helped to understand the distribution of different parameters and identify any outliers or correlations.
  
2. Data Preprocessing: Ensuring data quality, I performed preprocessing tasks, including handling missing values,  feature scaling, and data partitioning for training and testing purposes.
  
3. Model building: I have Used Linear Regression algorithm  to predict the quality of wine .
   
4. Prediction and Evaluation: The model is tested. R2 score  of the model is .

# Task 3 - "Iris Flower Classification"

# Objectives: 

To build a machine learning model to predict the species of Iris flower into different species based on their features.

# Dataset:

A small classic dataset from Fisher, 1936.

Attribute Type:Real

Instances:150

Attributes:4

The iris dataset contains three classes of flowers, Versicolor, Setosa, Virginica, and each class contains 4 features, ‘Sepal length’, ‘Sepal width’, ‘Petal length’, ‘Petal width’.

Attribute Information:
    
1.sepal length in cm
2.sepal width in cm
3.petal length in cm
4.petal width in cm
5.class: 
-- Iris Setosa
-- Iris Versicolour
-- Iris Virginica

# Steps:
Data pre-processing, Data Visualization and Model Training and Model Prediction are the key fundamentals of this task.

1. Exploratory Data Analysis: I thoroughly analyzed the Iris flower dataset, gaining insights into the distinctive features that set each species apart.
  
2. Data Preprocessing: Ensuring data quality, I performed preprocessing tasks, including handling missing values, Label encoding, feature scaling, and data partitioning for training and testing purposes.
  
3. Model building: I have Used K-Nearest Neighbours(KNN) algorithm  on the iris dataset to predict the species of iris flower given the sepal and petal dimensions.
   
4. Prediction and Evaluation: I have created a new data frame and model is tested. Accuracy Score of the model is 97%.

   At last Thankyou Bharat Intern for providing this opportunity
