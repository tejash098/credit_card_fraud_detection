<h1 align="center">💳 Credit Card Fraud Detection</h1>

<p align="center">
  <strong>A Machine Learning Project to Detect Fraudulent Credit Card Transactions</strong>
</p>

## 📖 Overview

Credit card fraud is a significant problem in the financial industry, costing billions of dollars annually. This project aims to build a machine learning model capable of accurately identifying fraudulent transactions, allowing financial institutions to prevent unauthorized charges and protect their customers.

This project was developed using **Google Colaboratory** and leverages a dataset of credit card transactions to train and evaluate a predictive model.

## ✨ Features

- **Data Loading and Preprocessing:** Efficiently handles large datasets using Pandas.
- **Exploratory Data Analysis:** Analyzes the distribution of legitimate vs. fraudulent transactions.
- **Data Splitting:** Uses `train_test_split` to divide the dataset into training and testing sets for robust evaluation.
- **Machine Learning Model:** Implements a **Logistic Regression** model using `scikit-learn` for binary classification (Fraud vs. Legitimate).
- **Evaluation Metrics:** Uses accuracy score to measure model performance and reliability.

## 🛠️ Tech Stack

- **Python:** The core programming language.
- **NumPy:** For numerical operations and arrays.
- **Pandas:** For data manipulation and analysis.
- **Scikit-Learn (sklearn):** For machine learning modeling and evaluation.
- **Jupyter Notebook / Google Colab:** For interactive development and data exploration.

## 🚀 Setup Instructions

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/credit_card_fraud_detection.git
   cd credit_card_fraud_detection
   ```

2. **Install Dependencies:**
   Ensure you have Python installed, then install the required libraries:
   ```bash
   pip install numpy pandas scikit-learn
   ```

3. **Download the Dataset:**
   The project requires the `creditcard.csv` dataset. Place it in the root directory or update the path in the notebook appropriately.

4. **Run the Notebook:**
   You can open the Jupyter Notebook locally or upload it to Google Colab.
   ```bash
   jupyter notebook Welcome_To_Colaboratory.ipynb
   ```

## 📊 Model Used

The core algorithm used in this project is **Logistic Regression**. It is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, which is highly suitable for identifying whether a transaction is fraudulent (1) or not (0).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## 📝 License

This project is open-source and available under the MIT License.
