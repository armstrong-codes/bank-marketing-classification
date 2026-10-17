# Bank Marketing Classification Project

## Overview

This project predicts whether a bank customer will subscribe to a term deposit following a marketing campaign. It compares traditional machine-learning algorithms with a neural network built using TensorFlow/Keras.

## Objectives

- Clean and explore the dataset.
- Train and compare Scikit-learn classification models.
- Tune a Random Forest model.
- Train a neural network using TensorFlow/Keras and `tf.data`.
- Evaluate models using accuracy, precision, recall, F1-score, ROC-AUC, and average precision.

## Dataset

The project uses the Bank Marketing dataset from the UCI Machine Learning Repository.

Dataset source: https://archive.ics.uci.edu/dataset/222/bank+marketing

The dataset contains customer and campaign information. The target variable `y` indicates whether the customer subscribed to a term deposit.

The raw dataset is stored separately in Google Drive rather than committed to this public repository.

## Models

- Logistic Regression
- Random Forest
- Histogram-based Gradient Boosting
- Tuned Random Forest
- TensorFlow/Keras neural network

## Preliminary Test Results

| Metric | Tuned Random Forest | Neural Network |
|---|---:|---:|
| Accuracy | 86.18% | 89.37% |
| Precision | 42.62% | 61.76% |
| Recall | 52.46% | 23.83% |
| F1-score | 47.03% | 34.39% |
| ROC-AUC | 0.7895 | 0.7882 |
| Average Precision | 0.4519 | 0.4373 |

These results are from the current experiment and should be verified against the final notebook execution.

## Repository Contents

- `bank_marketing_full_project_google_drive.ipynb` — main project notebook.
- `README.md` — project documentation.
- `requirements.txt` — Python dependencies.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Authorize Google Drive access when prompted.
4. Upload the required dataset when requested.
5. Review the training results, evaluation plots, and saved model artifacts.

## Project Resources

- **Google Drive:** https://drive.google.com/drive/folders/1a0Z_xTWt4xHZLUio5KmDdNXLWWqpCnRa?usp=drive_link
- **Final Report:** [INSERT LINK OR FILE PATH]
- **Presentation Video:** [INSERT LINK WHEN AVAILABLE]

## Limitations

The dataset represents historical marketing campaigns. Model performance may change on new customers or campaigns. Accuracy alone is insufficient for model selection because the target classes are imbalanced.

## Author

ARMSTRONG Hirwa
