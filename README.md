# Machine Learning Classification Tasks

This repository contains four machine learning classification tasks implemented using Python and scikit-learn/XGBoost.

The notebooks were created and executed using Google Colab.

## Tasks

### Task 1 — Random Forest Classifier

**Objective:**  
Predict whether a tumor is malignant or benign using the Breast Cancer dataset from scikit-learn.

**Model:**
- Random Forest Classifier

**Evaluation metrics:**
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- ROC-AUC score

[Open Task 1 — Random Forest](./Task_1_Random_Forest.ipynb)

---

### Task 2 — Logistic Regression

**Objective:**  
Predict whether a patient has diabetes (1) or does not have diabetes (0) using the Pima Indians Diabetes Dataset.

**Steps performed:**
- Load the dataset into a pandas DataFrame
- Assign appropriate column names
- Check for missing and zero values
- Split the dataset into 80% training and 20% testing data
- Apply feature scaling
- Train a Logistic Regression model
- Evaluate the model
- Interpret model coefficients

**Evaluation metrics:**
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- ROC-AUC score

[Open Task 2 — Logistic Regression](./Task_2_Logistic_Regression.ipynb)

---

### Task 3 — XGBoost Classifier

**Objective:**  
Predict whether a passenger survived the Titanic disaster.

**Model:**
- XGBoost Classifier

**Steps performed:**
- Load the dataset into a pandas DataFrame
- Assign appropriate column names
- Check for missing and zero values
- Split the dataset into 80% training and 20% testing data
- Apply feature scaling
- Train an XGBoost model with specified parameters
- Evaluate the model
- Interpret the model's features

**Evaluation metrics:**
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- ROC-AUC score

[Open Task 3 — XGBoost](./Task_3_XGBoost.ipynb)

---

### Task 4 — Decision Tree Classifier

**Objective:**  
Predict whether a patient has diabetes (0 = No, 1 = Yes) using the Pima Indians Diabetes Dataset.

**Models:**
- Decision Tree Classifier
- Decision Tree Classifier with `max_depth=3`

**Steps performed:**
- Load the dataset into a pandas DataFrame
- Assign appropriate column names
- Check for missing and unrealistic zero values
- Handle unrealistic zero values
- Split the dataset into 80% training and 20% testing data
- Use `random_state=42`
- Define features and target variable
- Train a Decision Tree Classifier
- Evaluate the model
- Train a restricted Decision Tree with `max_depth=3`
- Compare both models
- Extract and display feature importance

**Evaluation metrics:**
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

[Open Task 4 — Decision Tree](./Task_4_Decision_Tree.ipynb)

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- XGBoost

## Datasets

| Task | Dataset | Model |
|------|---------|-------|
| Task 1 | Breast Cancer Dataset | Random Forest |
| Task 2 | Pima Indians Diabetes Dataset | Logistic Regression |
| Task 3 | Titanic Dataset | XGBoost |
| Task 4 | Pima Indians Diabetes Dataset | Decision Tree |

## Repository Structure

```text
machine-learning-tasks/
│
├── Task_1_Random_Forest.ipynb
├── Task_2_Logistic_Regression.ipynb
├── Task_3_XGBoost.ipynb
├── Task_4_Decision_Tree.ipynb
└── README.md
