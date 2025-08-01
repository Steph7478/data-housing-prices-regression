# 🏠 Real Estate Price Predictor

## 📋 Project Overview
This project uses Python and machine learning to predict real estate prices based on various features. It loads a dataset, preprocesses the data, trains a Linear Regression model, and visualizes the comparison between actual and predicted prices.

## 🚧 Project Status
This project is completed and functional. It provides a basic predictive model and visualization. Future improvements could include model tuning, feature engineering, and deployment.

## ✨ Features
- 📊 Data Preprocessing: Handles missing values and removes irrelevant columns.
- 📈 Model Training: Trains a Linear Regression model to predict prices.
- 📉 Visualization: Plots real vs predicted prices with a scatter plot and regression line.
- 💡 Price Prediction: Predicts average property price based on input features' mean.

## 🛠️ Technologies
- Python 3.13+
- pandas
- matplotlib
- scikit-learn

## ⚙️ Installation and Running

### Prerequisites
- Python 3.13 or higher
- pip (Python package installer)

### Steps

1. Clone the repository:
    ```bash
    git clone https://your-repo-url.git
    cd your-repo-folder
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Prepare your dataset:  
   Place your dataset CSV file in the `data/` folder named `dataset.csv`.  
   The dataset must contain columns including `ID` and `Price`.

4. Run the main script:
    ```bash
    python main.py
    ```

You will see a plot showing real vs predicted prices, and the average predicted property price will be printed in the console.

## 🔗 How It Works
- Loads the dataset and calculates correlation between numeric columns.
- Drops the `ID` column and fills missing values with 0.
- Splits data into features (X) and target (`Price` as y).
- Splits data into training and testing sets.
- Trains a Linear Regression model on the training data.
- Predicts prices on the test set and plots the results.
- Predicts average price based on mean values of features.
