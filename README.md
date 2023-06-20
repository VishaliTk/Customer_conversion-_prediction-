# Customer_conversion-_prediction-
# Problem Statement 

You are working for a new-age insurance company and employ mutiple outreach plans to sell term insurance to your customers. Telephonic marketing campaigns still remain one of the most effective way to reach out to people however they incur a lot of cost. Hence, it is important to identify the customers that are most likely to convert beforehand so that they can be specifically targeted via call. We are given the historical marketing data of the insurance company and are required to build a ML model that will predict if a client will subscribe to the insurance.

# Features: 
age (numeric) ,
job : type of job ,
marital : marital status ,
educational_qual : education status ,
call_type : contact communication type ,
day: last contact day of the month (numeric) ,
mon: last contact month of year ,
dur: last contact duration, in seconds (numeric) ,
num_calls: number of contacts performed during this campaign and for this client  ,
Dataset in dataset_fin.csv 

# Project approach
In this project i use the google colab for python programming and machine learning
# Importing all the packages
importing the machine learning packages and python libraries
# Data cleaning
i clean the data through missing values,removing duplicates ect..
# Exploratory data analysis
To predict the good model i done Univariate analysis,Bivariate analysis,correlation checking ,data type checking and take dummies
# Encoding categorical Features
I used Label and one hot encoding for this features("job","education_qual","martial","call type","mon","prev_outcomes)
# Spliting dataset
SMOTE Oversampling used because of imbalanced data
# scalling
StandardaScaler used
# Models
I use all the classification algorithms for this dataset because it is catagorical data set
Logistic Regression is:  92.08629932331488 %
Random forest is : 93.8790754899376 %
X Gradient Boosting is: 93.589067580631 %
K Nearest Neighbour is :  0.9169522805167414 %
DecisionTreeClassifier is :  0.858732116962102 %
 

