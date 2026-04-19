# Lab 7 - Logistic Regression

## Overview
This repository contains the solution for Lab 7 of the ARTI308 - Machine Learning course. The project focuses on implementing a Logistic Regression model to predict whether a particular internet user will click on an advertisement on a company website based on their user features.

## Dataset
The project utilizes the `advertising.csv` dataset, which includes the following features:
* Daily Time Spent on Site: Consumer time on site in minutes
* Age: Customer age in years
* Area Income: Average Income of geographical area of consumer
* Daily Internet Usage: Average minutes a day consumer is on the internet
* Ad Topic Line: Headline of the advertisement
* City: City of consumer
* Male: Whether or not consumer was male (Binary)
* Country: Country of consumer
* Timestamp: Time at which consumer clicked on Ad or closed window
* Clicked on Ad: 0 or 1 indicated clicking on Ad (Target Variable)

## Technologies Used
* Python
* pandas (Data manipulation)
* numpy (Numerical computing)
* matplotlib & seaborn (Data visualization)
* scikit-learn (Machine learning model and evaluation)

## Project Structure
* `02-Logistic Regression Assignment.ipynb`: The primary Jupyter Notebook containing the data exploration, visualizations, model training, and evaluation.
* `advertising.csv`: The raw dataset used for the analysis.

## Methodology
1. **Exploratory Data Analysis (EDA):** Analyzed feature distributions and relationships using histograms, jointplots, and pairplots.
2. **Data Preprocessing:** Selected relevant features (`Daily Time Spent on Site`, `Age`, `Area Income`, `Daily Internet Usage`, `Male`) and split the data into training (67%) and testing (33%) sets.
3. **Model Training:** Initialized and trained a Logistic Regression classifier on the training data.
4. **Evaluation:** Generated predictions on the test set and evaluated performance using a classification report.

## Results
The Logistic Regression model achieved an overall accuracy of 91% on the testing data, demonstrating strong predictive capabilities for both classes (clicked vs. not clicked).
