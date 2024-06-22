# Real_Estate
A real estate price prediction application using dash framework
## Process
The dataset contains:

Transaction date: The date of the real estate transaction.

House age: Age of the house in years.

Distance to the nearest MRT station: Distance to the nearest Mass Rapid Transit station in meters.

Number of convenience stores: Number of convenience stores in the vicinity.

Latitude: Latitude of the property location.

Longitude: Longitude of the property location.

House price of unit area: House price of unit area.

![image](https://github.com/Koninikax/Real_Estate/assets/96631757/6e864b0c-d383-4cef-9c79-b3c21c5ef18c)

The histograms provide insights into the distribution of each variable:

House Age: This shows a relatively uniform distribution with a slight increase in the number of newer properties (lower age).
Distance to the Nearest MRT Station: Most properties are located close to an MRT station, as indicated by the high frequency of lower distances. There’s a long tail extending towards higher distances, suggesting some properties are quite far from MRT stations.
Number of Convenience Stores: Displays a wide range, with notable peaks at specific counts, like 0, 5, and 10. It suggests certain common configurations in terms of convenience store availability.
Latitude and Longitude: Both show relatively concentrated distributions, indicating that the properties are located in a geographically limited area.
House Price of Unit Area: Displays a right-skewed distribution, with a concentration of properties in the lower price range and fewer properties as prices increase.

![image](https://github.com/Koninikax/Real_Estate/assets/96631757/7dca8dd2-bda5-4920-b6b3-5ece54c4214a)

House Age vs. House Price: There doesn’t seem to be a strong linear relationship between house age and price. However, it appears that very new and very old houses might have higher prices.
Distance to the Nearest MRT Station vs. House Price: There is a clear trend showing that as the distance to the nearest MRT station increases, the house price tends to decrease. It suggests a strong negative relationship between these two variables.
Number of Convenience Stores vs. House Price: There seems to be a positive relationship between the number of convenience stores and house prices. Houses with more convenience stores in the vicinity tend to have higher prices.
Latitude vs. House Price: While not a strong linear relationship, there seems to be a pattern where certain latitudes correspond to higher or lower house prices. It could be indicative of specific neighbourhoods being more desirable.

![image](https://github.com/Koninikax/Real_Estate/assets/96631757/34b23743-c69e-416c-8ec9-0da3144aba1d)

House Age: This shows a very weak negative correlation with house price (-0.012), implying that age is not a strong predictor of price in this dataset.
Distance to Nearest MRT Station: Has a strong negative correlation with house price (-0.637). It indicates that properties closer to MRT stations tend to have higher prices, which is a significant factor in property valuation.
Number of Convenience Stores: Displays a moderate positive correlation with house price (0.281). More convenience stores in the vicinity seem to positively affect property prices.
Latitude and Longitude: Both show a weak correlation with house prices. Latitude has a slight positive correlation (0.081), while longitude has a slight negative correlation (-0.099).
## Building a regression model
![image](https://github.com/Koninikax/Real_Estate/assets/96631757/54d272ae-037f-460d-ad40-9c798c7f1e7a)
The diagonal dashed line represents where the actual and predicted values would be equal. Points close to this line indicate accurate predictions. From the plot, we can observe:

Many points are close to the diagonal line, suggesting that the model makes reasonably accurate predictions for a significant portion of the test set.
Some points are further from the line, indicating areas where the model’s predictions deviate more significantly from the actual values.

## Model

![image](https://github.com/Koninikax/Real_Estate/assets/96631757/9e96897b-7015-4cb7-b543-0e648192ff4a)


