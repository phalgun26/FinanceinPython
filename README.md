## Predicting Housing Prices in the Netherlands

This project analyzes a dataset of housing prices in the Netherlands to build a predictive model for asking prices. The dataset, sourced from Funda, contains various features of properties, including location, type of building, number of rooms, living area size, energy label, and more.

The project follows these key steps:

1.  **Data Loading and Preprocessing:** Load the dataset and preprocess the data by cleaning, transforming, and encoding categorical features.

2.  **Feature Engineering:** Create new relevant features from existing ones to improve model accuracy.

3.  **Model Selection and Training:** Select appropriate machine learning models (Decision Tree and Random Forest) and train them on the preprocessed data.

4.  **Hyperparameter Tuning:** Optimize the models' hyperparameters using GridSearchCV to enhance performance.

5.  **Evaluation and Insights:** Evaluate the models' performance using metrics like MAE, MSE, RMSE, and R-squared. Gain insights into the data and model predictions through visualizations.

**Key Findings:**

*   The Random Forest model outperforms the Decision Tree model in predicting asking prices, achieving an MAE of 47,838 and an R-squared of 0.8284.

*   The most important features for predicting asking prices are `Living_AreaSize(m2)`, `price_per_m2`, and `Location`.

*   The distribution of asking prices is right-skewed, with most properties clustered at lower prices and a few high-priced outliers.

*   There is a strong positive correlation between living area and asking price, as shown in the scatter plot and the correlation matrix.

*   Average asking prices vary significantly across provinces, with Noord-Holland having the highest average price, and Limburg having the lowest average price.

*   Different building types also exhibit varying average asking prices, with villas having the highest average price and gallery flats having the lowest average price.

This project demonstrates the application of machine learning techniques to predict Dutch housing prices and provides valuable insights into the factors influencing the Dutch housing market.

**Note:** Due to the provider's terms of use, the dataset used in this project cannot be shared publicly.
