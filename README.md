Breast Cancer Prediction Using Logistic Regression

This project predicts whether breast cancer is Malignant or Benign using a Logistic Regression model from Scikit-learn.

 Project Overview

Breast cancer is one of the most common types of cancer, and early detection is crucial. This project uses machine learning to classify tumors as malignant or benign based on a set of features from the Breast Cancer Wisconsin dataset (built into Scikit-learn).

Technologies Used

Python

NumPy – Numerical computations

Pandas – Data manipulation and analysis

Scikit-learn – Machine Learning algorithms and metrics

 Dataset

The dataset is available in Scikit-learn:

Features: 30 numeric features (e.g., mean radius, texture, smoothness)

Target:

0 → Malignant

1 → Benign

 Project Workflow

Data Loading
Load the Breast Cancer dataset from Scikit-learn and convert it into a Pandas DataFrame.

Exploratory Data Analysis (EDA)

Check dataset shape and info

Handle missing values

Analyze target distribution

Data Preprocessing

Separate features (X) and target (Y)

Split into train (80%) and test (20%) sets

Model Training
Train a Logistic Regression model on the training data.

Model Evaluation

Accuracy on training data

Accuracy on test data

Predictive System
Build a system to predict whether a new data sample is malignant or benign.

 Results

Training Accuracy: 96.92%

Testing Accuracy: 92.98%

 Sample Prediction

Input:

(13.54,14.36,87.46,566.3,0.09779,0.08129,0.06664,0.04781,0.1885,0.05766,
 0.2699,0.7886,2.058,23.56,0.008462,0.0146,0.02387,0.01315,0.0198,0.0023,
 15.11,19.26,99.7,711.2,0.144,0.1773,0.239,0.1288,0.2977,0.07259)


Output:

The Breast Cancer is Benign

 How to Run

Clone this repository:

git clone https://github.com/PranithaBokketi/Breast-Cancer-Prediction.git


Navigate to the project folder:

cd Breast-Cancer-Prediction


Install dependencies:

pip install numpy pandas scikit-learn


Open the Jupyter Notebook or Google Colab and run all cells:

jupyter notebook breast_cancer_prediction.ipynb

 Future Enhancements

Add visualizations (correlation heatmap, target distribution)

Implement other models (Random Forest, SVM) for comparison

Deploy using Streamlit or Flask for a web-based interface

AUTHOR BY
BOKKETI PRANITHA
