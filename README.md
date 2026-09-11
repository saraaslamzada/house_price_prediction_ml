# House Price Prediction Using Machine Learning

## Project Overview

This project explores how machine learning can be used to predict house prices based on residential and geographic features.

Using the California Housing dataset, I explored the data, prepared the features, trained Linear Regression and Random Forest Regression models, compared their performance, analyzed feature importance, performed error analysis, and generated a final prediction.

The project was developed using Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

## Dataset

The project uses the California Housing dataset available through Scikit-learn.

The dataset contains 20,640 observations and 8 input features:

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

The target variable is `MedHouseVal`, representing the median house value.

## Data Preparation

The dataset was divided into training and testing sets using an 80/20 split.

- Training samples: 16,512
- Testing samples: 4,128

## Models

Two regression models were trained:

1. Linear Regression
2. Random Forest Regression

## Model Results

| Model | MAE | MSE | RMSE | R² |
|---|---:|---:|---:|---:|
| Linear Regression | 0.5332 | 0.5559 | 0.7456 | 0.5758 |
| Random Forest | 0.3275 | 0.2554 | 0.5053 | 0.8051 |

Random Forest Regression performed better than Linear Regression, achieving lower prediction errors and a higher R² score.

## Feature Importance

Feature importance was analyzed using the Random Forest model to understand which features contributed most to its predictions.

The feature importance results are also visualized as a bar chart in the notebook.

## Error Analysis

The project examined the largest prediction errors by comparing actual and predicted house values and calculating the absolute error.

## Final Prediction

The Random Forest model was used to generate a prediction for a sample residential area from the test set.

**Predicted House Value: 0.51**

## Conclusion

This project demonstrated how machine learning can be applied to house price prediction using residential and geographic features.

By training and comparing Linear Regression and Random Forest Regression models, I learned how different machine learning approaches can perform on the same prediction problem.

The project also provided practical experience with data exploration, data preparation, model training, evaluation, feature importance, error analysis, and interpreting machine learning results.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
