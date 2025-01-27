Diabetes Prediction Using Machine Learning
This project analyzes the Diabetes Dataset to predict the likelihood of diabetes in patients using machine learning models. The dataset contains medical diagnostic data such as glucose levels, BMI, insulin levels, and more.

Key Features:
Exploratory Data Analysis (EDA):

Summary statistics and null value checks.
Skewness analysis to handle zero and missing values effectively.
Heatmaps and boxplots to explore relationships between features and outcomes.

Data Preprocessing:
Handling missing values by replacing zeros with the mean of each column.
Standardizing numerical features for improved model performance.

Machine Learning Models:
Logistic Regression: Simple yet effective baseline model.
Support Vector Machine (SVM): Utilizes the RBF kernel for enhanced accuracy.
XGBoost Classifier: A high-performance gradient-boosting algorithm.

Performance Evaluation:
Accuracy, classification reports, and other metrics to assess model performance.
Dependencies:
Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

Future Goals:
In future i aim to include AUC-ROC metric evaluation also and involve Gan's or smote to balance the datasets and thus attain balanced datasets for proper classification metric scores  
