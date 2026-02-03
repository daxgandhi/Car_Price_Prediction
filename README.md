# Car Price Prediction

This project predicts the selling price of used cars based on various features such as the car's age, mileage, fuel type, transmission, and more. It utilizes machine learning techniques to estimate market value, helping buyers and sellers make informed decisions.

## Project Overview

*   **Dataset**: Uses the "CAR DETAILS FROM CAR DEKHO" dataset (`CAR DETAILS FROM CAR DEKHO.csv`).
*   **Model**: The trained machine learning model is saved as `car_price_model.pkl`.
*   **Analysis**: The entire data analysis, preprocessing, and model training process is documented in `Main.ipynb`.

## Files

*   `Main.ipynb`: Jupyter Notebook containing the code for EDA (Exploratory Data Analysis), feature engineering, and model training.
*   `car_price_model.pkl`: Serialized Python object of the trained model, ready for deployment or inference.
*   `CAR DETAILS FROM CAR DEKHO.csv`: The source dataset used for training.

## Getting Started

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/daxgandhi/Car_Price_Prediction.git
    ```
2.  **Install dependencies** (ensure you have Python installed):
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  **Run the Notebook**:
    Open `Main.ipynb` in Jupyter Notebook or VS Code to view the analysis or retrain the model.

## Usage

You can load the trained model using `pickle` to make predictions on new data:

```python
import pickle
import pandas as pd

# Load the model
model = pickle.load(open('car_price_model.pkl', 'rb'))

# Example prediction (make sure input matches training features)
# prediction = model.predict(new_data)
```
