# breast_cancer_pred
data source: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29

# Introduction
This project is building upon a project I did in college, Empirical Comparison of Binary Classifiers. I have learned so much since finsihing the first iteration of this project and I wanted to apply my new knowledge to perform a deeper dive into classification algortithms. 
<br><br>
In this project I compare three different classification algorithms (Logistic Regression, K-Nearest Neighbors, and Random Forest) on a breast cancer dataset form the UCI repository with the goal of classifying tumors as benign or malignant. For this problem, I chose to use recall/sensitivity as the main performance metric because presenting a false negative has much more serious consequences than presenting a false positive.
<br><br>
# Findings
After tuning hyperparameters, the random forest classifier performed the best on the test set with a sensitivity score of 94.83%. However, I also iterated through different thresholds for the logistic regression classifier and found that lowering the threshold from 0.5 to 0.1 resulted in a sensitivity score of 100% without sacrificing specificity. This finding may be a result of overfitting. 
