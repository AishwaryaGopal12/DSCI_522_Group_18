# DSCI_522_Group_18

## Proposal

The Census Income Dataset is created by Ronny Kohavi and Barry Becker, and sourced from the UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. This is a classification dataset and we will complete a classification task to predict whether or not a person can earn more than $50k/yr for this project. 

We plan to predict the income status (larger than 50k or not) based on the personal information included in the dataset. We will use the binary attribute "income" as our target, which includes two values: ">50K" and "<=50K". There are 14 explanatory variables in the dataset, 6 are numeric features and 8 are categorical features. Each row contains one observation with the 14 explanatory variables(personal information) and the relative income status. There are 48842 observations in the dataset.

For analyzing the dataset and solve our predictive problem, we plan to build a classification model by using `scikit-learn`. We will initially try to fit the model with Logistic Regression and also test different models to find the model with best accuracies.

## EDA


## Citation
Ron Kohavi, "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", Proceedings of the Second International Conference on Knowledge Discovery and Data Mining, 1996

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.
