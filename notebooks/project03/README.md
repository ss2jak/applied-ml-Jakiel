Jakiel David
11-9-25

Project 3 obejective is to predict a Categorical Target and Evaluating Performance

We will:
1. Prepare the data
2. Train 3 models: Decision Tree, Support Vector Machine (SVM), and a Neural Net (NN)
3. Get model performance on train and test sets
4. Create appropriate graphs

Section 1. Load and Inspect the Data
Section 2. Data Exploration and Preparation
Section 3. Feature Selection and Justification
Section 4. Train a Classification Model (Decision Tree)
Section 5. Compare Alternative Models (SVC, NN)


| Model Type | Case | Features Used | Accuracy | Precision | Recall | F1-Score | Notes |
|------------|------|---------------|----------|-----------|--------|-----------|-------|
| Decision Tree | Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                   | Case 2 | age | 61% | 58% | 61% | 55% | - |
|                   | Case 3 | age + family_size | 59% | 57% | 59% | 57% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| SVM (RBF Kernel)| Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                    | Case 2 | age | 63% | 66% | 63% | x52% | - |
|                    | Case 3 | age + family_size | 63% | 66% | 63% | 52% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| Neural Network (MLP)| Case 3 | age + family_size | 66% | 65% | 66% | 63% | - |

