# Student-Placement-Calculator

Predictions for Student Placement

I created a model that would help University XYZ determine which students should be placed in their business program. Each students' numerical statistics was used as data to predict where each student should be placed. After reviewing the correlation matrix, I saw some data points that correlated heavy with the placement of students. Those were the data points I had decided to focus on.

I experimented with multiple models and the logistic regression model with a l1 penalty was the most accurate with the smallest calculable error. This model had the highest testing accuracy over all the other models and it was the least overfit. furthermore, after reviewing the confusion matrix and the classification report, this model had the fewest false positives and it had clearly defined classes after reviewing the ROC AUC.

University XYZ received the model and deployed it successfully. Contract Complete. Closing out
