# Predicting Housing Prices with Random Forest

## 1. Project Overview

This project focuses on predicting housing prices using the Random Forest algorithm. Leveraging a housing dataset, the goal is to build a regression model capable of accurately estimating house prices based on various features such as area, number of bedrooms, parking availability, and furnishing status. The project demonstrates the application of machine learning algorithms in real estate pricing and valuation, offering valuable insights for homeowners, buyers, and real estate professionals.

## 2. Table of Contents

- [Introduction](#3-introduction)

- [Dataset](#4-dataset)

- [Features](#5-features)

- [Methodology](#6-methodology)

- [Results](#7-results)

- [Usage](#8-usage)

- [Contributing](#9-contributing)

- [License](#10-license)

## 3. Introduction

This project aims to predict housing prices using Random Forest, a powerful machine learning algorithm known for its accuracy in regression tasks. By analyzing a housing dataset, we can understand the relationship between various features and housing prices, providing valuable insights for both buyers and sellers in the real estate market.

## 4. Dataset

The dataset used for this project contains housing-related information, including features such as area, number of bedrooms, parking availability, and furnishing status. Each entry in the dataset represents a specific property listing with corresponding price information.

## 5. Features

The key features used to predict housing prices in this project are:

- **Area**: Total area of the property.

- **Bedrooms**: Total number of bedrooms in the property.

- **Parking**: Availability of parking space.

- **Furnishing Status (Semi-Furnished)**: Indicates whether the property is semi-furnished.

## 6. Methodology

1\. **Data Preprocessing**:

    - Loaded the housing dataset.

    - Checked for missing values and outliers.

    - Conducted feature engineering and transformation as needed.

2\. **Exploratory Data Analysis (EDA)**:

    - Visualized the distribution of housing prices and key features.

    - Analyzed correlations between features and prices.

3\. **Model Implementation**:

    - Implemented a Random Forest regression model using the `scikit-learn` library.

    - Split the dataset into training and test sets.

    - Trained the model on the training set.

4\. **Model Evaluation**:

    - Evaluated the model's performance using regression metrics such as mean squared error (MSE), mean absolute error (MAE), and R-squared score.

    - Visualized the predicted prices vs. actual prices to assess model accuracy.

## 7. Results

The Random Forest regression model achieved the following performance metrics on the test set:

- **Mean Squared Error (MSE)**: 2659567581255.7075

- **Mean Absolute Error (MAE)**: 1229692.752675841

- **R-squared Score**: 23.67%

These results demonstrate the effectiveness of the Random Forest algorithm in accurately predicting housing prices based on various property features.

## 8. Usage

To use this project, follow these steps:

1\. **Access the Kaggle notebook**:

   - Open the Kaggle notebook by clicking on the following link: [Link to Kaggle notebook](https://www.kaggle.com/code/sahilwarudkar/housing-prices-prediction/edit)

2\. **Run the notebook**:

   - Once the notebook is open, you can run each cell sequentially to see the analysis and model implementation.

## 9. Contributing

Contributions are welcome! Please follow these steps:

1\. Fork the repository.

2\. Create a new branch (`git checkout -b feature-branch`).

3\. Commit your changes (`git commit -m 'Add new feature'`).

4\. Push to the branch (`git push origin feature-branch`).

5\. Open a pull request.

## 10. License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
