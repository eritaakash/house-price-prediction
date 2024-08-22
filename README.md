## House Price Prediction 

This project involves a Linear Regression Model developed to predict house prices based on various features of a property. It contains a Linear Regression Model trained on [Kaggle's "House Price India" Dataset](https://www.kaggle.com/datasets/sukhmandeepsinghbrar/house-prices-india/data)


### Overview 

The goal of this project is to accurately predict the prices of houses using features such as the number of bedrooms, bathrooms, living area, lot area, and more. The model provides insights that can help real estate agents, buyers, and sellers make informed decisions.


#### Key Features:
- Number of Bedrooms
- Number of Bathrooms
- Living Area
- Lot Area
- House Condition
- House Grade
- Age of the House
- Proximity to Amenities (e.g., schools, airport)


### Model Performance 

The model achieved a Root Mean Squared Error (RMSE) of **0.488** on the test dataset, indicating its strong performance in predicting house prices.

Here is the report of different metrics:
```
[1]: R² Score                 0.7632692907451433
[2]: Mean Squared Error       0.23862629978013955
[3]: Mean Absolute Error      0.3773077204256993
[4]: Root Mean Squared Error  0.48849390966535045
```


### Dataset Details:
- Number of Instances: 14619

- Number of Features:
- - 23 [Before Preprocessing]
- - 16 [After Preprocessing]

- Target Variable: `price`
- - 100k units [Before Preprocessing]
- - 1k units [After Preprocessing]


### Conclusion

This Linear Regression model provides an effective tool for predicting house prices in India. By using relevant features and robust preprocessing techniques, the model achieves high accuracy, making it valuable for various stakeholders in the real estate industry.


### Acknowledgements

Thanks to [Sukhmandeep Singh Brar](https://www.kaggle.com/datasets/sukhmandeepsinghbrar/house-prices-india/data) for providing the dataset on Kaggle.