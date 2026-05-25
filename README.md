<p align="center">
  <img src="https://img.shields.io/badge/Python-Machine%20Learning-blue?style=for-the-badge&logo=python" alt="Python badge">
  <img src="https://img.shields.io/badge/scikit--learn-Classification-f7931e?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn badge">
  <img src="https://img.shields.io/badge/Focus-Mass%20Spectrometry-6f42c1?style=for-the-badge" alt="Mass spectrometry badge">
</p>

# Plant MS Classifier

A machine learning workflow for classifying plant-derived mass spectrometry data into natural product classes. This project applies supervised learning methods to spectral features in order to distinguish compounds belonging to categories such as alkaloids, flavonoids, and terpenoids.

## Executive Summary

This project demonstrates a practical workflow for applying machine learning to mass spectrometry-based chemical classification. Using Python and scikit-learn, spectral data were preprocessed, encoded, split into training and test sets, and evaluated across multiple supervised classification models.

The goal was not only to build a working classifier, but also to compare modeling approaches and interpret performance using standard evaluation metrics and visualization outputs. The resulting workflow reflects skills relevant to biomedical data analysis, computational chemistry, and analytical-method interpretation.

## Key Outcomes

- Built a supervised machine learning pipeline for plant mass spectrometry classification.
- Compared Random Forest, Logistic Regression, and Support Vector Machine models.
- Evaluated model performance using accuracy, class-wise precision, recall, F1-score, and confusion matrices.
- Generated visualization outputs to support interpretation of model behavior and feature importance.
- Structured the repository as a reproducible GitHub project for technical portfolio presentation.

## Scientific Context

Mass spectrometry is widely used for chemical profiling, metabolomics, and natural products research. Classifying spectra into meaningful phytochemical groups can support faster exploratory analysis, reduce manual interpretation burden, and provide a foundation for later cheminformatics or drug-discovery workflows.

This project focuses on proof-of-concept classification of plant-derived spectra into major natural product classes. It is designed as a computational analysis workflow rather than a production-ready identification platform.

## Workflow

The project follows a standard supervised machine learning pipeline:

1. Load plant-derived spectral data from CSV format.
2. Separate spectral features from class labels.
3. Encode target classes for model training.
4. Split the data into training and test sets.
5. Train multiple classification models.
6. Compare predictive performance across models.
7. Visualize confusion matrix results, model comparison, and feature importance.

## Models Evaluated

The following supervised learning models were used:

- Random Forest
- Logistic Regression
- Support Vector Machine (SVM)

These models were selected to compare tree-based and linear/kernel-based approaches on the same spectral classification task.

## Results

### Performance Summary

The final workflow produced strong classification performance across the tested natural product classes, with evaluation based on:

- accuracy
- precision
- recall
- F1-score
- confusion matrix interpretation

Because the project includes model comparison and visual outputs, the repository highlights not just a final score but the full evaluation process used to interpret model quality.

## Repository Structure

```text
plant-ms-classifier/
├── README.md
├── plant_ms_classifier.ipynb
├── data/
│   └── plant_spectra_dataset.csv
└── images/
    ├── confusion_matrix.png
    ├── accuracy_bar_chart.png
    └── feature_importance.png
```

## Visual Outputs

### Confusion matrix

![Confusion Matrix](./images/confusion_matrix.png.png)

### Model comparison

![Accuracy Bar Chart](./images/accuracy_bar_chart.png.png)

### Feature importance

![Feature Importance](./images/feature_importance.png.png)

## Technical Skills Demonstrated

- Python data analysis with pandas and NumPy
- Supervised machine learning with scikit-learn
- Classification workflow design and evaluation
- Confusion matrix and performance metric interpretation
- Scientific plotting with matplotlib and seaborn
- Reproducible notebook-based project organization

## Limitations

This project is a proof-of-concept classification workflow and should not be interpreted as a validated analytical platform for real-world phytochemical identification. Performance depends on dataset size, class balance, feature quality, and how closely the training data represent real experimental spectra.

## Future Extensions

Potential next steps include:

- expanding the dataset with additional spectra
- testing more robust preprocessing and peak-binning strategies
- adding cross-validation and hyperparameter optimization
- integrating external metabolomics or natural products datasets
- converting the notebook into a reusable analysis script or lightweight application

## Author

**Ava Richards**  
Biomedical science graduate interested in computational analysis, natural products research, and data-driven approaches to chemistry and biomedicine.
