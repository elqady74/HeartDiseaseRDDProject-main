🔍 Heart Disease Prediction using PySpark RDD
This project demonstrates how to use PySpark and RDDs (Resilient Distributed Datasets) to analyze and model heart disease prediction data. The pipeline includes data preprocessing, exploratory data analysis, and building a machine learning model using Logistic Regression from PySpark's MLlib.

📁 Dataset
The dataset used is based on the Cleveland Heart Disease dataset, which contains 14 clinical attributes including age, sex, chest pain type, cholesterol, heart rate, and more. The target variable indicates whether a patient has heart disease (1) or not (0).

📌 Key Steps
✅ Create a Spark session and load data using RDD

🔧 Parse and clean data (handle missing values, remove duplicates)

📊 Perform basic EDA including summary statistics and boxplot visualization

🧹 Remove records with null values to prepare for ML

💡 Convert to LabeledPoint format for MLlib

🤖 Train a Logistic Regression model

🎯 Evaluate model performance (accuracy, predictions)

👤 Allow user input for interactive heart disease prediction

📦 Technologies
PySpark (RDD, MLlib)

Python (Matplotlib for visualization)

Logistic Regression

📈 Output
Model accuracy on test set

Distribution of predicted vs actual labels

Interactive command-line prediction for new patient data

👨‍💻 Developed by [Ahmed Elqady](www.linkedin.com/in/ahmed-elkady-0180a7361)

