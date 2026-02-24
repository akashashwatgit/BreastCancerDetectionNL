🧠 Breast Cancer Classification using Neural Networks
<p align="center"> <img src="https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python"/> <img src="https://img.shields.io/badge/TensorFlow-Keras-orange?style=for-the-badge&logo=tensorflow"/> <img src="https://img.shields.io/badge/Scikit--Learn-ML-green?style=for-the-badge&logo=scikitlearn"/> <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/> </p>
📌 Overview

This project implements a neural-network–based binary classification system to predict whether a breast tumor is malignant or benign using diagnostic features.
It demonstrates a complete end-to-end machine learning workflow, from data preprocessing to model evaluation and real-time prediction.

The dataset is sourced directly from scikit-learn, ensuring reproducibility and simplicity.

🧬 Dataset

- Name: Breast Cancer Wisconsin Dataset

- Source: sklearn.datasets.load_breast_cancer()

- Samples: 569

- Features: 30 numerical features

Target Labels:

- 0 → Malignant

- 1 → Benign

🏗️ Model Architecture

- Input Layer: 30 features

- Hidden Layer: 20 neurons (ReLU activation)

- Output Layer: 1 neuron (Sigmoid activation)

- Loss Function: Binary Crossentropy

- Optimizer: Adam

This architecture represents a shallow feedforward neural network, suitable for structured tabular data.

⚙️ Workflow

- Load dataset from sklearn

- Perform exploratory data analysis (EDA)

- Split data into training and testing sets

- Standardize features using StandardScaler

- Train a neural network with validation split

- Visualize training & validation performance

- Evaluate model on unseen test data

- Build a predictive system for new inputs

📊 Results

- Achieves high accuracy on test data

- Stable convergence of loss and accuracy

- No data leakage (proper train–test separation)

- Model generalizes well on unseen samples

🧪 Example Prediction
Input: Diagnostic measurements of a tumor
Output: Benign / Malignant
🛠️ Technologies Used

- Python

- NumPy

- Pandas

- Matplotlib

- Scikit-learn

- TensorFlow / Keras

📂 Project Structure
BreastCancerDetectionNL/

├── Breast_Cancer_Detection.ipynb

└── README.md

📈 Future Improvements

- Hyperparameter tuning

- Cross-validation

- Comparison with classical ML models

- Deployment using Flask or FastAPI

- Model persistence and inference API
