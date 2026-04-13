# Laptop Price Prediction Model

This project was developed using Python and machine learning techniques to predict the market prices of laptops based on their technical specifications. Extensive data cleaning, visualization, and model optimization were performed on the dataset.

## Project Success Metrics
The model delivers highly consistent results, particularly for laptops in the general market segment (under 125,000 TL):
- **R² Score:** 0.8239 (Explains 82% of price variability)
- **Mean Absolute Error (MAE):** 6,587.80 TL (Average error margin)

## Technologies & Libraries Used
- **Python:** Primary programming language.
- **Pandas & NumPy:** Data processing and analysis.
- **Scikit-learn:** Model training and hyperparameter optimization (Random Forest).
- **Matplotlib & Seaborn:** Data visualization and error analysis (Residual Plots).

## Applied Data Science Steps
1. **Data Preprocessing:** Categorical variables were converted to numerical data using the One-Hot Encoding method.
2. **Outlier Cleaning:** Devices with “extreme” prices exceeding 125,000 TL, which confused the model and caused data skew, were removed to improve the model’s generalization ability.
3. **Hyperparameter Optimization:** The optimal tree depth and number were determined using `RandomizedSearchCV`.
4. **Error Analysis:** Residual plots were used to visualize where the model deviated across different price ranges.

## How Does the Model Work?
The model takes basic features such as processor type, RAM capacity, SSD size, and brand to generate a price prediction suitable for market conditions.

---
