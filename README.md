##### 🩺 Diabetes Prediction using Machine Learning

##### A Machine Learning Classification Project that predicts whether a patient is diabetic or non-diabetic based on diagnostic medical measurements. This project uses a Support Vector Machine (SVM) classifier with a linear kernel to predict diabetes outcomes.

##### 📡 Project Overview
##### The goal of this project is to classify patients based on medical features:
 ##### 0 → Non-Diabetic
##### 1 → Diabetic
##### The dataset contains 768 patient records, each with 8 medical features, including glucose level, BMI, blood pressure, age, and insulin levels.

##### 📂 Dataset Information
##### Source: Kaggle Diabetic Dataset
##### Total Samples: 768
##### Features (X): 8 medical measurements
##### Target Label (y): Outcome
##### 0 → Non-Diabetic
##### 1 → Diabetic

##### 🌟 Features
##### Pregnancies – Number of times pregnant
##### Glucose – Plasma glucose concentration
##### BloodPressure – Diastolic blood pressure (mm Hg)
##### SkinThickness – Triceps skin fold thickness (mm)
##### Insulin – 2-Hour serum insulin (mu U/ml)
##### BMI – Body mass index (weight in kg/(height in m)^2)
##### DiabetesPedigreeFunction – Function measuring diabetes risk
##### Age – Patient age in years

##### Machine Learning Model: Support Vector Machine (SVM) with linear kernel
##### Output: Predicts whether a patient is diabetic (1) or non-diabetic (0)
##### 📥 Data Loading & Exploration
##### Dataset loaded from CSV using panda
##### Explored dataset with .describe(), .value_counts(), and .groupby() to analyze patterns.

##### 🔧 Data Processing
##### Feature-Label Separation:
##### The dataset was split into features (X) and target labels (y).
##### Features (X): All columns representing patient medical measurements
##### Target Labels (y): The Outcome column, which indicates whether a patient is non-diabetic (0) or diabetic (1).


##### Standardization:
##### All feature values were scaled using StandardScaler to bring them to a common range.
##### Train-Test Split:
##### The dataset was split into training and testing sets:
##### Training set: 614 samples
##### Testing set: 154 samples

##### 🤖 Model Training
##### Algorithm Used: Support Vector Machine (SVM) with a linear kernel
##### The SVM classifier was trained on the training dataset.
##### The model tries to find the optimal hyperplane that separates diabetic and non-diabetic patients based on the features.
##### SVM is chosen because it is effective for binary classification problems and works well with standardized feature data.

##### 📊 Model Accuracy
##### Training Accuracy: 78.66%
##### Testing Accuracy: 77.27%

##### Model Evaluation
##### Confusion Matrix – Training Data:
##### Shows how many training samples were correctly or incorrectly classified.


##### Confusion Matrix – Testing Data:
##### Similar visualization for the testing set, allowing evaluation of model performance on unseen data.
##### Classification Report – Training Data:
##### Precision: Percentage of predicted positives that are actually positive
##### Recall: Percentage of actual positives that are correctly predicted
##### F1-Score: Harmonic mean of precision and recall


##### 🛠️ Technologies Used
##### Python
##### NumPy
##### Pandas
##### Matplotlib & Seaborn
##### Scikit-Learn (SVM, StandardScaler, Train-Test Split)
##### Jupyter Notebook




