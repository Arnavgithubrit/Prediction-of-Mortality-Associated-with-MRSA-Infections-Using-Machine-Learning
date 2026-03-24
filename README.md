**Prediction-of-Mortality-Associated-with-MRSA-Infections-Using-Machine-Learning**

**🎯Overview**
This project develops a machine learning–based classification pipeline to predict mortality outcomes in patients infected with Methicillin-Resistant Staphylococcus aureus (MRSA). The study applies multiple supervised learning algorithms and evaluation metrics to identify the best-performing predictive model and interpret clinically relevant features associated with mortality risk

**📌The workflow follows a structured machine learning pipeline including**

✅Data preprocessing
✅Feature engineering
✅Train–test splitting
✅Stratified 5-fold cross-validation
✅Multi-model comparison
✅ROC–AUC and Precision–Recall curve analysis
✅Confusion matrix evaluation (Best performing model)
✅Calibration analysis

**📌Dataset Description**

The dataset contains clinical information from 83 pediatric patients diagnosed with MRSA infection. Each row represents one patient record and includes:

✅Demographic features (age group, gender)
✅Infection origin (community-acquired vs hospital-acquired MRSA)
✅Clinical severity indicators (septic shock, PICU admission, ventilator support)
✅Laboratory findings (anemia, neutrophilia, thrombocytopenia)
✅Infection site (pneumonia, septicemia, meningitis, SSTI, bone & joint infection)
✅Antibiotic treatment variables

**📌Target Variable:**

MORTALITY (YES = 1, NO = 0)

**🔬Machine Learning Pipeline**

**1️⃣ Data Cleaning**
Handling missing values
Column name standardization
Binary encoding verification

**2️⃣ Feature Engineering**
Feature–target separation
Data type verification
Preparation for classification modeling

**3️⃣ Train–Test Split**
Dataset split into:

Training dataset
Testing dataset

**4️⃣Cross-Validation Strategy**
Stratified 5-fold cross-validation was used to ensure robust performance estimation across models.

**📌The following classification algorithms were evaluated**
✅Logistic Regression
✅Random Forest
✅K-Nearest Neighbors (KNN)
✅Support Vector Machine (SVM)
✅Decision Tree
✅XGBoost

**📈Model performance was assessed using**
✅Accuracy
✅Precision
✅Recall
✅F1-score
✅ROC–AUC Score

**📌Results Summary**
Among all tested classifiers, XGBoost demonstrated the strongest predictive performance, achieving:

✅Highest ROC–AUC score
✅Best balance between sensitivity and specificity
✅Improved mortality prediction capability


