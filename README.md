# My Fourth Capstone
[Link to dataset used](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)
## Introduction

In this capstone project, we analyze a dataset containing information about students' scores in math, reading, and writing, as well as their average scores. Our objective is to gain insights from the data and build machine learning models to predict students' average scores based on various factors.

## Dataset

We start by loading the dataset, which is stored in a CSV file. The dataset contains information such as the students' gender, ethnic group, parental education, lunch type, test preparation, and weekly study hours, among others.

## Exploratory Data Analysis (EDA)

To get an initial understanding of the dataset, we perform exploratory data analysis. We examine the first few rows of the dataset, check the basic information using the `info()` method, and calculate descriptive statistics using the `describe()` method.

## Missing Values

We check for missing values in the dataset and find that there are no null values present.

## Pass/Fail Status

We determine the pass/fail status of each student based on their scores in math, reading, writing, and average. We set a pass mark of 50 and assign 'P' for pass and 'F' for fail. We then count the number of students in each pass/fail category for each subject.

## Density Plots

We create density plots for the math, writing, and reading scores to visualize their distributions. This helps us understand the spread and central tendencies of the scores.

## Number of Students Passing/Failing Each Subject

We calculate the number of students who pass or fail each subject (math, writing, reading, and average). Using this information, we create a bar chart to visualize the number of students passing or failing in each subject.

## Machine Learning Models

We move on to building machine learning models to predict students' average scores. We start with a Random Forest Regressor and evaluate its performance using mean squared error (MSE) and mean absolute error (MAE).

Next, we explore the performance of an SVM (Support Vector Machine) model. We evaluate the SVM model and visualize the predicted vs. actual average scores using a scatter plot.

Finally, we implement a Gradient Boosting Regressor model and assess its performance using MSE and MAE. We also visualize the predicted vs. actual average scores for the Gradient Boosting model.

## Conclusion

In this capstone project, we analyzed a dataset of students' scores and built machine learning models to predict their average scores. Through exploratory data analysis and visualization, we gained insights into the distribution of scores and identified factors that influence students' performance. The machine learning models provided predictions for average scores, with varying degrees of accuracy. Overall, this project highlights the potential of data analysis and machine learning in understanding student performance and guiding educational interventions.

Below is a link to my Linked In.
[Linkedin Link](https://www.linkedin.com/in/see-jun-wong-b33922263/)
---
