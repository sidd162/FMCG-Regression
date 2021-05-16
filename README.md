Problem Statement:
An FMCG brand X is available at a large number of stores. The brand is available as a basic version X and in the form of some value-added variants. The price of the brand X can vary from store to store depending on the discounts / promos that the store is offering. In some stores there are special displays for the brand X.
Weekly Sales of Brand X is given for 3238 stores
In addition to Sales, the following information are also given
- Price: Avg price of Brand X in that store
- Feature: Whether value-added variant of Brand X is present in the store (1) or not (0)
- Display: Whether any store level promo of  Brand X is present in the store (1) or not (0)
- Price-Competitors: Prices of 5 competition brands in the store have been given also.
Train-Test split : 70:30 Create a model(using Training set) to predict future sales Use this model to predict future sales (in Test set) and then compare the “Predicted Sales” with the “Actual Sales”
The model will be tested by evaluation metric Adjusted R-sq Mean Absolute Error (MAE)
