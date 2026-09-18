# Hypothyroidism Prediction Using Machine Learning

Machine learning-based prediction of hypothyroidism using clinical and biochemical features, with comparative evaluation of classification models.

## Project Overview

Hypothyroidism is a thyroid-related condition that can be studied using clinical and biochemical indicators.

This project explores the use of machine learning classification techniques for hypothyroidism prediction. It includes dataset preparation, model development, and comparative evaluation using:

- Logistic Regression
- Random Forest
- Support Vector Machine

The repository contains the datasets and Jupyter notebooks associated with the project.

## Objectives

- Explore clinical and biochemical features related to hypothyroidism.
- Prepare the available data for machine learning analysis.
- Develop machine learning classification models.
- Compare the performance of different classification algorithms.
- Evaluate model performance using classification metrics.

## Machine Learning Models

### Logistic Regression

A supervised classification algorithm used to predict the target class based on the available input features.

### Random Forest

An ensemble learning algorithm that combines multiple decision trees for classification.

### Support Vector Machine

A supervised learning algorithm used to classify observations into different target classes.

## Repository Structure

```text
hypothyroidism-prediction/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── hypothyroidism_dataset.csv
│   ├── hypothyroidism_status_dataset.csv
│   └── README.md
│
└── notebooks/
    ├── model_comparison.ipynb
    ├── logistic_regression.ipynb
    ├── random_forest.ipynb
    ├── support_vector_machine.ipynb
    └── README.md
```

## Dataset

The `data/` folder contains the datasets used in the project:

- `hypothyroidism_dataset.csv`
- `hypothyroidism_status_dataset.csv`

The datasets use different target-column names. The required dataset and target column should be checked before running each notebook.

## Project Notebooks

| Notebook | Description |
|---|---|
| `model_comparison.ipynb` | Model development and comparative evaluation workflow |
| `logistic_regression.ipynb` | Logistic Regression implementation |
| `random_forest.ipynb` | Random Forest implementation |
| `support_vector_machine.ipynb` | Support Vector Machine implementation |

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- Seaborn

## Installation

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

## How to Run

### 1. Open the Repository

Download or clone this repository to your computer.

### 2. Install the Requirements

Open a terminal inside the project folder and run:

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open a Notebook

Open any notebook from the `notebooks/` folder.

Before running a notebook:

1. Check the dataset path.
2. Confirm that the required dataset is available in the `data/` folder.
3. Check the target-column name.
4. Run the notebook cells in order.

## Published Research Paper

This project is associated with the following published research paper:

**Prediction Modeling and Comparative Evaluation of Hypothyroidism Using Machine Learning Techniques**

The paper is published through IEEE.

**Published Paper DOI:**  
https://doi.org/10.1109/ICECMSN68058.2025.11382912

## Notes

- This repository contains the project datasets and Jupyter notebooks.
- The notebooks represent the model-development work associated with the project.
- Dataset paths may need to be updated after downloading or cloning the repository.
- Results may depend on the dataset version, preprocessing steps, random state, and execution environment.
