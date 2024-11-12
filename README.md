# Earthquake-Prediction-and-Location-Classification-Project-using-ML
**This README provides an overview of the project. For more in-depth information, refer to the full project documentation available in this repository.**
## Project Overview
### The Earthquake Prediction and Location Classification project uses machine learning to forecast the timing and location of earthquakes in Turkey. With a historical dataset (1915-2023) containing earthquake occurrences, the project applies both regression and classification techniques to enhance disaster preparedness.
### Objectives
### 1.	Predict earthquake timing.
### 2.	Classify earthquake location.
### 3.	Optimize model performance for accuracy, precision, and recall.
## Methodology
### 1.	Data Preprocessing: Addressed missing values using mean imputation and formatted date and time features for analysis.
### 2.	Regression Models: Explored models (Linear, Decision Tree, Random Forest) with Random Forest yielding the best results for time prediction.
### 3.	Classification Models: Tested Random Forest, SVM, and Neural Networks across three configurations; Random Forest in the third configuration (Latitude, Longitude, Depth, Magnitude) achieved the highest accuracy (0.9965).
### 4.	Combined Model: Achieved high combined accuracy for time and location predictions (0.9963 and 0.9965, respectively).
## Key Results
### •	Regression Best Model: Random Forest (MAE: 1.7014, R²: 0.7622).
### •	Classification Best Model: Random Forest (Accuracy: 0.9965, Precision: 0.99648, Recall: 0.9965).
### •	Combined Model: Demonstrated robust accuracy for both temporal and spatial predictions.
## Conclusion
### Random Forest proved to be the optimal model for both tasks due to its accuracy and robustness. This project demonstrates the potential of machine learning for earthquake prediction, offering valuable insights for future disaster management.
