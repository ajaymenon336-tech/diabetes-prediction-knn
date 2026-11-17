# Diabetes Prediction Using KNN

## Overview
This project uses the **K-Nearest Neighbors (KNN)** machine learning algorithm to predict whether a patient has diabetes based on health-related measurements.

The project was developed using Python and Scikit-learn as part of a machine learning assignment.

## Dataset Source and License

The dataset used in this project is the **Pima Indians Diabetes Dataset**, obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/34/diabetes).

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0).

The dataset may be shared and adapted under the terms of this licence, provided appropriate credit is given.

**Attribution:** UCI Machine Learning Repository – Pima Indians Diabetes Dataset.

**License link:** https://creativecommons.org/licenses/by/4.0/

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Methodology

The project follows these steps:

1. **Data Loading:** Import the diabetes dataset.
2. **Preprocessing:** Inspect the data and handle missing measurements using median imputation.
3. **Exploratory Data Analysis:** Visualize the outcome distribution and glucose measurements.
4. **Dataset Splitting:** Divide the data into 80% training and 20% testing.
5. **Feature Scaling:** Apply StandardScaler to standardize the input features.
6. **Model Training:** Train a KNN classifier using 5 nearest neighbors.
7. **Prediction and Evaluation:** Generate predictions and evaluate the model using accuracy, a confusion matrix, precision, recall and F1-score.

## Results

The KNN model achieved the following results on the test dataset:

| Metric | Result |
|---|---:|
| Accuracy | 75.32% |
| Precision (No Diabetes) | 0.80 |
| Recall (No Diabetes) | 0.83 |
| F1-score (No Diabetes) | 0.81 |
| Precision (Diabetes) | 0.66 |
| Recall (Diabetes) | 0.61 |
| F1-score (Diabetes) | 0.63 |

The results show that the model performs better at identifying patients without diabetes than patients with diabetes.

## How to Run

1. Download or clone this repository.
2. Open the notebook `diabetes_prediction_knn.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the `diabetes.csv` dataset when prompted, or update the dataset path.
4. Run the notebook cells in order.

## Disclaimer
This project is for educational purposes only. It is not intended for medical diagnosis or clinical decision-making.

## Author
Ajay Menon

GitHub: [ajaymenon336-tech](https://github.com/ajaymenon336-tech)
