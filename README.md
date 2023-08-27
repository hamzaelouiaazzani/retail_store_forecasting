# Retail Store Sales Forecasting

Welcome to the **Retail Store Sales Forecasting** repository! This project dives deep into a comprehensive analysis of retail store datasets, aiming to predict weekly sales using a variety of benchmarking, statistical, and machine learning-based models. The repository showcases the journey of exploration and experimentation for accurate weekly sales forecasting for diverse retail stores.

## Notebooks Overview

This repository contains three notebooks, each focusing on a distinct aspect of the forecasting process:

1. **data_exploration_&_analysis.ipynb**: In this notebook, we conduct an extensive study of the provided dataset, exploring and analyzing its intricate details.
   
2. **statistical_modeling.ipynb**: Delve into the world of statistical forecasting models (MA, AR, ARIMA, and SARIMA). This notebook demonstrates their application to the dataset and presents a comparison with benchmarking naive models.

3. **ML_Modeling.ipynb**: This notebook takes you through the journey of creating Machine Learning-based algorithms for forecasting weekly sales of each problem. We explore and compare various algorithms, including Linear Regression, Random Forest, GradientBoostingRegressor, Voting Regressor, and the innovative LSTM+1D-CNN architecture. The notebook culminates with an insightful report of Mean Absolute Error (MAE) and Mean Squared Error (MSE) losses, along with a compelling comparison between the most performing ML-based algorithm and the strongest statistical model.

## Data Split and Performance Measurement

For all approaches—benchmarking, statistical, and ML-based—we maintain a consistent data split strategy: 80% of the data is allocated for training, while the remaining 20% is reserved for testing. This careful division is performed on a per-store basis, ensuring an accurate evaluation across all scenarios.

Performance evaluation is carried out using MAE and MSE metrics. Detailed results are compiled into Excel files for clear visualization and analysis:

- `MAE_models_stores.csv` and `MSE_models_stores.csv`: These files provide a comprehensive overview of losses per store for each model, enabling you to delve into the specific performance characteristics.

- `overall_losses.csv`: Here, we present the aggregate losses across all available stores, allowing for a holistic view of the forecasting accuracy achieved.

Feel free to explore the notebooks and results to gain insights into the art and science of retail store sales forecasting. Happy forecasting!

*(Please note that all losses are calculated using the Mean Absolute Error and Mean Squared Error metrics.)*
