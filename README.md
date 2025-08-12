 📊 Project Workflow

1. Data Loading & Exploration
   - Imported dataset and checked for missing values
   - Analyzed data distribution and feature relationships

2. Data Preprocessing
   - Handled missing values
   - Encoded categorical variables
   - Scaled numerical features

3. Model Building
   - Used **Linear Regression** as the baseline model
   - Split data into **train** and **test** sets using `train_test_split`

4. Model Evaluation
   - **R² Score**: Measures goodness of fit
   - **MAE (Mean Absolute Error)**: Average prediction error
   - Metrics calculated on unseen test data

5. Prediction
   - Predicted house prices for given input data
   - Compared predicted vs actual values

🛠️ Tech Stack

Language: Python
Libraries:
  - Pandas, NumPy (Data manipulation)
  - Matplotlib, Seaborn (Data visualization)
  - Scikit-learn (ML algorithms & metrics)

📈 Results

| Metric           | Score       |
|------------------|-------------|
| R² Score         | 0.833800033 |
| MAE              | 0.310863180 |


