<p align="center">
  <img src="https://img.shields.io/badge/Python-Machine%20Learning-blue?style=for-the-badge&logo=python" alt="Python badge">
  <img src="https://img.shields.io/badge/scikit--learn-Classification-f7931e?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn badge">
  <img src="https://img.shields.io/badge/Focus-Mass%20Spectrometry-6f42c1?style=for-the-badge" alt="Mass spectrometry badge">
</p>

# Plant MS Classifier

A machine learning workflow for classifying plant-derived mass spectrometry data into natural product classes. This project applies supervised learning methods to spectral features in order to distinguish compounds belonging to categories such as alkaloids, flavonoids, and terpenoids. [web:11][web:12]

---

## Problem

Modern plant metabolomics experiments generate thousands of mass spectrometry features per sample, far more than can be efficiently interpreted by manual inspection alone. [web:11][web:13]  
A large fraction of peaks remain unlabeled or ambiguously annotated, which slows down biological interpretation, natural product discovery, and downstream cheminformatics. [web:12][web:18]  
In many workflows, grouping spectra into broad phytochemical classes (for example alkaloids, flavonoids, terpenoids) is still done with ad-hoc rules or expert curation, making it time‑intensive, subjective, and difficult to scale. [web:11][web:17]

## Why This Matters

Accurately assigning spectra to meaningful natural product classes provides a faster way to summarize complex datasets, prioritize interesting compounds, and connect chemical patterns to biological questions. [web:11][web:17]  
Computational classification approaches can reduce manual annotation burden, improve consistency between experiments, and serve as a foundation for more advanced metabolite identification and drug‑discovery pipelines. [web:12][web:18]

---

## Solution: Plant MS Classifier

Plant MS Classifier is a Python-based supervised learning pipeline that takes plant-derived mass spectral features as input and predicts their corresponding natural product class.  
The workflow encodes class labels, trains multiple models (Random Forest, Logistic Regression, and Support Vector Machine), and compares their performance using standard evaluation metrics and visual outputs. [web:16][web:19]

This project is designed as a reproducible, notebook-driven analysis that demonstrates how to move from raw spectral tables to interpretable classification results in a way that is transparent and easy to extend to new datasets. [web:16][web:19]

---

## Executive Summary

This project demonstrates a practical workflow for applying machine learning to mass spectrometry-based chemical classification.  
Using Python and scikit-learn, spectral data are preprocessed, encoded, split into training and test sets, and evaluated across multiple supervised classification models. [web:16][web:19]

The goal is not only to build a working classifier, but also to compare modeling approaches and interpret performance using standard evaluation metrics and visualization outputs.  
The resulting workflow showcases skills relevant to biomedical data analysis, computational chemistry, and analytical-method interpretation. [web:16]

---

## Key Outcomes

- Built a supervised machine learning pipeline for plant mass spectrometry classification.  
- Compared Random Forest, Logistic Regression, and Support Vector Machine models on the same spectral dataset.  
- Evaluated model performance using accuracy, class-wise precision, recall, F1-score, and confusion matrices.  
- Generated visualization outputs to support interpretation of model behavior and feature importance.  
- Structured the repository as a reproducible GitHub project suitable for technical portfolio review. [web:16][web:19]

---

## Scientific Context

Mass spectrometry is widely used for chemical profiling, metabolomics, and natural products research, particularly in plants. [web:11][web:15]  
However, untargeted experiments often produce high-dimensional data where most features are initially unidentified, creating a bottleneck for biological interpretation. [web:12][web:18]

Classifying spectra into broad phytochemical classes offers a middle ground between fully unidentified peaks and fully resolved structures: it enables faster exploratory analysis, comparison between samples or treatments, and prioritization of chemical families for follow-up work. [web:11][web:17]  
This project focuses on proof-of-concept classification of plant-derived spectra into major natural product classes, emphasizing the computational workflow rather than production-ready deployment. [web:12]

---

## Workflow

The project follows a standard supervised machine learning pipeline:

1. Load plant-derived spectral data from CSV format.  
2. Separate spectral features from class labels.  
3. Encode target classes for model training.  
4. Split the data into training and test sets.  
5. Train multiple classification models.  
6. Compare predictive performance across models.  
7. Visualize confusion matrix results, model comparison, and feature importance. [web:17]

---

## Models Evaluated

The following supervised learning models were used:

- Random Forest  
- Logistic Regression  
- Support Vector Machine (SVM)  

These models were selected to compare tree-based and linear/kernel-based approaches on the same spectral classification task, highlighting trade-offs in performance and interpretability. [web:16][web:19]

---

## Results

### Performance Summary

The workflow produces solid classification performance across the tested natural product classes, evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion matrix interpretation  

Because the project includes model comparison and visual outputs, the repository highlights not just a final score but the full evaluation process used to interpret model quality. [web:16][web:19]

---

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

---

## Visual Outputs

### Confusion matrix

![Confusion Matrix](./images/confusion_matrix.png)

### Model comparison

![Accuracy Bar Chart](./images/accuracy_bar_chart.png)

### Feature importance

![Feature Importance](./images/feature_importance.png)

---

## Technical Skills Demonstrated

- Python data analysis with pandas and NumPy  
- Supervised machine learning with scikit-learn  
- Classification workflow design and evaluation  
- Confusion matrix and performance metric interpretation  
- Scientific plotting with matplotlib and seaborn  
- Reproducible notebook-based project organization [web:16][web:19]

---

## Limitations

This project is a proof-of-concept classification workflow and should not be interpreted as a validated analytical platform for real-world phytochemical identification.  
Performance depends on dataset size, class balance, feature quality, and how closely the training data represent real experimental spectra. [web:12][web:18]

---

## Future Extensions

Potential next steps include:

- Expanding the dataset with additional spectra and classes  
- Testing more robust preprocessing and peak-binning strategies  
- Adding cross-validation and hyperparameter optimization  
- Integrating external metabolomics or natural products datasets  
- Converting the notebook into a reusable analysis script or lightweight application [web:17]

---

## Author

**Ava Richards**  
Biomedical science graduate interested in computational analysis, natural products research, and data-driven approaches to chemistry and biomedicine.
