# Titanic-Survival-Analysis---Random-Forest
This repository contains a comprehensive analysis of the Titanic dataset, exploring factors that influenced the survival of passengers aboard the ill-fated voyage. 
Using data science techniques, we identify trends, relationships, and insights.

# Table of Contents
Introduction
Dataset Description
Objective
Installation and Requirements
Methodology
Results
Conclusion
Acknowledgments

## Introduction
The Titanic disaster is one of the most infamous tragedies in maritime history. This project uses the Titanic dataset from Kaggle to perform exploratory data analysis and build predictive models to understand the factors influencing passenger survival.

## Dataset Description
The dataset includes information about passengers such as:

PassengerId: Unique identifier for each passenger.

Survived: Survival status (0 = No, 1 = Yes). 

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).

Name: Passenger name.

Sex: Gender of the passenger.

Age: Age in years.

SibSp: Number of siblings/spouses aboard.

Parch: Number of parents/children aboard.

Ticket: Ticket number.

Fare: Passenger fare.

Cabin: Cabin number.

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

Objective
The primary goals of this analysis are:

## Exploratory Data Analysis (EDA): Discover patterns and trends in the data.
Data Visualization: Create visual representations of key insights.
Model Building: Build and evaluate predictive models to determine survival likelihood.
Insights: Derive actionable insights into survival factors.
Installation and Requirements
Clone this repository:
bash

## Data Cleaning:
Handle missing values for Age, Cabin, and Embarked.
Convert categorical data into numerical format.
## Exploratory Data Analysis:

Visualize survival rates by gender, class, and age group.
Analyze the influence of fare and embarkation port.
Feature Engineering:

Create new features such as family size and title extraction.
Scale numerical features for model input.
Model Building:

Implement and evaluate models (Logistic Regression, Random Forest, Gradient Boosting).
Compare performance metrics like accuracy, precision, recall, and F1-score.
## Results
Key findings from the analysis:

Gender: Females had a significantly higher survival rate compared to males.

Class: Passengers in first class were more likely to survive than those in second or third class.

Age: Children had a higher survival rate compared to adults.

Fare: Higher fares were positively correlated with survival.

Predictive models achieved the following metrics:

## Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	79.0%	76.2%	71.8%	73.9%
Random Forest	81.4%	80.1%	76.3%	78.1%
Gradient Boosting	83.2%	82.5%	78.9%	80.6%

## Conclusion
The analysis highlights critical factors that influenced survival on the Titanic. The project demonstrates the use of data science techniques to analyze real-world datasets and build effective predictive models.

## Acknowledgments
The Titanic dataset provided by Kaggle.
Open-source libraries and tools that made this project possible.
