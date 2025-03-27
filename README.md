# House Price Prediction using Machine Learning

## By: Usman Nazakat

## Introduction
This project predicts house prices using **Linear Regression** and **Random Forest Regressor**. The dataset used is the **California Housing Prices** dataset from Kaggle. The goal is to develop a model that accurately estimates house prices based on various factors like location, number of rooms, and population density.

## Dataset Overview
- **Source**: `housing.csv`
- **Target Variable**: `median_house_value` (House Price)
- **Features**:
  - `longitude`, `latitude`: Location of the house
  - `housing_median_age`: Age of the house
  - `total_rooms`, `total_bedrooms`, `population`, `households`: Structural details
  - `median_income`: Income level of residents
  - `ocean_proximity`: Categorical feature representing house location

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### Running the Project
1. Clone the repository:
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```
2. Run the script:
```bash
python house_price_prediction.py
```

## Project Steps
1. **Data Preprocessing**:
   - Handle missing values
   - Convert categorical variables into numerical
2. **Exploratory Data Analysis (EDA)**:
   - Plot distributions and correlations
3. **Model Training**:
   - Train **Linear Regression** and **Random Forest Regressor** models
4. **Model Evaluation**:
   - Compare models using Mean Squared Error (MSE) and R² Score
5. **Model Saving**:
   - Save the best-performing model using `joblib`

## Results
- The model performance is evaluated using:
  - **Mean Squared Error (MSE)**
  - **R² Score**
- The best-performing model is saved as `best_house_price_model.pkl`.

## Visualization
The project visualizes:
- Distribution of house prices
- Feature correlation heatmap
- Actual vs Predicted prices comparison

## License
This project is open-source and available under the MIT License.

## Author
Usman Nazakat
