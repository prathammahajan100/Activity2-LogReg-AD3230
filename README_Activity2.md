# Activity 2: Binary Classification with Logistic Regression (Breast Tumour Screening)

**Course:** Regression and Classification Algorithms (T.Y. B.Tech AI & DS, Sem V), CIE 2, Unit II

**Name / Roll No.:** Pratham Mahajan, Roll No. AD3230

**GitHub:** [complexiota](https://github.com/complexiota)

## Activity
Build a Logistic Regression model for a two-class problem, convert probabilities into class labels, evaluate with a confusion matrix, accuracy, precision, recall, specificity, F1-score and ROC-AUC, compare thresholds 0.3, 0.5 and 0.7, and recommend a threshold.

## Dataset
Breast Cancer Wisconsin (Diagnostic), via `sklearn.datasets.load_breast_cancer`. Source: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
Classes: 1 = malignant (positive class), 0 = benign. Features used: mean radius, mean texture, mean smoothness, mean compactness, mean concave points, mean symmetry.

## Work completed
- Data inspection, class distribution plot, class balance check
- Feature scaling (fit on train only) and stratified 80:20 split (seed 42)
- Sigmoid plot and explanation, Logistic Regression training, coefficient interpretation
- Probabilities, labels, threshold effects, confusion matrix, classification report
- Majority-class baseline, ROC curve with AUC, precision-recall curve
- Threshold comparison table (0.3, 0.5, 0.7) with recommendation and justification
- Train vs test comparison, decision-behaviour plot, new prediction, limitations and decision log

## Key results
(Fill in after running: test accuracy, precision, recall, specificity, F1, ROC-AUC, recommended threshold and why.)

## Files
- `Activity2_Binary_Classification_Logistic_Regression.ipynb`: full notebook
