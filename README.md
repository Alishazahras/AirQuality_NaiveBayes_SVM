# Air Quality Analysis in Yogyakarta during the COVID-19 Pandemic Using Naive Bayes and Support Vector Machine
Air quality is crucial for human health and the environment, as clean air reduces the risk of disease. During the Covid-19 pandemic, air quality worsened in many cities, including Yogyakarta, due to increased pollution levels. This study applied **Naive Bayes** and **Support Vector Machine (SVM)** algorithms to predict whether air quality in Yogyakarta is good or bad, based on various air components. The results showed that **SVM** was the best model, achieving an accuracy of 1.00 on the training data and 0.95 on the testing data, based on the f1-score calculation from the testing dataset.

## Dataset Overview
The dataset used in this study contains measurements of various air quality components in Yogyakarta, collected before and during the Covid-19 pandemic. The dataset includes:
- PM2.5 and PM10 levels: Particulate matter concentrations.
- CO, SO2, NO2 levels: Concentration of carbon monoxide, sulfur dioxide, and nitrogen dioxide.
- Air Quality Label: Whether the air quality is classified as "Good" or "Bad.

## Objectives
1. To analyze the air quality in Yogyakarta during the pandemic.
2. To compare the performance of Naive Bayes and Support Vector Machine (SVM) for predicting air quality.
3. To identify the most effective model for air quality prediction based on accuracy and f1-score.

## Methods
Two classification methods were applied to the dataset:
1. **Naive Bayes Classifier:** A probabilistic classifier that applies Bayes' Theorem with strong (naive) independence assumptions between the features. This method is known for its simplicity and performance on smaller datasets.
2. **Support Vector Machine (SVM):** A powerful classification method that finds the optimal hyperplane to separate classes in a high-dimensional space. It is known for handling complex and non-linear relationships in the data.

## Model Evaluation Metrics
1. **Accuracy:** The proportion of correct predictions out of all predictions made.
2. **Precision:** The proportion of positive predictions that are actually correct (how many of the predicted "bad air quality" labels are accurate).
3. **Recall:** The proportion of actual positive instances that are correctly identified (how many of the actual "bad air quality" cases were correctly predicted).
4. **F1-Score:** The harmonic mean of precision and recall, balancing both metrics.

## Results
1. **Naive Bayes** showed moderate performance on both training and testing datasets, with an accuracy of 0.85 and an f1-score of 0.82 on the testing data.
2. **Support Vector Machine (SVM)** significantly outperformed Naive Bayes, with a training accuracy of 1.00 and a testing accuracy of 0.95. The f1-score on the testing dataset was the highest among the models, making SVM the preferred model for this task.

## Conclusion
Based on the results, Support Vector Machine (SVM) is the best model for predicting air quality in Yogyakarta, achieving near-perfect performance in both training and testing phases. Future work can focus on refining the model by incorporating more features or using real-time data to improve prediction accuracy.

## Technical Requirements
The following Python libraries are required to run the project:

- `pandas `
- `numpy `
- `sklearn `
- `matplotlib`
- `seaborn`

## How to Run the Project
1. **Preprocessing:** Load the dataset, clean missing values, and normalize the features.Preprocessing: Load the dataset, clean missing values, and normalize the features.
2. **Train Models:** Train both Naive Bayes and SVM models on the training dataset.
3. **Evaluate Models:** Evaluate both models using accuracy and f1-score on the testing dataset.
4. **Predict:** Use the best-performing model (SVM) to predict the air quality on new data.

## Contributors
2501971742 - Alisha Zahra Saadiya

2540124021 - Edrick Setiawan

2501962340 - Gregory Nicolla
