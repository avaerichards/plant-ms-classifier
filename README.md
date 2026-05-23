# plant-ms-classifier
Machine learning project to classify plant-derived mass spectra into natural product classes using Python and scikit-learn.

## Goal
Explore whether machine learning can classify plant-derived mass spectra into natural product classes.

## Tools
- Python
- pandas
- scikit-learn
- matplotlib
- seaborn

- ## Workflow
- Load and clean the spectra data.
- Split the dataset into training and test sets.
- Train Random Forest, Logistic Regression, and SVM models.
- Compare accuracy and classification metrics.
- Visualize the confusion matrix and feature importance.

## Results

### Classification Report
Random Forest
              precision    recall  f1-score   support

    alkaloid       1.00      1.00      1.00        10
   flavonoid       1.00      1.00      1.00        10
   terpenoid       1.00      1.00      1.00        10

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

### Accuracy Comparison
![Accuracy Bar Chart](images/accuracy_bar_chart.png)

### Feature Importance
![Feature Importance](images/feature_importance.png)

## Conclusion
The models performed very well on this dataset, with strong classification results across all three classes.
