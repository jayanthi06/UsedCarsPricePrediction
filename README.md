# Used Cars Price Prediction

## Overview

This project aims to develop a machine learning model that accurately predicts the prices of used cars based on various features. By analyzing historical data, the model assists both buyers and sellers in making informed decisions in the used car market.

## Dataset

The dataset used in this project includes information on used cars, such as:

- **Manufacturer**: Brand of the car.
- **Model**: Specific model name.
- **Year**: Year of manufacture.
- **Mileage**: Distance the car has traveled.
- **Fuel Type**: Type of fuel the car uses (e.g., petrol, diesel).
- **Transmission**: Gear system (e.g., manual, automatic).
- **Price**: Selling price of the car.

## Methodology

1. **Data Preprocessing**:
   - Handled missing values.
   - Converted categorical variables into numerical formats using techniques like one-hot encoding.
   - Standardized numerical features to ensure uniformity.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized data distributions and relationships between variables.
   - Identified key features influencing car prices.

3. **Model Development**:
   - Implemented regression algorithms, including:
     - Linear Regression
     - Decision Tree Regression
     - Random Forest Regression
     - Gradient Boosting Regression
   - Evaluated models using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

4. **Model Evaluation**:
   - Compared model performances.
   - Selected the best-performing model based on evaluation metrics.

## Results

The Random Forest Regression model demonstrated superior performance with the lowest RMSE, indicating its effectiveness in predicting used car prices.

## Usage

To utilize the model:

1. Clone the repository:

   ```bash
   git clone https://github.com/jayanthi06/UsedCarsPricePrediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd UsedCarsPricePrediction
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook to explore the analysis and model development:

   ```bash
   jupyter notebook Used_Cars_Price_Prediction_Using_Prediction_Analytics.ipynb
   ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request for any enhancements or bug fixes.


## Acknowledgments

- Data sourced from [Kaggle](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data).
- Inspired by various used car price prediction projects on GitHub.
