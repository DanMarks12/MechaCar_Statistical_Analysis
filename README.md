# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
AWD, spoiler angle and vehicle weight all provided a non-random amount of variance. This means that ground clearance and vehicle length provided the most amount of random variance. 

### Is the slope of the linear model considered to be zero? Why or why not?
Our slope is not zero. We can tell this because the relationship between our linear regression formula and Y intercept does not equal zero. 

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
To determine if our linear model can predict MPG of MechaCar prototypes we need to look at our R squared value. At 71% we can see it can predict the mpg 71% of the time. Although this is not that close to 100%, it is still a decent prediction tool. To get closer we would need to look at other variables that affect MPG in MechaCar protoypes.

## Summary Statistics on Suspension Coils
### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
Lot 1 and Lot 2 are both within design specifications and have the same mean and median. Lot 3 shows more variance and exceeds the given manufacturer design specifications. 


## T-Tests on Suspension Coils
### LOT 1
![](https://github.com/DanMarks12/MechaCar_Statistical_Analysis/blob/main/JPGs/Lot1_Ttest.JPG)

Lot 1 the p-value is 1 which is over .05 so we cannot reject the null hypthesis. 

### LOT 2
![](https://github.com/DanMarks12/MechaCar_Statistical_Analysis/blob/main/JPGs/Lot2_Ttest.JPG)

Lot 2 the p-value is .6072 which is over .05 so we cannot reject the null hypthesis. 

### LOT 3
![](https://github.com/DanMarks12/MechaCar_Statistical_Analysis/blob/main/JPGs/Lot3_Ttest.JPG)

Lot 3 the p-value is .04 which is under .05 so we can reject the null hypothesis. This result is statistically significant, and our test hypothesis is false.


## Study Design: MechaCar vs Competition
The biggest factors consumers think about when buying a car are price, mpg, and horsepower. There are obviously other factors such as brand value, color, year, style but at a statistical standpoint mpg and horsepower and price are main purchasing factors. We can assume that mpg and horsepower remains constant across the same models of cars, but we could perform statistical analysis to determine if our prices for these 2 variables (mpg and horsepower) have any statistical significance compared to a competitor. Our first steps would be collecting similar data from competitor lots, and then running a t-test to compare our vehicles to those of our competitor. This could be a simple comparison but if our hypothesis is rejected (that there is no difference between us and competitors) there is more tests we could perform)

In addition we could perform an ANOVA test using MPG and look categorically at our cars vs our competitor cars. This would mean looking at sedans, SUV, sports cars, trucks etc. and using a single dependent variable (MPG). By performing an ANOVA test we can look at all car types categorically and tell which groups there is a statistical significance. Our null hypothesis would state that there is no difference between us and the competitor and we would look which groups we are able to reject that hypothesis. 

