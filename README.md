# Used Car Price Prediction

## Project Overview

This project uses **Predictive Analytics and Machine Learning** to estimate the selling price of used cars based on their features. It follows the **Knowledge Discovery in Databases (KDD) process** to prepare data, explore patterns, train models, and evaluate predictions.

## Objectives

- Combine two CarDekho datasets for analysis.
- Clean and preprocess the combined data.
- Explore the relationship between car features and selling prices.
- Train and compare multiple regression models.
- Evaluate model performance using standard regression metrics.
- Predict the estimated selling price of a used car.

## Datasets

The project uses the following two datasets:

1. `CAR DETAILS FROM CAR DEKHO.csv`
2. `Car details v3.csv`

The common columns are selected from both datasets, and their records are combined. Exact duplicate records and invalid entries are removed during data cleaning.

## Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualisation
- **Seaborn** — Statistical visualisation
- **Scikit-learn** — Data preprocessing, model training and evaluation
- **Google Colab** — Development environment

## Project Workflow

1. **Data Collection:** Load both CarDekho datasets.
2. **Data Integration:** Select common columns and combine the datasets.
3. **Data Cleaning:** Handle missing values, correct data types, remove exact duplicates and filter invalid records.
4. **Feature Engineering:** Extract the car brand and calculate car age.
5. **Exploratory Data Analysis:** Visualise price distributions and relationships between car features.
6. **Data Preprocessing:** Handle missing values, scale numerical features and encode categorical features.
7. **Model Training:** Train four regression models.
8. **Model Evaluation:** Compare performance using MAE, RMSE and R².
9. **Price Prediction:** Use the selected model to estimate the selling price of a used car.

## Machine Learning Models

The following regression algorithms are implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

The models are compared using the same training and testing split. The model with the lowest Mean Absolute Error (MAE) is selected as the best-performing model according to that criterion.

## Evaluation Metrics

| Metric | Purpose |
|---|---|
| MAE | Measures the average absolute prediction error |
| RMSE | Penalises larger prediction errors more strongly |
| R² Score | Measures how well the model explains variation in selling prices |

The notebook also includes actual-versus-predicted visualisation, feature analysis where supported, and a prediction-error breakdown.

## Visualisations

The project includes graphs for:

- Distribution of used-car selling prices
- Number of cars by fuel type
- Manufacturing year versus selling price
- Kilometres driven versus selling price
- Comparison of regression model performance
- Actual versus predicted prices
- Average selling price by manufacturing year
- Predictions within and above a 20% error threshold

## How to Run the Project

1. Download or clone this repository.
2. Open `Used_Car_Price_Prediction.ipynb` in Google Colab.
3. Run the notebook cells in order.
4. Upload both required CSV datasets when prompted.
5. Allow the notebook to clean the data, train the models and display the results.
6. Use the prediction function at the end to estimate a car's selling price.

## Results

The notebook calculates model performance metrics using the combined and cleaned dataset. It compares the four regression models and selects the model with the lowest MAE.

The final evaluation scores and prediction results are generated when the notebook is executed. They depend on the datasets and the resulting train-test split.

## Conclusion

This project demonstrates how predictive analytics can support used-car price estimation. By combining data from two sources, preparing the data, comparing regression algorithms and evaluating their predictions, the project provides an end-to-end machine-learning workflow.

**Note:** Predicted prices are estimates based on historical listings and are not guaranteed market prices.

## Author

**Tasneem Sadikot**

Project: Predictive Analytics — Used Car Price Prediction
