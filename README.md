# Prediction-of-Product-Sales
A sales prediction tool for food items sold at various stores.

By: Kirsten Casteel

## Business Purpose
***The purpose is to utilize past data to make future sales predictions using the CRISP-DM process***

## Visualization 

*The following graph shows the various items and the count of those items sales. This gives insight in to what categories of items produce the most/least sales as well as providing quick visibility of our items popularity.*

![Type vs Sales](https://github.com/KirstenC32/Prediction-of-Product-Sales/assets/145694223/aa56791d-4f85-4a36-956a-7698b2c1c77d)


*The following heatmap indicates any correlations in our numerical data This allows us to quickly identify relationships between variables. For example, we may want to explore the correlation between sales and item visibility.* 

![Heat Map Sales Prediction Data](https://github.com/KirstenC32/KirstenC32/assets/145694223/a6c02c03-3925-4cf7-b479-4f782a1bbdc1)

*The following plot shows us that item visibility is very important in product sales. It shows the more visible, the more likely there will be a sale.*

![Visibility graph](https://github.com/KirstenC32/Prediction-of-Product-Sales/assets/145694223/e455b9b2-7b57-474d-8547-43295b511c7c)


*This is the LinearRegression coefficients plot. The top 3 important coefficiants are Outlet_Type_Grocery Store, Outlet_Identifier_OUT027, and Outlet_Type_Supermarket Type3.*

![Actual coefficiant graph](https://github.com/KirstenC32/Prediction-of-Product-Sales/assets/145694223/dda1ebc5-6211-4ff5-bb8d-ce37b381493c)


*This is the  tree-based model's feature importances. The top 5 are Item_Visibility, Item_MRP, Outlet_Type_Grocery Store, Outlet_Establishment_Year and Outlet_Identifier_OUT027*

![Features real](https://github.com/KirstenC32/Prediction-of-Product-Sales/assets/145694223/97825a23-d840-44fb-b51d-4382bab9b72d)



## Recommendations:

I would reccomend using the tuned random forest model for determining product sales. This model is performing well about 69% of the time.
The MAE lets us know that our predictions are off by about 733.11 dollars on average. ` I think this model is close to balanced between testing and training, maybe slightly underfit.

## Limitations & Next Steps


## For further information
For any additional questions, please contact kccasteel32@gmail.com
