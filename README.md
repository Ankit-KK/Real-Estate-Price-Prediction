# Real Estate Price Prediction Using Machine Learning Techniques

![Alt text](https://github.com/Ankit-KK/Real-Estate-Price-Prediction/blob/main/mindmap%20(1).png)

## Introduction
In the ever-evolving real estate market, accurately forecasting property prices is paramount for stakeholders, including buyers, sellers, investors, and real estate professionals. This project seeks to harness the power of machine learning algorithms to create a robust predictive model for real estate prices. Utilizing a rich dataset that encompasses a wide range of property features—such as square footage, number of rooms, the presence of amenities (yard, pool, basement, attic, garage), and additional relevant factors—this project aims to uncover the underlying patterns and key determinants that influence property valuations.

## Libraries and Tools
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Support for large, multi-dimensional arrays and matrices.
- **Matplotlib**: Basic plotting library for creating static, animated, and interactive visualizations.
- **Seaborn**: High-level interface for drawing attractive statistical graphics.
- **Plotly Express**: High-level wrapper for Plotly to create interactive plots with minimal code.
- **Plotly Figure Factory**: Tools to create specialized plots.

## Data Description
The dataset consists of 10,000 entries with the following columns:
- `squareMeters`: The size of the property in square meters.
- `numberOfRooms`: Number of rooms in the property.
- `hasYard`: Binary column indicating if the property has a yard (1) or not (0).
- `hasPool`: Binary column indicating if the property has a pool (1) or not (0).
- `floors`: Number of floors in the property.
- `cityCode`: Code assigned to the city where the property is located.
- `cityPartRange`: A range or code representing a part of the city.
- `numPrevOwners`: Number of previous owners of the property.
- `made`: Year the property was made.
- `isNewBuilt`: Binary column indicating if the property is newly built (1) or not (0).
- `hasStormProtector`: Binary column indicating if the property has a storm protector (1) or not (0).
- `basement`: Binary column indicating if the property has a basement (1) or not (0).
- `attic`: Binary column indicating if the property has an attic (1) or not (0).
- `garage`: Binary column indicating if the property has a garage (1) or not (0).
- `hasStorageRoom`: Binary column indicating if the property has a storage room (1) or not (0).
- `hasGuestRoom`: Binary column indicating if the property has a guest room (1) or not (0).
- `price`: The market price of the property.

## Model Training
Various regression algorithms were used, including:
- Linear Regression
- Ridge
- Lasso
- ElasticNet
- Support Vector Regressor (SVR)
- Random Forest Regressor
- Gradient Boosting Regressor

The dataset was split into training and testing sets with an 80-20 ratio, and features were standardized using `StandardScaler`.

## Visualizations
Key visualizations include:
- Scatter plot between `squareMeters` and `price`.
- Bar plot showing average price by pool availability.

## Conclusion
The project successfully created a predictive model for real estate prices, with the size in square meters identified as the primary determinant of house price, while other factors had a relatively minor impact.

## Usage
To use this project, clone the repository and ensure you have the required libraries installed. Run the scripts to explore the data and visualize the insights.

```bash
git clone https://github.com/Ankit-KK/Real-Estate-Price-Prediction
cd Real-Estate-Price-Prediction
pip install -r requirements.txt
