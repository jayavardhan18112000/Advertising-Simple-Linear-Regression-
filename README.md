# Advertising Sales Analysis

This project involves the analysis of advertising data and the development of a predictive model for sales based on advertising expenditures. The dataset used in this analysis contains information on advertising spending across different media channels (TV, radio, newspaper) and their corresponding sales figures.

## Data Exploration and Preprocessing

- Loaded the dataset using `pd.read_csv`.
- Checked the columns and data types using `df.columns` and `df.info()`.
- Checked for missing values using `df.isna().sum()`.

## Data Visualization

- Visualized the correlation between variables using a heatmap.
- Created scatter plots to visualize the relationships between advertising spending (TV, radio, and newspaper) and sales.
- Used `sns.pairplot` to create pairwise scatter plots for all variables.

## Data Preprocessing

- Removed the 'Unnamed: 0' column as it was unnecessary.
- Described the dataset using `df.describe()`.

## Model Training and Evaluation

- Split the data into training and testing sets using `train_test_split`.
- Trained a linear regression model using scikit-learn's `LinearRegression`.
- Calculated and printed the model's intercept and coefficients.
- Made predictions on the test set and calculated evaluation metrics: MAE, MSE, and R-squared.

## Visualization of Predictions

- Created a DataFrame (`comparision_df`) to compare actual and predicted values.
- Plotted the distribution of sales predictions using a distribution plot.
- Created a scatter plot to compare actual vs. predicted values with different colors.

The analysis revealed strong linear relationships between sales and advertising spending on TV,radio and Newspaper. Almost the predicted values are very near to orignal values.  This proved that linear regression helps to predict the sales.
