# LeslieSaltDataSet

In 1968, the city of Mountain View, California began the necessary legal proceedings to acquire
a parcel of land owned by the Leslie Salt Company. The Leslie property contained 246.8 acres
and was located right on the San Francisco Bay. The land had been used for salt evaporation and
had an elevation of exactly sea level. However, the property was diked so that the waters from
the bay park were kept out. The city of Mountain View intended to fill the property and use it for
a city park.
Ultimately, it fell into the hands of the courts to determine a fair market value for the property.
Appraisers were hired, but what made the processes difficult was that there were very few sales
of a byland property and none of them corresponded exactly to the characteristics of the Leslie
property. The experts involved decided to build a regression model to better understand the
factors that might have influenced the market valuation. They collected data on 31 byland
properties that were sold during the last 10 years. In addition to the transaction price for each
property, they collected data for a large number of other factors, including size, time of sale,
elevation, location, and access to sewers. A listing of these data, including only those variables
deemed relevant for this exercise. A description of the variables is provided below.

Variable name  | Description
------------- | -------------
Price  | Sales price in $000 per acre
County  | San Mateo=0, Santa Clara =1
Size  | Size of the property in acres
Elevation | Average Elevation in foot above sea level
Sewer | Distance (in feet) to nearest sewer connection
Date | Date of sale counting backward from currenttime (in months)
Flood | Subject to flooding by tidal action =1;otherwise =0
Distance | Distance in miles from Leslie Property (inalmost all cases, this is toward San Francisco

Answer the following questions:
1. What is the nature of each of the variables? Which variable is dependent variable and
what are the independent variables in the model?
2. Check whether the variables require any transformation individually
3. Set up a regression equation, run the model and discuss your results
