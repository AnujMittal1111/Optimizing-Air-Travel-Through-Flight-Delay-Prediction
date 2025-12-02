# Optimizing Air Travel Through Flight Delay Prediction

This project aims to predict flight departure delays across major US airports using machine learning models.  
The goal is to provide early delay warnings that help airlines and passengers make better scheduling decisions.

## Project Summary

- Processed over 1 million flight records across 14 major US airports.
- Carried out data cleaning, feature engineering, and exploratory data analysis.
- Trained and evaluated ensemble learning models including XGBoost and Gradient Boosting.
- Applied hyperparameter tuning and recursive feature selection to improve accuracy.
- Achieved 78 percent classification accuracy with improved prediction stability through cross-validation and bagging methods.

This repository includes the analysis notebook and project presentation.

## Repository Structure

23117025_Anuj_Mittal_Optimizing_AirTravel-checkpoint.ipynb   : Full analysis and model training notebook  
Deck_23117025.pdf                                            : Project presentation  
README.md                                                     : Project documentation  

## Tech Stack Used

### Languages and Tools
- Python  
- Jupyter Notebook  

### Libraries
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  

### Techniques
- Exploratory Data Analysis  
- Feature Engineering  
- Handling Missing Values  
- Ensemble Learning Models  
- Hyperparameter Tuning  
- Recursive Feature Selection (RFE)  
- Model Evaluation (Accuracy, Confusion Matrix, Cross-Validation)  

## Model Performance

- Achieved 78 percent classification accuracy on flight delay prediction.
- Ensemble models such as XGBoost delivered the most stable performance.
- Cross-validation and bagging improved robustness of predictions.

## Key Insights

- Weather conditions, airline type, and airport congestion significantly impact delay likelihood.
- Ensemble models outperform basic classifiers for complex real-world datasets.
- Effective feature engineering improves reliability in delay classification.

## How to Run

1. Install required libraries:

   pip install numpy pandas scikit-learn xgboost matplotlib seaborn

2. Open the notebook:

   23117025_Anuj_Mittal_Optimizing_AirTravel-checkpoint.ipynb

3. Run all cells sequentially to reproduce:
   - Data preprocessing  
   - Model training  
   - Evaluation metrics  

## Documentation

Refer to Deck_23117025.pdf for the complete project summary and visual explanation.

## Author

Anuj Mittal  
IIT Roorkee  
