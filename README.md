# Backpack Price Prediction 🏷️🎒

## Aim 🎯
The aim of this project is to predict the price of backpacks based on various features such as brand, material, size, compartments, style, and other attributes. By building a predictive model, we aim to identify patterns and relationships in the data that can help estimate the price of backpacks based on their characteristics. This model can be used by manufacturers, retailers, or customers to make informed decisions about pricing.

## Dataset 🗂️
The dataset contains the following columns:

- **id**: A unique identifier for each backpack.
- **Brand**: The brand name of the backpack (e.g., Jansport, Nike, Adidas).
- **Material**: The material used to make the backpack (e.g., Leather, Canvas, Nylon).
- **Size**: The size of the backpack (e.g., Small, Medium).
- **Compartments**: The number of compartments in the backpack.
- **Laptop Compartment**: Indicates whether the backpack has a compartment for a laptop (Yes/No).
- **Waterproof**: Indicates whether the backpack is waterproof (Yes/No).
- **Style**: The style or type of backpack (e.g., Messenger, Tote).
- **Color**: The color of the backpack (e.g., Black, Green, Red).
- **Weight Capacity (kg)**: The maximum weight the backpack can hold (in kilograms).
- **Price**: The price of the backpack (target variable).

## Models Tested 🧑‍💻
We evaluated multiple machine learning algorithms to predict the price of backpacks. The models tested include:

- Gradient Boosting
- Ridge Regression
- Linear Regression
- ElasticNet
- Lasso
- XGBoost
- Random Forest
- KNeighbors
- Decision Trees
- Extra Trees

## Results 📊
- **Top Performers**: Gradient Boosting, Ridge, and Linear Regression performed similarly, achieving R-squared values close to 0.001 and relatively low RMSE and MAE values.
- **Poor Performers**: Tree-based models, such as Random Forest and Extra Trees, performed poorly with R-squared values in the negative range.
- **Deep Learning**: Deep learning produced a lower R-squared score of -0.0047, indicating it was less effective in capturing patterns compared to traditional machine learning models.
- **Best Conclusion**: Traditional machine learning models like Gradient Boosting and Ridge performed the best for predicting backpack prices.

## Conclusion 🏁
In conclusion, **Gradient Boosting** and **Ridge** regression emerged as the most suitable models for predicting backpack prices. Deep learning models did not offer significant improvements in this case. The project demonstrates that simpler, traditional machine learning techniques are more efficient and accurate for this task.

## Kaggle Notebook Link 🔗
You can access the original Kaggle notebook here: [Backpack Price Prediction](https://www.kaggle.com/code/senasudemir/backpack-price-prediction)
