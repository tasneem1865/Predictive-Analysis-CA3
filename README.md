# Predictive-Analysis-CA3
# Used Car Price Prediction Using Predictive Analytics

## 1. Problem Statement

The objective of this project is to predict the selling price of a used car based on its features, including manufacturing year, kilometers driven, fuel type, seller type, transmission, and ownership history.

The project uses machine learning regression algorithms to learn patterns from historical used-car data and estimate selling prices.

## 2. Dataset

**Dataset name:** CarDekho Used Car Dataset

**File:** `CAR DETAILS FROM CAR DEKHO.csv`

The dataset contains used-car information such as:

- Car name
- Manufacturing year
- Selling price
- Kilometers driven
- Fuel type
- Seller type
- Transmission
- Owner history

The target variable is `selling_price`.

Dataset source: [CarDekho Vehicle Dataset on Kaggle](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)

## 3. Methodology

The project follows the Knowledge Discovery in Databases (KDD) process:

1. **Data Selection:** Load and inspect the CarDekho dataset.
2. **Data Preprocessing:** Check missing values, remove duplicates, and prepare the data.
3. **Exploratory Data Analysis:** Use graphs to examine price distributions and relationships between car features and selling price.
4. **Data Transformation:** Convert categorical variables into numerical features.
5. **Predictive Modelling:** Train Linear Regression, Decision Tree Regressor, and Random Forest Regressor.
6. **Model Evaluation:** Compare models using MAE, RMSE, and R² score.
7. **Knowledge Presentation:** Display model comparisons, actual versus predicted prices, sample predictions, and feature importance.

## 4. Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Project Files

- `predictive_project.ipynb` — Complete implementation of the predictive analytics model.
- `CAR DETAILS FROM CAR DEKHO.csv` — Dataset used for model development.
- `README.md` — Project description, methodology, and execution instructions.

## 6. How to Run the Project

1. Download or clone this repository.
2. Open `predictive_project.ipynb` in Google Colab or Jupyter Notebook.
3. Upload `CAR DETAILS FROM CAR DEKHO.csv` to the Colab session if it is not already available.
4. Ensure the dataset path in the notebook is correct.
5. Run the notebook cells in order.
6. Review the graphs, evaluation metrics, model comparisons, and predictions.

## 7. Evaluation Metrics

- **MAE:** Measures the average absolute difference between actual and predicted prices.
- **RMSE:** Measures prediction error while penalizing larger errors more heavily.
- **R² Score:** Measures how much variation in selling prices is explained by the model.

The best-performing model is identified by comparing the evaluation results.

## 8. Conclusion

This project demonstrates how predictive analytics and regression algorithms can be used to estimate used-car selling prices. The performance of three regression models is compared, and the results are analyzed using evaluation metrics and visualizations.

The model's accuracy depends on the quality of the dataset and the features used. Further improvements may include hyperparameter tuning, feature engineering, and incorporating additional relevant car information.
