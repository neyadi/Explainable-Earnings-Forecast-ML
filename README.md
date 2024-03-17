# Machine Learning for Explainable Future Earnings Forecasting

This repository contains the implementation of my MSc thesis project, titled "Machine Learning for Explainable Future Earnings Forecasting", at Khalifa University of Science and Technology. The project explores the application of machine learning techniques, particularly Light Gradient Boosting Machine (LightGBM), to forecast the direction of future quarterly earnings and provides insights using Explainable Artificial Intelligence (XAI) methods like SHAP and LIME.

## Overview

The goal of this project is to build a machine learning-based model that can accurately predict the direction of future quarterly earnings for public companies. The model leverages high-dimensional data from financial statements and aims to match or surpass the performance of traditional analyst forecasts. Additionally, the project utilizes XAI techniques to provide both global and local interpretations of the model’s predictions.

## Dataset

The dataset used in this study consists of financial statement data sourced from Compustat and the Institutional Brokers' Estimate System (IBES). It covers a wide range of public companies over a period between 1985-2020.

## Methodology

- <b>Modeling Approach</b>: Using the LightGBM algorithm, the project predicts whether a company’s earnings will increase in the next quarter, compared to the current quarter.
- <b>Feature Engineering</b>: Features include current values, lagged values, and percentage changes derived from the financial statements.
- <b>Evaluation</b>: The model is evaluated based on classification accuracy, macro F1 score, Area Under the ROC Curve (AUC), and economic significance through a market-neutral trading strategy.
- <b>Explainability</b>: SHAP and LIME are used for interpreting the ML model, offering insights into feature importance and model behavior.

## Results

- The model demonstrates a high degree of accuracy in predicting the direction of earnings changes, closely matching the performance of financial analysts.
- SHAP and LIME interpretations provide valuable insights into the decision-making process of the model, highlighting key financial features influencing earnings predictions.

## Installation

Instructions for setting up the project environment:

```bash
# clone the repository
git clone https://github.com/neyadi/Explainable-Earnings-Forecast-ML.git

# navigate to the project directory
cd Explainable-Earnings-Forecast-ML
```

## Usage

To use this project and get the results in the thesis, you need to follow these steps:

1. Make sure you have Jupyter installed. If not, you can install it using pip:
```bash
pip install notebook
```

2. Navigate to the project directory, if you haven't already:
```bash
cd Explainable-Earnings-Forecast-ML
```

3. Start Jupyter Notebook
```bash
jupyter notebook
```

4. Once Jupyter Notebook is running, it should open in your web browser. Navigate through the `code` directory.
   
5. Inside the `code` directory, you will find a series of Jupyter notebooks (`*.ipynb` files). These notebooks are prefixed with numbers indicating the order in which they should be executed.

Note: Some notebooks may depend on the outputs of the previous ones. Ensure all notebooks are run in the sequence provided to maintain consistency in results.




