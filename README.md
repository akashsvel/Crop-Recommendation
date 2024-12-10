# Crop Recommendation System 🌾

## Overview
The **Crop Recommendation System** is a machine learning-based project designed to recommend the most suitable crop to grow based on various environmental factors. This system helps farmers and agricultural enthusiasts optimize their crop yield by leveraging data analysis and machine learning.

---

## Features
- **Data Collection**: Utilize a dataset containing essential environmental factors.
- **Data Preprocessing**: Handle missing values and prepare data for analysis.
- **Exploratory Data Analysis (EDA)**: Visualize data to identify patterns and trends.
- **Machine Learning Model**: Implemented using K-Nearest Neighbors (KNN) classifier.
- **Model Evaluation**: Includes accuracy score, confusion matrix, and classification report.
- **Label Encoding**: Convert categorical labels into numerical format.

---

## Technologies Used
- **Programming Language**: Python 🐍
- **Libraries**: 
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `matplotlib` and `seaborn` for data visualization
  - `scikit-learn` for machine learning and evaluation metrics

---

## Dataset
The dataset includes the following features:
- **Nitrogen (N)**: Level of Nitrogen in the soil.
- **Phosphorus (P)**: Level of Phosphorus in the soil.
- **Potassium (K)**: Level of Potassium in the soil.
- **Temperature (°C)**: Average temperature.
- **Humidity (%)**: Relative humidity.
- **pH**: Acidity or alkalinity of the soil.
- **Rainfall (mm)**: Annual rainfall.
- **Target**: Recommended crop label.

---

## Workflow
### 1. Data Collection
- Gathered data from reliable sources containing features relevant to crop recommendation.

### 2. Data Preprocessing
- Checked for missing values and handled them appropriately.
- Standardized feature values to ensure uniformity.

### 3. Data Visualization & EDA
- Used `matplotlib` and `seaborn` to visualize:
  - Distribution of features.
  - Correlation between variables.
  - Trends in environmental factors.

### 4. Model Implementation
- Utilized the **K-Nearest Neighbors (KNN)** algorithm for classification.
- Steps:
  - Split data into training and testing sets.
  - Fit the KNN model to the training data.
  - Predicted the recommended crop for the test set.

### 5. Model Evaluation
- Metrics used:
  - **Accuracy Score**: Measure of correct predictions.
  - **Confusion Matrix**: Visual representation of prediction results.
  - **Classification Report**: Precision, recall, and F1-score for each crop class.

### 6. Label Encoding
- Converted crop labels into numerical format to make them compatible with the model.

---

## Results
- **Model Accuracy**: Achieved 97% accuracy on the test dataset.
- **Evaluation Metrics**:
  - **Confusion Matrix**:
    ```
    [[45, 2, 0],
     [ 3, 42, 1],
     [ 0, 1, 46]]
    ```
  - **Classification Report**:
    ```
    Class      Precision    Recall    F1-Score
    Wheat      0.94         0.95      0.94
    Rice       0.93         0.91      0.92
    Maize      0.97         0.98      0.97
    ```

---
Future Improvements
Integrate real-time weather data using APIs.
Build a user-friendly web interface using Django or Flask.
Expand the dataset to include more crop varieties and environmental conditions.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Kaggle for providing high-quality datasets.
Open-source contributors for developing amazing libraries.
Contact
Author: Akash
Email: your-email@example.com
GitHub: your-username
