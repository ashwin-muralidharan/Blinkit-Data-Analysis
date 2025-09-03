#  Blinkit Sales Analysis

This project is a data analysis and machine learning pipeline built in Python (Jupyter Notebook) to analyze Blinkit’s sales dataset. It explores sales patterns, preprocesses data, and compares multiple ML models to predict sales.

##  Features

- Data cleaning and preprocessing (missing values, categorical encoding, duplicates removal)

- Exploratory Data Analysis (EDA) with Matplotlib & Seaborn

### Sales prediction using:

- 📈 Linear Regression

- 🌲 Random Forest Regressor

- 🚀 Gradient Boosting Regressor

### Model performance evaluation with R² and RMSE

- Visualization of actual vs predicted sales, residuals, and model comparison



##  Setup and Usage Instructions

1️⃣ Clone the project

```bash
git clone https://github.com/ashwin-muralidharan/Blinkit-Data-Analysis.git
cd Blinkit-Data-Analysis
```

2️⃣ Create and activate a virtual environment

**Windows:**

```bash
python -m venv .venv
.\.venv\Scripts\activate
```

**macOS/Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3️⃣ Install dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```
5️⃣ Open Blinkit Analysis.ipynb and run cells.

##  Output Highlights

- Actual vs Predicted Sales Scatterplots

- Residual Distribution Plots

- Model Performance Comparison (R² vs RMSE)
