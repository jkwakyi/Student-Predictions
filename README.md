# Student-Predictions

Predictions for Student Placement

I wanted to create a model that would help university XYZ determine which students should be placed in their business program. I used each students numerical statistics as the data necessary to predict where each student would be placed. After reviewing the correlation matrix, I saw some data points that correlated heavy with the placement of students. Those were the data points I had decided to focus on.

I experimented with multiple models but the concessus choice was the logistic regression model with a l1 penalty. This model had the highest testig accuracy over all the other models and it was the least overfit. futhermore, after reviewing the confusion matrix and the classification report, this model had the fewest false positives and it had clearly defined classes after reviewing the ROC AUC. 
