# California-Housing-Prices-Prediction-using-Random-Forest

This project aims to predict housing prices in California using machine learning techniques, specifically a **Random Forest Regressor** model. The dataset contains various features of houses, such as the number of rooms, latitude, longitude, median income, and other demographic information, which are used to predict the median house value.

## Dataset

The dataset used for this project is the **California Housing Prices** dataset, available on Kaggle. You can download it from the following link:

[California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices))

Once you download the dataset, make sure to place it in the same directory as the script or update the file path in the script accordingly.

## Key Features

- **Longitude**: Longitude of the house location.
- **Latitude**: Latitude of the house location.
- **Housing Median Age**: Median age of the houses in the area.
- **Total Rooms**: Total number of rooms in the house.
- **Total Bedrooms**: Total number of bedrooms in the house.
- **Population**: Population of the area.
- **Households**: Number of households in the area.
- **Median Income**: Median income of the area’s residents.
- **Ocean Proximity**: Proximity of the house to the ocean (categorical feature).

## Model and Evaluation

- **Model**: Random Forest Regressor
- **Evaluation Metric**: The model's performance is evaluated using the **R-squared** score and **Mean Squared Error (MSE)**.
- **R-squared**: The R-squared value of the model is approximately **0.81**, indicating a relatively good fit to the data.
- **MSE**: The Mean Squared Error is used to assess the accuracy of the predictions.
