# AReM-
A comprehensive Jupyter notebook demonstrating data manipulation, exploratory analysis, and visualization techniques using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. Ideal for exploring data insights, generating visual analytics, and enhancing your analytical programming skills.
## Author
Simran Kshirsagar  
MSc in Data Analytics, National College of Ireland  
Email: x23433132@student.ncirl.ie
## Project Overview
This project is all about working with time-series data to make predictions using machine learning. Time-series data is a set of values collected over time, like measurements from sensors or stock prices over days.
In this project, we have several files with time-series data. The process starts by dividing the data into smaller chunks, called segments. For each segment, we calculate useful statistics like the average, maximum, and minimum values. These statistics are like summaries of the data that help the machine learn patterns.
Once we have these summarized features, we use them to train and test machine learning models, which can make predictions or identify patterns in the data.
In short, this project takes raw time-series data, processes it into easy-to-understand summaries, and uses them to teach a computer to make smart predictions. It's a simple way to get started with machine learning using time-series data.
This project explores the use of machine learning to solve one real-world problems:
- Human Activity Recognition (HAR) – classifying physical movements using sensor data.
The objective is to preprocess data, extract meaningful features, train and evaluate classification models, and analyze their performance using visual and statistical metrics.
## Research Objectives
- Investigate how preprocessing impacts ML model outcomes.
- Apply classifiers like SVM, Logistic Regression, and Naive Bayes to:
  - Classify human activity (AReM)
- Use feature engineering to enhance model accuracy.
- Evaluate using Accuracy, ROC-AUC, Confusion Matrix, and other metrics.
## Datasets Used
### AReM Dataset (Activity Recognition)
- Contains measurements from multiple wearable sensors placed on the body.
- Used to detect and classify various human movements such as:
  - Walking
  - Standing
  - Sitting
  - bending
  - lying
  - cycling
- Preprocessed using feature extraction from time-series data windows.

