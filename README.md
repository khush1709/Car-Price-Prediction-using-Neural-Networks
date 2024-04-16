# Car Price Prediction using Neural Networks

This repository contains Python code for predicting car prices using a neural network model. The dataset used for this prediction is `cardekho_data.csv`. The dataset contains information about various attributes of cars such as selling price, present price, kilometers driven, fuel type, seller type, transmission type, etc.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, seaborn, sklearn, matplotlib, tensorflow

## Usage
1. Clone the repository:
  ```bash
  git clone https://github.com/khush1709/car-price-prediction.git
  ```

2. Install the required libraries:
  ```bash
  pip install -r requirements.txt
  ```

3. Run the Python script:
  ```bash
  python car_price_prediction.py
  ```

## Description
- The Python script loads the dataset and preprocesses it by encoding categorical variables, handling outliers, and scaling the numerical features.
- A neural network model is built using TensorFlow's Keras API with multiple dense layers.
- The model is trained on the preprocessed data.
- Finally, the model is evaluated using mean squared error and R-squared score metrics.

## Files
- `cardekho_data.csv`: Dataset containing car information.
- `car_price_prediction.py`: Python script for preprocessing, model building, training, and evaluation.
- `README.md`: This file containing information about the project and usage instructions.

## Author
Khushal Gautam
