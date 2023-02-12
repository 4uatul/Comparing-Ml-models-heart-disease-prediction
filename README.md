# Heart Disease Prediction Model Comparison
This repository contains code and data for comparing different machine learning models for predicting heart disease. The models were trained and evaluated on a dataset of patients with various health metrics and symptoms.

## Dataset
The dataset used for training and evaluation can be found in the data directory. It contains records for 304 patients, with 14 features including age, sex, blood pressure, cholesterol levels, and symptoms like chest pain and shortness of breath. The target variable is a binary classification of whether or not the patient has heart disease.

## Models
I compared six different machine learning models for predicting heart disease:

- Linear Regression
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machines (SVM) 


I trained and evaluated each model using the same dataset and the same evaluation metric, accuracy.

## Results
The accuracy values for each model are as follows:

- Linear Regression: 0.55
- K-Nearest Neighbors (KNN): 0.92
- Logistic Regression: 0.86
- Decision Tree: 0.86
- Random Forest: 0.91
- Support Vector Machines (SVM): 0.88  


Based on these results, the KNN and Random Forest models appear to be the most accurate for predicting heart disease.                   


However, it's important to note that accuracy is just one metric for evaluating model performance, and other factors like precision, recall, and F1 score may be important as well depending on the specific use case.

## Code
The code for training and evaluating the models can be found in the directory. I used Python and scikit-learn to build and train the models, and used Matplotlib for visualizing the results.

## Future Work
While these results are promising, there is still more work to be done to improve the accuracy and robustness of the heart disease prediction models. Some possible areas for future work include:

- Experimenting with different feature engineering techniques and feature selection methods to see if they can improve the accuracy of the models.
- Trying out different machine learning algorithms, such as neural networks or gradient boosting, to see if they can outperform the current models.
- Collecting more data and exploring different data sources to see if the models can be improved with more diverse and representative data.
## Conclusion
In conclusion, this repository provides a comparison of six different machine learning models for predicting heart disease based on accuracy. The results suggest that the KNN and Random Forest models are the most accurate for this task, but more analysis and evaluation would be needed to determine which model(s) would be most appropriate for a specific use case.
