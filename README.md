# Churn Management Model for Video Streaming Service

## Introduction
In this project, a machine learning model to predict customer churn for a video streaming service is buit. Subscription services often face the challenge of retaining customers, and predicting churn is crucial for targeted interventions. This repository contains a complete data science workflow to tackle this problem, using a unique dataset provided for the challenge.

## Project Structure
The project is organized into the following phases:
1. **Data Loading**: Load the train and test datasets.
2. **Exploratory Data Analysis (EDA)**: Analyze the data to understand distributions, correlations, and basic statistics.
3. **Data Cleaning**: Handle missing values and prepare the data for modeling.
4. **Feature Selection**: Select important features based on correlation and feature importance from a RandomForest model.
5. **Model Building**: Build a RandomForestClassifier to predict churn.
6. **Model Evaluation**: Evaluate the model using cross-validation.
7. **Prediction**: Make predictions on the test dataset.


## Datasets
- `train.csv`: Training dataset with 243,787 subscriptions and the target variable `Churn`.
- `test.csv`: Test dataset with 104,480 subscriptions for which predictions are to be made.
- `data_descriptions.csv`: Description of the dataset features.

## Requirements
- Python 3.6+
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, shap

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/churn-management-model.git
    cd churn-management-model
    ```
2. Install the required libraries:
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn shap
    ```

## Results
The model's performance is evaluated using ROC AUC.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
