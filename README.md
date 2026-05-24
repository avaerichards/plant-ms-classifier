# Plant MS Classifier

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python badge">
  <img src="https://img.shields.io/badge/scikit--learn-Machine%20Learning-f7931e?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn badge">
  <img src="https://img.shields.io/badge/Project-Biomedical%20Data%20Science-0a7b83?style=for-the-badge" alt="Project badge">
</p>

Machine learning workflow for classifying plant-derived mass spectrometry data into natural product classes using Python and scikit-learn.

## Overview

This project applies supervised machine learning to plant mass spectrometry data in order to classify samples into natural product classes such as alkaloids, flavonoids, and terpenoids. It was designed as a portfolio project at the intersection of biochemistry, analytical chemistry, and data science.

The goal of this project is to demonstrate a complete scientific machine learning workflow, including data loading, preprocessing, model training, evaluation, and interpretation of results.

## Scientific Motivation

Natural products remain an important area of drug discovery and chemical biology. Classifying plant-derived mass spectrometry data can help organize complex chemical information and support early-stage analysis of biologically relevant compounds.

## Features

- Classification of plant-derived mass spectra into natural product classes
- Model development using Python and scikit-learn
- Performance evaluation with classification metrics and a confusion matrix
- Visual comparison of model accuracy
- Feature importance analysis for model interpretation

## Project Structure

```text
plant-ms-classifier/
├── images/
│   ├── accuracy_bar_chart.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
├── plant_ms_classifier.ipynb
└── README.md
```

## Tools and Libraries

- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn

## Workflow

1. Load the plant mass spectrometry dataset.
2. Separate features and class labels.
3. Encode labels and split data into training and test sets.
4. Train machine learning models using scikit-learn.
5. Evaluate model performance with classification metrics.
6. Visualize results using a confusion matrix, model comparison chart, and feature importance plot.

## Results

### Classification Summary

The models showed strong classification performance across the selected natural product classes. This project demonstrates how machine learning can be applied to chemical datasets to distinguish biologically relevant compound groups from spectral features.

### Visualizations

#### Confusion Matrix

<p align="center">
  <img src="./images/confusion_matrix.png.png" alt="Confusion Matrix" width="500">
</p>

#### Accuracy Comparison

<p align="center">
  <img src="./images/accuracy_bar_chart.png.png" alt="Accuracy Comparison" width="500">
</p>

#### Feature Importance

<p align="center">
  <img src="./images/feature_importance.png.png" alt="Feature Importance" width="500">
</p>

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/avaerichards/plant-ms-classifier.git
   ```

2. Move into the project folder:

   ```bash
   cd plant-ms-classifier
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `plant_ms_classifier.ipynb` and run the notebook cells.

## Applications

This workflow is relevant to:
- natural products research
- metabolomics
- plant biochemistry
- introductory cheminformatics and machine learning for scientific data

## Limitations

- The dataset is relatively small and may not reflect the variability of real experimental spectra.
- Model performance may change with larger or more diverse datasets.
- This project is intended as a proof-of-concept workflow rather than a validated predictive tool.

## Future Improvements

- Add more natural product classes
- Evaluate additional machine learning models
- Include cross-validation
- Add a cleaned sample dataset to the repository
- Convert the notebook into a reproducible script-based pipeline

## Author

**Ava Richards**  
Biomedical science / biochemistry student interested in medicinal chemistry, natural products, machine learning, and scientific data analysis.
