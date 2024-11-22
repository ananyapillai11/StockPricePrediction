# 📈 Stock Price Prediction Using Fuzzy Inference Systems (FIS)

This project explores the predictive capabilities of **Fuzzy Inference Systems (FIS)** for stock price forecasting. Specifically, the study compares three fuzzy logic models: **Sugeno FIS**, **Mamdani FIS**, and **Adaptive Neuro-Fuzzy Inference System (ANFIS)**. By integrating these models with **Gradient Descent Optimization**, the project demonstrates an enhanced ability to predict stock prices with improved accuracy.

---

## 🎯 Key Features

1. **Models Implemented**:
   - **Sugeno FIS**: Uses optimized triangular membership functions for better adaptability.
   - **Mamdani FIS**: Focuses on interpretability through trapezoidal membership functions and expert-defined rules.
   - **ANFIS**: Combines the learning capability of neural networks with fuzzy logic for dynamic rule adjustment.

2. **Optimization**:
   - **Gradient Descent**: Enhances model performance by fine-tuning membership functions and rule weights.

3. **Error Metrics Evaluated**:
   - Root Mean Squared Error (RMSE)
   - Mean Absolute Error (MAE)
   - Mean Absolute Percentage Error (MAPE)
   - R-Squared (R²)
   - Mean Percentage Error (MPE)

4. **Visualization**:
   - Graphical comparisons of model predictions.
   - Performance metrics visualized using line plots and bar charts.

---

## 🛠️ Tech Stack

- **Programming Language**: Python
- **Libraries Used**:
  - `numpy`, `pandas`: Data manipulation and analysis.
  - `matplotlib`, `seaborn`: Visualization of data and performance metrics.
  - `skfuzzy`: Fuzzy logic modeling.
  - `scikit-learn`: Machine learning utilities for evaluation and preprocessing.

---

## 📊 Dataset

The dataset used in this project contains historical stock price data, including:
- **Features**: `open`, `high`, `low`, `volume`
- **Target Variable**: `close` (closing price)

**Source**: The dataset simulates Google stock price data over a period of time.

---

## 🚀 How It Works

### 1. Data Preprocessing
- Normalizes the features (`open`, `high`, `low`, `volume`) and the target variable (`close`) for better model performance.

### 2. Fuzzy Inference Systems
- **Sugeno FIS**:
  - Employs triangular membership functions.
  - Optimized using gradient descent to minimize prediction errors.
- **Mamdani FIS**:
  - Utilizes trapezoidal membership functions with expert-defined rules for interpretability.
- **ANFIS**:
  - Integrates fuzzy logic with neural networks for dynamic learning and adaptation.

### 3. Model Evaluation
- Splits the dataset into training and testing sets.
- Evaluates performance using RMSE, MAE, MAPE, R², and MPE.
- Visualizes predictions and performance metrics for easy comparison.

---

## 📈 Results and Findings

1. **Comparative Analysis**:
   - ANFIS outperformed Sugeno and Mamdani in terms of RMSE, MAE, and MAPE.
   - Mamdani provided better interpretability but slightly lower accuracy.
   - Sugeno achieved a balance between interpretability and accuracy.

2. **Optimization Impact**:
   - Gradient descent significantly reduced errors in Sugeno and ANFIS models.
   - Enhanced adaptability to changing stock trends.

3. **Visualizations**:
   - Performance metrics highlighted key differences between models.
   - Graphical predictions demonstrated ANFIS's superior ability to track stock trends.

---


