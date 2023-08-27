# HeartDisease-Analysis

This project focuses on predicting the risk of heart disease based on various medical attributes of patients. It involves exploratory data analysis, preprocessing, model training, and evaluation. Different machine learning models are employed to predict heart disease risk, and their performances are compared.

## Dataset

The dataset used in this project contains medical attributes of patients that can be potential indicators of heart disease risk. 

The attributes include age, sex, chest pain type, blood pressure, cholesterol level, fasting blood sugar, electrocardiogram results, maximum heart rate achieved, exercise-induced angina, and more.

## Exploratory Data Analysis

During the exploratory data analysis phase, the following steps were undertaken:

- Distribution analysis of key variables
- Correlation analysis to understand relationships between variables
- Visualization of variables' impact on heart disease risk

## Modeling

Different machine learning models were employed for heart disease prediction, including:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest

The models were trained, evaluated, and compared based on accuracy, F1-score, mean absolute error, mean squared error, and R2 score.

## Conclusion

From the exploratory data analysis, it was observed that factors such as maximum heart rate, ST depression during exercise, chest pain type, exercise-induced angina, and ST segment slope have a significant impact on heart disease risk. The SVM model outperformed other models, achieving an accuracy of 84%.

However, it's important to note that the accuracy of the model could potentially be improved by increasing the size of the dataset. The dataset used in this project was relatively small, which might have affected the model's generalization.

For future work, fine-tuning hyperparameters, exploring feature engineering techniques, and considering more complex models could lead to improved performance.

Feel free to explore the Jupyter Notebook for detailed analysis and code implementation.



