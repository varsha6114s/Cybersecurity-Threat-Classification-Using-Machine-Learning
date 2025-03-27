# Cybersecurity-Threat-Classification-Using-Machine-Learning
## Project Overview
Machine learning system for classifying network threats using synthetic cybersecurity data.

## Requirements
- Python 3.7+
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Installation

pip install -r requirements.txt
Usage
1.	Run the Jupyter notebook Cyber_Threat_Classifier.ipynb
2.	The notebook will:
o	Generate synthetic cybersecurity data
o	Preprocess and analyze the data
o	Train and evaluate ML models
o	Display performance metrics and visualizations
Models Implemented
•	Random Forest Classifier
•	Support Vector Machine (SVM)
Results
•	Random Forest Accuracy: 75%
•	SVM Accuracy: 70%
File Structure
•	Cyber_Threat_Classifier.ipynb: Main notebook
•	synthetic_cyber_threats.csv: Generated dataset
•	report.pdf: Analysis summary
Future Improvements
•	Incorporate real-world cybersecurity datasets
•	Experiment with deep learning approaches
•	Add feature importance analysis

## Objective:
Develop a machine learning system to classify network threats using synthetic cybersecurity data.
Approach:
1.	Data Preparation:
o	Generated synthetic dataset with 100 samples and 5 threat classes
o	Engineered features representing network traffic patterns
o	Handled missing values with median imputation
2.	Feature Engineering:
o	Selected relevant network traffic features
o	Applied RobustScaler for normalization
o	Encoded target labels
3.	Model Training:
o	Random Forest (n_estimators=100, balanced class weights)
o	SVM (RBF kernel, balanced class weights)
o	80-20 train-test split
4.	Evaluation Metrics:
o	Random Forest Accuracy: 75%
o	SVM Accuracy: 70%
o	Detailed classification reports for each model

## Key Findings:
•	Random Forest performed slightly better than SVM
•	Model struggles most with rare attack types (DDoS, SQL Injection)
•	Best at detecting BruteForce and XSS attacks

## Conclusion:
The system demonstrates effective threat classification capabilities using synthetic data. Future improvements could include:
•	Larger, more diverse dataset
•	Neural network architectures
•	Feature importance analysis

## Visualizations Included:
1.	Model accuracy comparison
2.	Confusion matrix for best-performing model
