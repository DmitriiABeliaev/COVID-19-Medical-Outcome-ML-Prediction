# COVID-19 Medical Outcome Prediction

A machine learning project aimed at predicting COVID-19 patient outcomes using cleaned and preprocessed global COVID-19 data. Developed as part of CMPT 459 - Data Mining and Data Warehousing.

## Problem Statement
Analyzed incomplete COVID-19 datasets across continents to develop predictive models. Addressed major data inconsistencies, particularly from underrepresented regions like Africa and Asia.

## Data Preprocessing
- **Data Cleaning:** Standardized country names, handled missing values, corrected invalid entries.
- **Feature Engineering:** Created meaningful features such as expected mortality rate.
- **Dataset Merging:** Combined location and patient outcome datasets, aggregating duplicates.
- **Class Balancing:** Applied SMOTENC oversampling to address class imbalance in target variables.

Ex: Before and After the Class Balancing

![Image](https://github.com/user-attachments/assets/c49636e3-4696-4d97-b7a1-0441731c4050)

## Model Development
Developed and evaluated four machine learning models:
- **Logistic Regression**
- **K-Nearest Neighbors**
- **Gradient Boosting Classifier**
- **Random Forest** (Best performer)

**Hyperparameter Tuning**:  
- GridSearchCV for Logistic Regression, KNN, Gradient Boosting.
- RandomizedSearchCV for Random Forest.

![Image](https://github.com/user-attachments/assets/f612f9f3-ee8e-45a8-ba0e-673d6937e34a)

**Cross-validation:**  
- 5-Fold Cross Validation to assess model generalization and detect overfitting.

## Results
- Random Forest achieved the best F1-scores and accuracy with minimal overfitting.
- Class distributions were balanced post-SMOTENC application.
- Models demonstrated robust performance even on unseen (unlabeled) data.
- For more details of our work process and finding check report.pdf

## Team Contributions
- Dmitrii Beliaev
- Tristian Labanowich
- Long Duong
- Manvir Singh Heer
