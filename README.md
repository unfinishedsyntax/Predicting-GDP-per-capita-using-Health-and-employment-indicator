# Predicting-GDP-per-capita-using-Health-and-employment-indicator
## 🧠 Project Overview

This project explores how education, healthcare, and employment contribute to a country's economic performance.
Using a dataset of 191 countries, we predict GDP per Capita based on:

Literacy Rate

Physician Density

Unemployment Rate (%)

GDP Growth (% Annual)

##🎯 Objective

To build a regression model that accurately predicts GDP per Capita using socio-economic indicators.

## 📊 Dataset Information
Column	Description
Country	Name of the country
Literacy Rate	Percentage of literate population
Physician Density	Physicians per 1,000 people
GDP (Current USD)	Gross Domestic Product
GDP Growth (% Annual)	Yearly GDP growth percentage
GDP per Capita (Current USD)	Economic output per person
GDP per Capita Category	Categorical GDP level (Low, Mid, High, etc.)
Unemployment Rate (%)	Unemployment percentage
Continent	Continent name
## ⚙️ Tools & Libraries Used

🐍 Python 3.10+

📦 Pandas, NumPy – Data manipulation

📊 Matplotlib, Seaborn – Visualization

🤖 Scikit-learn – Machine Learning

📈 Linear Regression & Random Forest Regressor

## 📂 Project Workflow

Load & Explore Data

Checked data quality, summary statistics, and correlations.

EDA (Exploratory Data Analysis)

Analyzed literacy, physician access, and unemployment across continents.

Built correlation heatmaps between features and GDP.

Model Building

Linear Regression model trained on 80% of data.

Features: Literacy Rate, Physician Density, Unemployment Rate, GDP Growth (%).

Evaluation Metrics

R² Score

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Visualization

Actual vs Predicted GDP plot

Feature Importance bar chart

## 📈 Results
Metric	Score
R² Score	≈ 0.78 
MAE	~2000 USD
RMSE	~3500 USD
🔍 Insights

Literacy Rate & Physician Density → Positive correlation with GDP per Capita.

High Unemployment → Negative impact on GDP per Capita.

Education and healthcare investments are strong predictors of prosperity.

## 📊 Visuals

You can include screenshots like:

Correlation Heatmap

Actual vs Predicted GDP Plot

Feature Importance (Regression Coefficients)

## 🚀 Next Steps

feature scaling or polynomial regression to improve fit.

Add continent-wise analysis dashboards (Streamlit/Power BI).

Deploy as a Gradio or Streamlit app on Hugging Face Spaces.

💬 How to Run
# Clone the repository
git clone https://github.com/yourusername/GDP-Per-Capita-Regression.git
cd GDP-Per-Capita-Regression

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook GDP_Prediction_Regression_Project.ipynb
