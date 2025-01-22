
# Assignment 1
In this assignment, you’ll delve into the intricacies of real-world data, employing classifiers such as decision trees and KNN
from scikit-learn to gauge the lending risk. The objective here is to familiarize you with the scikit-learn API. By the end, you’ll
be adept at exploring fundamental statistics, constructing classification models, managing train/validation data divisions,
and assessing the outcomes.

1. Explore data statistics (6 points).
    (a) Calculate the average FICO credit score for customers who meet (credit.policy = 1) and don’t meet (credit.policy = 0) the credit underwriting criteria.
    (b) Visualize the distribution of FICO scores for those who have and haven’t fully paid their loans with two separate histograms in a single plot.
    (c) Calculate the correlation between interest rate and FICO score and explain what it implies.
    (d) Visualize the relationship between FICO score and interest rate using a scatter plot and compare it with your conclusion drawn from the last question.
    (e) What’s the average interest rate based on the purpose of the loan?
    (f) Is there a significant difference in the distribution of FICO scores between customers who fully paid their loans and those who didn’t? (Hint: Visualize using a boxplot)

2. Prepare the dataset for model training (4 points). 
    1) convert categorical variables (e.g., purpose) into dummy variables; 
    2) drop the category reference; 
    3) show the first 5 rows after preprocessing; 
    4) Split the data into training and test sets (70% training, 30% test), and show the sizes of training and testing data.

3. Construct a decision tree (4 points). 
    1) Train a decision tree classification model using the Gini criterion and show its accuracy. 
    2) Train a decision tree classification model using the Entropy criterion and show its accuracy. 
    3) Which decision tree model (Gini or Entropy) performs better on the test set?

4. Build a KNN (3 points). 
    1) Train a K-Nearest Neighbors (KNN) classifier with k = 5 and show its accuracy. 
    2) Train a K-Nearest Neighbors (KNN) classifier with k = 3 and show its accuracy. 
    3) Which K-Nearest Neighbors model (k = 3 or k = 5) performs better on the test set?

5. Perform evaluation (3 points). 
    1) Evaluate the performance of the decision tree (using Entropy) and KNN (k = 5) models using the F1-score. 
    2) Calculate the precision and recall for the decision tree (using Entropy) model. 
    3) Calculate the ROC-AUC score for both the decision tree (using Entropy) and KNN (k = 5) models.

