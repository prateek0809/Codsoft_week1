# Titanic Survival Prediction

## Table of Contents
- [Project Overview](#Project-overview)
- [Dataset](#Dataset)
- [Technologies Used](#Technologies-Used)
- [Project Structure](#Project-Structure)
- [Installation](#Installation)
- [Models Used](#Models-used)
- [Results](#Results)

## Project Overview

The Titanic Survival Prediction project is a machine learning-based approach to predict the survival of passengers on the Titanic. By utilizing historical data, this project demonstrates how to preprocess data, select features, train models, and evaluate their performance.

## Dataset

The dataset used in this project is the famous Titanic dataset, which is available through Kaggle. It contains information about the passengers such as age, sex, ticket class, and whether they survived or not.

## Technologies Used

- **Python**: The programming language used for the entire project.
- **Jupyter Notebook**: Used to write and execute the Python code.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For implementing machine learning models.
- **Matplotlib/Seaborn**: For data visualization.

## Project Structure

- `Titanic_Survival_Prediction.ipynb`: The main Jupyter Notebook containing the code for data preprocessing, feature engineering, model training, and evaluation.
- `tested/`: Directory containing the dataset (CSV file).
- `README.md`: This file, provides an overview of the project.

## Installation

1. Clone the repository to your local machine using:
    ```bash
    git clone https://github.com/prateek0809/Titanic_Survival_Prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Titanic_Survival_Prediction
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Titanic_Survival_Prediction.ipynb
    ```

4. Run the cells in the notebook to see the analysis and model predictions.

## Model Used

The model used in this project is Logistic Regression. This statistical method is ideal for binary classification problems like predicting survival. The model was chosen because it effectively handles binary outcomes (survived or not) and provides interpretable coefficients, making it easier to understand the impact of different features on survival probability.

## Results

The final model is evaluated using metrics such as accuracy. The results provide insights into the model's performance and areas for potential improvement.
