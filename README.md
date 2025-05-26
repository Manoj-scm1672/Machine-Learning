# Car Price Prediction Using Machine Learning 🚗📈

This project presents an analysis and predictive modeling of car prices using machine learning techniques. The objective is to understand how different car features affect the price and to build a model that can accurately predict car prices based on these features.

## 📂 Project Structure

- `An_Analysis_of_Car_Price_Prediction_Using_Machine_Learning.ipynb`: Jupyter Notebook containing the full analysis, visualizations, preprocessing, model building, evaluation, and conclusions.
- `car data.csv`: Dataset used for training and evaluating the machine learning models.

## 📊 Dataset Description

The dataset includes various attributes of cars such as:
- **Car Name**
- **Year**
- **Selling Price**
- **Present Price**
- **Kms Driven**
- **Fuel Type**
- **Seller Type**
- **Transmission**
- **Owner**

These features are used to predict the selling price of a car.

## 🧠 ML Techniques Used

The following machine learning models were implemented and compared:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Each model was evaluated using metrics such as:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## 📈 Results

The project highlights the importance of feature engineering and model selection. Random Forest Regressor showed the best performance among all models evaluated.

## 📌 Requirements

To run the notebook, install the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
