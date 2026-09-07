# Fashion-MNIST Classification using KNN

Machine Learning assignment focused on image classification using the Fashion-MNIST dataset.

## Project Overview

The goal of this project is to classify Fashion-MNIST images into 10 different clothing categories using a K-Nearest Neighbors (KNN) classifier implemented from scratch.

The notebook includes the complete machine learning pipeline, from data exploration and preprocessing to model training, hyperparameter tuning, evaluation and analysis.

## Main Steps

- Data loading and exploratory data analysis (EDA)
- Pixel normalization
- Dimensionality reduction using PCA
- KNN classifier implementation from scratch
- Hyperparameter tuning using 5-Fold Cross Validation
- Comparison of different K values and weighting methods
- Final model training and evaluation
- Model explainability and class imbalance analysis

## Dataset

The project uses the [Fashion-MNIST Dataset](https://www.kaggle.com/datasets/zalando-research/fashionmnist) available on Kaggle.

- 70,000 grayscale images
- Image size: 28x28 pixels
- 10 clothing categories
- 60,000 training samples
- 10,000 test samples

## Model and Evaluation

The KNN classifier was implemented from scratch and optimized using different hyperparameter combinations.

PCA was used for dimensionality reduction, and model performance was evaluated primarily using the Macro F1-Score.

The initial model achieved a Macro F1-Score of **0.8599**.

After hyperparameter tuning, the final model achieved:
- Accuracy: **0.8893**
- Macro F1-Score: **0.8892**
- Macro F1 improvement: **+0.0293**

## Files

- `ML_Assignment.ipynb` - Full implementation, experiments, results and explanations

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
