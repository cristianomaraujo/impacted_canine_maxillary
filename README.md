# Machine Learning-Based Prediction of Maxillary Canine Impaction

## Overview
Contained within this repository are the resources for a study focused on forecasting the impaction of palatally impacted maxillary canines using supervised machine learning techniques based on measurements of the dental arch and maxillary skeletal base.

## Dataset
The dataset encompasses tomographic scans of the maxilla and mandible from 138 patients. It comprises measurements such as inter-molar width, inter-premolar width, inter-pterygoid width, maxillary length, maxillary width, nasal cavity width, and nostril width, derived from Cone Beam Computed Tomography scans.

## Models
A variety of machine learning algorithms were employed to construct predictive models, including Adaboosting Classifier, Decision Tree, Gradient Boosting Classifier, K-Nearest Neighbors (KNN), Logistic Regression, Multi-Layer Perceptron Classifier (MLP), Random Forest Classifier, and Support Vector Machine (SVM).

## Evaluation
Models underwent evaluation using a 5-fold cross-validation technique. Metrics such as area under the curve (AUC), accuracy, recall, precision, and F1 Score were computed for each model, with ROC curves generated for visualization purposes.

## Results
The predictive model incorporated four variables (two dental and two skeletal), with inter-pterygoid width and nostril width demonstrating the most significant effects. The Gradient Boosting Classifier displayed the most favorable metrics, with AUC values ranging from 0.91 for test data to 0.90 for cross-validation. Notably, across all tested algorithms, the nostril width variable exhibited the highest importance.

## Conclusion
Leveraging dental arch and maxillary skeletal base measurements through supervised machine learning techniques presents a promising avenue for prognosticating maxillary canine impaction by palatally. This method can function as a supplementary tool in orthodontic planning, furnishing insights and clinical guidance to orthodontists for a more precise and personalized approach.
