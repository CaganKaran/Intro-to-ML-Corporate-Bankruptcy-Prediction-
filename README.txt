#İstanbul University-Cerrahpaşa | Introduction to Machine Learning | Final Project

#Corporate Bankruptcy Prediction on Taiwanese Bankruptcy Prediction Dataset

## Project Overview
This project applies machine learning techniques to predict corporate bankruptcy using financial data from the Taiwan Economic Journal (1999–2009). By analyzing 95 quantitative financial features, we aim to build a robust binary classifier that can identify companies at risk of financial distress.

Our approach addresses the severe class imbalance (only 3.2% bankrupt cases) by prioritizing metrics like **Recall** and **ROC-AUC** over simple accuracy, ensuring the model effectively acts as an early warning system for stakeholders.

## Team Members
Çağan Karan - 1306220087
Fatih Bedir - 1306220024

## Dataset
**Source:** UCI Machine Learning Repository - Taiwanese Bankruptcy Prediction
**Instances:** 6,819 companies
**Features:** 95 Financial Ratios
**Link:** https://archive.ics.uci.edu/dataset/572/taiwanese+bankruptcy+prediction

## Methodology
1. **Preprocessing:**
   - **Stratified Train-Test Split (80/20):** Used to preserve the 3.2% bankruptcy ratio in the test set.
   - **Standardization:** Applied `StandardScaler` to all 95 input features.
2. **Models Implemented:**
   - **Baseline:** Dummy Classifier
   - **Linear:** Logistic Regression
   - **Ensemble:** Random Forest Classifier
3. **Evaluation:**
   - Focused on Recall, Precision, and ROC-AUC.

## How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
3. Open main.ipynb .
4. Run all cells to reproduce the experiments.
