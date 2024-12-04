### Objective: Classification for Wine Quality (Binary Classification)

This project implements classification techniques using two different models: 

**Random Forest** and **XGBoost** <br> 
The workflow includes data preprocessing, model training, <br>
hyperparameter optimization, evaluation, and visualization of the results.

#### Steps
1: Data Exploration and Preprocessing <br>
2: Model Training with Random Forest and XGBoost <br>
3: Evaluation Metrics and Visualization <br>
4: Deliverables <br>
<br>
<br>

1. **Data Preparation**
    - Load the wine quality dataset.
    - Analyze statistics and correlations of features.
    - Transform multiple classifications of wine quality
     to binary classification.
    - Standard Scaling ($\mu$ = 0, $\sigma$ = 1)

2. **Model Training**
    - Split the dataset into training and testing sets.
    - Train with Random Forest (w/o grid search) 
    and XGBoost with optuna.

3. **Evaluation Metrics and Visualization**
    - Evaluate precision, recall, and F1 scores
    - Visualized ROC curve, confusion matrix, and
    feature importance 


4. **Deliverables**
    - RF, and XGBoost trained models were saved to 'pkl'
    files, and reproducing test results