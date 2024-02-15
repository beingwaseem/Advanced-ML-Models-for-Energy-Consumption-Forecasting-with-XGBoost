<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Advanced ML Models for Energy Consumption Forecasting with XGBoost</title>
</head>
<body>

<h1>Advanced ML Models for Energy Consumption Forecasting with XGBoost</h1>

<h2>Introduction</h2>
<p>This project focuses on energy consumption forecasting using advanced machine learning (ML) models, with a primary emphasis on XGBoost. Time series forecasting plays a vital role in various domains, from finance to energy management, aiding in making informed decisions based on predicted future values.</p>

<h2>Key Steps</h2>
<ol>
  <li><strong>Data Exploration and Cleaning:</strong> Begin by loading the dataset and performing initial exploratory data analysis to understand the structure of the data and identify potential outliers.</li>
  <li><strong>Outlier Analysis and Removal:</strong> Detect and remove outliers to ensure the model's accuracy and robustness.</li>
  <li><strong>Time Series Cross-Validation:</strong> Evaluate the model's performance using time series cross-validation, considering temporal order when splitting the data.</li>
  <li><strong>Feature Engineering:</strong> Generate meaningful features such as hour of the day, day of the week, and more to capture temporal patterns.</li>
  <li><strong>Lag Features:</strong> Add lag features representing past values of the target variable to consider historical trends in predictions.</li>
  <li><strong>Model Training and Cross-Validation:</strong> Train an XGBoost regressor on the preprocessed data and evaluate its performance using cross-validation.</li>
  <li><strong>Evaluation:</strong> Assess the model's performance using root mean squared error (RMSE) across different cross-validation folds.</li>
  <li><strong>Predicting the Future:</strong> Use the trained model to make future predictions.</li>
</ol>

<h2>Project Structure</h2>
<ul>
  <li><strong>data:</strong> Contains the dataset (<code>PJME_hourly.csv</code>) used for energy consumption prediction.</li>
  <li><strong>code:</strong> Contains the Python scripts for data preprocessing, model training, and evaluation.</li>
  <li><strong>models:</strong> Stores the trained XGBoost model (<code>model.json</code>) for future use.</li>
  <li><strong>results:</strong> Contains evaluation metrics and visualizations.</li>
  <li><strong>README.md:</strong> Provides an overview of the project and instructions for usage.</li>
</ul>

<h2>Usage</h2>
<ol>
  <li><strong>Setup Environment:</strong> Install the required dependencies listed in <code>requirements.txt</code>.</li>
  <li><strong>Run Scripts:</strong> Execute the Python scripts in the <code>code</code> directory to preprocess the data, train the model, and evaluate performance.</li>
  <li><strong>Interpret Results:</strong> Analyze the evaluation metrics and visualizations generated in the <code>results</code> directory.</li>
  <li><strong>Make Predictions:</strong> Use the trained model stored in the <code>models</code> directory to make future predictions.</li>
</ol>

<h2>Dependencies</h2>
<ul>
  <li>pandas</li>
  <li>numpy</li>
  <li>seaborn</li>
  <li>matplotlib</li>
  <li>xgboost</li>
  <li>scikit-learn</li>
</ul>

<h2>License</h2>
<p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>
</html>
