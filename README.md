# 🌧️ Rainfall Prediction Using Linear Regression

## 📌 Project Overview
This project focuses on predicting rainfall using **Linear Regression**, a supervised Machine Learning algorithm. The model learns patterns from historical weather data and predicts rainfall based on selected weather features.

The project uses Python and popular data science libraries to perform data preprocessing, model training, prediction, and evaluation.

## 🎯 Objectives
- Analyze historical weather data.
- Perform data cleaning and preprocessing.
- Understand the relationship between weather features and rainfall.
- Build a Linear Regression model for rainfall prediction.
- Evaluate model performance using regression metrics.
- Visualize actual vs. predicted rainfall and residuals.

## 📂 Dataset
- **Dataset:** Austin Weather Data (2019–2023)
- **Source:** Add your dataset source/link here.
- **Format:** CSV

The dataset contains historical weather observations. The selected input features and target variable depend on the columns available in the dataset.

**Target Variable:** Rainfall (use the exact rainfall column name from your dataset).

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow
1. Import required libraries.
2. Load the weather dataset.
3. Explore the dataset using `head()`, `info()`, and `describe()`.
4. Handle missing values and prepare features.
5. Split the data into training and testing sets.
6. Train the Linear Regression model.
7. Generate rainfall predictions.
8. Evaluate the model.
9. Visualize predictions and residuals.

## 🧠 Algorithm
**Linear Regression**

Linear Regression models the relationship between input features and a continuous target variable.

For multiple input features:

`y_pred = b0 + b1*x1 + b2*x2 + ... + bn*xn`

Where:
- `y_pred` = Predicted rainfall
- `b0` = Intercept
- `b1, b2, ..., bn` = Model coefficients
- `x1, x2, ..., xn` = Weather features

## 📊 Model Evaluation
The model can be evaluated using:
- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

Evaluation results should be added after running the model.

## 📈 Visualizations
- Actual vs. Predicted Rainfall
- Residual Plot
- Rainfall distribution
- Feature relationship plots


## 🚀 How to Run

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd Rainfall-Prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
Open `notebooks/rainfall_prediction.ipynb` in Jupyter Notebook or VS Code and run the cells.

## 📦 Requirements
```text
pandas
numpy
matplotlib
scikit-learn
jupyter
```

## ⚠️ Limitations
- Model performance depends on data quality and feature selection.
- Linear Regression may not capture complex weather patterns.
- Rainfall observations may contain many zero values and extreme events.
- Predictions are not guaranteed to represent actual future weather.

## 🔮 Future Improvements
- Compare Linear Regression with other ML algorithms.
- Perform feature engineering.
- Experiment with Random Forest and other regression models.
- Improve evaluation using time-aware validation.
- Explore rainfall classification for rain/no-rain prediction.

## 👩‍💻 Author
**Ashvini Sundge**

- GitHub: [Your GitHub Profile](https://github.com/your-username)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/ashvini-sundge-145187343/)

## ⭐ Acknowledgements
This project was created as a hands-on
