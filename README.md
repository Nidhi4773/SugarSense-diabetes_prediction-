# SugarSense-diabetes_prediction-
# Project Overview:
sugarsense is a machine learning-based classification project that predicts whether a patient is likely to have diabetes. It uses the Logistic Regression algorithm on the Pima Indians Diabetes dataset. This project includes data cleaning, feature scaling, training, and evaluation.

# Dataset Used:
The dataset diabetes.csv includes the following features:

     *Pregnancies
 
     *Glucose

     *BloodPressure
  
     *SkinThickness
 
     *Insulin
     
     *BMI
     
     *DiabetesPedigreeFunction
    
     *Age
 
     *Outcome (0 = No Diabetes, 1 = Diabetes)
 
# Steps Followed in the Project:

1-Load the dataset using pandas

2-Check for null values and basic statistics

3-Visualize feature correlation using a heatmap

4-Split data into training and testing sets (80-20)

5-Scale the features using StandardScaler

6-Train a Logistic Regression model

7-Predict and evaluate the results using:

   ->Accuracy score
   
   ->Classification report
   
   ->Confusion matrix heatmap
   
# Libraries Used:

>pandas

>numpy

>matplotlib

>seaborn

>scikit-learn

# Project Structure:
diabetes_pre.py → Python script for training and testing

diabetes.csv → Dataset (must be downloaded manually)

README.txt → Project description

# Model Evaluation:
Accuracy Score

Precision, Recall, F1-Score

Confusion Matrix



