# English-Premier-League-Rankings-Prediction
Objective
The objective of this project is to predict the outcome of a game given any two teams in the Premier League. Using the results, predictions for the total points of each team and the rankings of the top 6 teams are outputted.

Methodology
The first step in the methodology is to reduce the number of covariates under investigation using feature selection. Using the mutual information approach, covariates that do not provide additional information are removed.

Two different classification methods and eighth different models are used to determine predictions of each game. For classification, the first classification method is binary: home win (1) or not (0). The second classification method uses a multiclassifier: home team wins (0), away team wins(1), or draw (2). Experiments are run using eighth different models: SVM, Random Forest, Logistic Regression, Naive Bayes, Neural Networks, AdaBoost, K-Nearest Neighbor, and QDA. 
For each model and classification method, the performance is measured using precision, recall, F-1 score, and MSE. Based on the predictions of the games for a given
season, the total point values predicted for each team is outputted. The average of all the models is used to then determine the average total points, and the rankings are determined in descending order.
