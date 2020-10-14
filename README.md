# salary Prediction Project
# Define the Problem
Project Goal: The goal of this project is to examine a set of job postings with salaries and then predict salaries for a new set of job postings.

Tool: Python 3-Jupyter Notebook with a wide range of libraries and packages such as Pandas,NumPy,sklearn,matplotlib,seaborn for data manipulation,data visualization and predictive modeling.
# Data
train_features.csv: Each row represents metadata for an individual job posting. The job Id column represents a unique identifier for the job posting. The remaining columns describe features of the job posting.

train_salaries.csv: Each row associates a job Id along with salary.

test_features.csv: metadata for an individual job posting.

Feature includes Job-Type ,Degree,Major ,Industry,YearsofExperience,MilesFromMetropolis 
# Steps

1.Import Libraries 

2.Load Data

3.Clean data---> No duplicates and no null values in data and dropped invalid data

4.Explore data
Visualized coorelation matrix for each features and target variables using plots and counts.
diagram.
Identified highest coorelated feature as yearsofexperience

5.Baseline model:
The baseline negative MSE error:-1288

6.Hypothesis solutions:
The baseline model can be improved by using different supervised algorithms like
1.Random Forest ---->Random forest is a collection of decision trees which are randomly trained by nature and easy to
implement. The goal is to aggregate the accuracy of all the trees.It handles overfitting issues by reducing variance and independent classifiers.
2.Gradient Boosting Algorithms------> combines weakly coorelated fetures into a single strong learner.

7.Model development---->create models and evaluate models
Results of Evaluate Models
Multiple Linear Regression:-925 MSE
Random Forest:-389 MSE
Gradient Boosting:-358 MSE

8.selected best model with low Mean square error as Gradient Boosting.

9.Deploy models to predict features for testing data




