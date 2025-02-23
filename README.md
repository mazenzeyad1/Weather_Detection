# Weather Prediction using Machine Learning

## Overview
This project aims to develop a **weather prediction model** using machine learning techniques. The dataset consists of historical weather data, and the model is trained to predict future weather conditions based on various input features.

## Dataset
We use two datasets:
- **Training Data:** `Weather Training Data.csv`
- **Test Data:** `Weather Test Data.csv`

The datasets include features such as:
- Temperature
- Humidity
- Wind Speed
- Pressure
- Weather Conditions (Rain, Sunny, Cloudy, etc.)

## Methods
The project involves the following key steps:
1. **Data Preprocessing**
   - Handling missing values
   - Feature selection
   - Normalization & Scaling

2. **Model Selection and Training**
   - Evaluating multiple ML algorithms (Linear Regression, Decision Trees, Random Forest, Neural Networks)
   - Hyperparameter tuning

3. **Model Evaluation**
   - Accuracy metrics: RMSE, R² Score, MAE
   - Visualizing results

## Files
- `WeatherPrediction.ipynb`: Main Jupyter Notebook containing data preprocessing, model training, and evaluation.
- `bigdata1.ipynb`: Additional exploratory analysis on large-scale weather data.
- `Untitled.ipynb`, `Untitled1.ipynb`: Work-in-progress notebooks for testing alternative models and approaches.

## Results
- The trained model provides accurate predictions for temperature and other weather parameters.
- The feature importance analysis indicates that **humidity** and **wind speed** are the most significant contributors to weather changes.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-prediction.git
   cd weather-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook WeatherPrediction.ipynb
   ```

## Acknowledgments
This project was inspired by meteorological research and the application of machine learning to climate studies. Special thanks to the open-source community for datasets and frameworks.

