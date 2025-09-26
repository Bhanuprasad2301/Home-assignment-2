Name: Bhanu prasad
id  : 700762758

1)Decision Tree Classifier
This code loads the Iris flower dataset and splits it into training (70%) and testing (30%) data.
It then trains Decision Tree models with different depths 1, 2, 3 and checks how accurate they are on both the training and testing sets.
The goal is to see how tree depth affects learning:
A shallow tree depth=1 may miss patterns 
A deeper tree depth=3 captures more patterns but may memorize the training data
By comparing training and testing accuracy, we find a good balance.


2) k-Nearest Neighbors (kNN) + Decision Boundary Visualization
This part again uses the Iris dataset, but only takes the first two features so it’s easier to plot
It trains kNN classifiers with different k values 1, 3, 5, 10, checks accuracy on train/test sets, and plots decision boundaries
This helps visualize how k affects the model
Smaller k like 1 creates very detailed boundaries 
Larger k smooths boundaries but can miss details 
It shows the trade-off between flexibility and generalization.


3) kNN Model Evaluation (Confusion Matrix & ROC Curves)
This section trains a kNN model with k=5 on the full dataset.
It then evaluates it by
Showing a confusion matrix how well it predicted each class
Printing a classification report with precision, recall, and F1 scores.
Plotting ROC curves with AUC scores to measure how confidently it separates classes.
This goes beyond just accuracy and shows where the model performs well, where it struggles, and how reliable its predictions are.

