# Mobile Phone Price Prediction

This project predicts the price range (Low, Medium, High, Very High) of mobile phones using features like battery power, RAM, camera specs, etc.

## Objective
Build a system that can predict pricing for a mobile phone using data on available phones in the
 market. Predict if the mobile can be priced low/med/high/very high. Explore the data to
 understand the features and figure out an approach.

##  Algorithms Used
- Random Forest Classifier
- Scikit-learn for preprocessing & evaluation

## Dataset
- Columns include: battery_power, dual_sim, px_height, px_width, ram, etc.
- Target: `price_range` (0: Low, 1: Medium, 2: High, 3: Very High)

## Result
- Model Accuracy: 89%
- Confusion matrix and classification report included

## Notebook 
All the code is in [`moblie phone price prediction.ipynb`](./mobile phone price prediction.ipynb)

## 📌 Author
[Reha](https://github.com/rehanair08)
