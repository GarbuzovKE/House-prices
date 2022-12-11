# House-prices
This project is about predicting prices for houses in Ames, Iowa. Original kaggle competition is here https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques. 
The features engeneering includes:
- **Imputing missing** values by proceeding sequentially through the data
- **Transforming** some numerical variables that seem really categorical
- **Label Encoding** some categorical variables that may contain information in their ordering set
- **Box Cox Transformation** of skewed features.
- **Getting dummy variables** for categorical features. 

Then i chose base models, cross-validated them on the data and stacked them. Base models are robust to outlies via Robust scaler.
