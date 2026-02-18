# ML-based-phishing-attack-detection
Based on the performance metrics of the models trained:
The Random Forest Classifier performed best with an accuracy of 0.9717.

Key Findings
Random Forest Classifier achieved an accuracy of 0.9717. Its classification report indicated strong performance for both classes, with high precision, recall, and f1-scores (around 0.97). The confusion matrix showed a clear separation of true positives and negatives.
Decision Tree Classifier achieved an accuracy of 0.9478. Its classification report showed balanced performance for both classes, with precision, recall, and f1-scores around 0.94-0.95.
K-Nearest Neighbors Classifier had the lowest accuracy among the three models, at 0.6051. Its classification report showed moderate precision, recall, and f1-scores (around 0.54-0.65), indicating a significantly weaker performance compared to the tree-based models.
The Random Forest Classifier is the best-performing model among the three evaluated, demonstrating superior accuracy and robust classification metrics.
Next Steps
The superior performance of the Random Forest Classifier suggests that ensemble methods are highly effective for this dataset, potentially capturing complex relationships better than single decision trees or proximity-based methods.
For future model development, it would be beneficial to further optimize the Random Forest Classifier (e.g., hyperparameter tuning) and explore other ensemble methods like Gradient Boosting to potentially achieve even higher accuracy.
