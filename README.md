# 1. Business Understanding
---
- Knowing customer churn is essential for internet provider company for effectively prevent them using appropriate marketing initiative
- Internet provider company wants to give specific marketing initiative for preventing customer churn
- They want to spend this budget as efficient as possible

## 1.2 Business Questions
---
- How can internet provider company develop marketing effectiveness strategy to increase reduce 30% of churn?
- What marketing initiatives are suitable to reduce the 30% customer churn?
- How to prevent unnecessary budget allocation?

## 1.3 Modelling Task
---
- Output target: **customer status of churn (categorical)**

- The goal of this project is to predict whether a customer will churn or not based on various features.
Task: **Classification task**

- We need a model that can be easily interpreted so that we can understand how each feature contributes to the prediction. This can help us gain insights into the underlying factors that influence whether a customer will churn or not.
Model used: **Logistic regression**

- We will use ROC/AUC as our evaluation metric since we want it's not influeced by imbalance target and we need to measure threshold using ROC/AUC. **Evaluation metric: ROC/AUC & Recall**

# 2. Modelling Workflow
---
## **Machine Learning Workflow** (Simplified)

### 1. <font color='blue'> Importing Data to Python:
    * Data description, Importing data, Data splitting
    
### 2. <font color='blue'> Exploratory Data Analysis:
    *Descriptive statistic, Missing value checking, Data exploration
    
### 3. <font color='blue'> Prepocessing:
    * Missing value handling, Outliers handling

### 4. <font color='blue'> Modelling:
    * Model fitting, Evaluation
    
### 5. <font color='blue'> Lift Chart & Interpretation:
    * Targetting customer churn, Coeficient interpretation
