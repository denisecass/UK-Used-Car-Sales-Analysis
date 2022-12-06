# UK Used Car Sales Analysis

**- Introduction -**

*Context:*
There are several key factors to consider when estimating used car sale prices. For instance, the model year is not linear- the closer we get to the current year, the price goes up significantly. Other important variables to consider are: engine size, MPG, mileage, fuel type, engine size, brand, and model. 

*Opportunity:*
How can One Track Motors increase profit margins by 5% within 6 months by establishing maximum buy prices on used cars according to their brand, model, year built, mileage and other factors?

*Deliverable:*
- Identify which variables are most important in determining price and how does price vary with them (linear, non-linear, etc.) 
- Regression model to predict price 

**- Dataset Description -**

The variables were extracted from a dataset consisting of 99,186 records for used car sales. 
*Numerical Variables:*
Year, Price, Mileage, Tax, MPG, Engine Size
*Categorical Variables:*
Brand, Model, Transmission, Fuel Type

**- Executive Summary -**
- The correlation for key variables determines that engine size and year/year adjusted are the highest contributing factors in determining a used cars' sale price.


- Engine Size (0.65) and Year (-0.03) lead the correlations, showing that they are key variables in determining the final price of a used car. Additionally, the price steadily increases with larger engine sizes and newer models.


- Price shows a strong positive correlation with models produced after 2003, while models from the same time span show the highest mileage records.


- MPG shows a negative correlation with price through 80 MPG, after which newer fuel types, primarily Hybrid, drive an increase in median price.


- Used cars with either very low (20) or very high (100+) MPG's have the highest price points, with all the values in between 30-90 MPG showing the lowest sale prices.


- Price shows quick decline in values that slowly levels off into an asymptote in relation to Mileage.


- Most used cars have average to low mileage numbers (3k-21k), and used cars with high mileage are most likely to have a petrol fuel type and made by the Ford brand.


- Manual with a median of (£11k) shows a sharp discount from Semi-Auto (£22k) and Auto (£21k). Ford, and Vouxhall are strong brands in Manual, while Merc, Audi, BMW, and Toyota are the big brands in Auto/Semi-Auto with VW being in both Semi-Auto and Manual. 


- Premium brands command a higher price premium over non-premium.


- Diesel and Hybrid are the highest price premiums at around £17k, while Petrol only has a median sales value of £12k, with Diesel and Petrol making up almost the entire dataset.


- The 6 top-selling models (Fiesta, Golf, Focus, C Class, Corsa, and Polo) make up more than half of the sales values for all models sold.


- The top 6 models with the highest sales prices (G Class, R8, X7, 8 Series, Q8, and California) belong to Merc, Audi, BMW, and VW brands.

**- Framework for Evaluation -**
- Correlation 


- Descriptive stats on numerical variables 


- Descriptive stats on categorical variables 


- Regression Numerical (Including categorical as dummy variables)


**- Summary of Key Findings -**

- Engine Size (0.65) and Year (-0.03) lead the correlations are key variables in determining the final price of a used car.
- Used cars with either very low (20) or very high (100+) MPG's have the highest price points, and average (30-90) MPG's show the lowest sale prices.
- Ford and Vouxhall are strong brands in Manual, while Merc, Audi, BMW, and Toyota are the big brands in Auto/Semi-Auto, with VW being in both Semi-Auto and Manual. 
- Diesel and Hybrid have the highest price premiums (£17k), while Petrol is the lowest (£12k).
- The top 6 models with the highest sales prices (G Class, R8, X7, 8 Series, Q8, and California) belong to Merc, Audi, BMW, and VW brands.
- Price predictions show a positive correlation (R^2 = 0.945) across all brand types, thus indicating that the regression model is a good fit.


**- Next Steps -**
- Focus on following brands that are Ford, Merc, Audi, BMW, and VW that have very low or very high mileage and are diesel, hybrid, or petrol fuel types.
- Use the regression model to predict used car sales prices and set new retail sales prices accordingly
