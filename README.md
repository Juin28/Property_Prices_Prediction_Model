# Property Price Prediction Model

This is a property price prediction model developed using the Keras library of TensorFlow. The model aims to predict the sale price of homes based on various features, including the date of registration in the Land Registry, property type, number of bedrooms, building age, and more.

## Dataset
The dataset used for this project includes 29 features and 1,139 observations. Each observation represents the sale of a home, and each feature describes an attribute of the house or the circumstances of the sale. The features include:

- Register date in Land Registry
- Type of the property
- Number of bedrooms
- Building age at registration
- Sale price
- Number of primary schools near the property
- Number of shopping malls near the property
- Latitude and longitude of the property

## Visualization
The distribution of the sale prices in the dataset is visualized below:

![Sale Price Distribution](https://github.com/Juin28/Property_Prices_Prediction_Model/blob/b33cef4bccc482e841d2e092669387725f033da7/images/price.png?raw=true)

## Model and Performance
The property price prediction model was compiled using the Keras library of TensorFlow and utilized the Adam optimizer. Without fine-tuning, the model achieved a Mean Absolute Error (MAE) of 70.

The graph below shows the actual sales prices and the model's predictions:

![Actual vs. Predicted Prices](https://github.com/Juin28/Property_Prices_Prediction_Model/blob/b33cef4bccc482e841d2e092669387725f033da7/images/graph.png?raw=true)

The model appears to predict prices accurately for properties below 150,000,000 HKD. However, the accuracy decreases for properties above that price range.

## Acknowledgments
This project was developed as part of the COMP2211 course at the Hong Kong University of Science and Technology (HKUST) in Spring 2024. Special thanks to the teaching team for their guidance and support.