# Disease-prediction-model-
Project Title: Disease Predictor using Machine Learning
Objective:
The goal of this project is to build a machine learning model that predicts diseases based on a set of symptoms provided by the user. This project uses a dataset of symptoms and corresponding diseases to train and evaluate classification algorithms.

Project Description:
1. Data Collection and Preprocessing:

Dataset: The dataset used contains multiple records of diseases and up to 17 associated symptoms.
Loading and Inspection: The dataset is read using pandas, and basic inspection (e.g., .head()) is performed.
Unique Values Extraction:
A list of all unique diseases is extracted.
All unique symptoms across the dataset are identified.
Missing Value Handling:
Missing symptom values (NaN) are imputed using the mode of symptoms in each row, ensuring completeness without compromising data integrity.

2. Data Visualization:

Libraries: matplotlib.pyplot and seaborn are used.
Symptom vs Disease Plot: Scatter plots are generated to visualize the distribution of diseases across different symptoms, helping to understand potential patterns or associations.

3. Feature Engineering:

The symptom columns (Symptom_1 to Symptom_17) serve as input features (X), and the disease column serves as the target label (y).
Label Encoding: Since the dataset contains categorical data (textual symptom names), LabelEncoder is applied to convert them into numerical values, making them suitable for machine learning algorithms.

4. Modeling:

Train-Test Split: The dataset is split into training and testing sets with a test size of 21%.
Algorithms Implemented:
Naive Bayes (GaussianNB): A probabilistic classifier based on Bayes’ theorem is used as a baseline.
K-Nearest Neighbors (KNN): Also implemented (though not shown in the snippet, likely part of later cells), to compare performance with a non-parametric classifier.

Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score
