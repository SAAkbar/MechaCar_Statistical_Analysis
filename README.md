# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/76131315/114327593-b04f5e80-9b07-11eb-8462-80c5599315fc.png)

Looking at the results above, we can see that Vehicle Length and Ground Clearance had a P-valves of 2.60e-12 and 5.21e-08, respectively, which are both under 0.05 and therefore both have a statistically significant impact on MPG. The p-value for the intersect is also below 0.05 as it is 5.08e-08 and there for we reject the null hypothesis that the slope is zero, meaning the slope of the linear model is not zero. Lastly, we can say that this linear model can predict the mpg of MechaCar prototypes effectively, as the r-squared is 0.7149 which means that the model accounts for a significant amount of variance.

## Summary Statistics on Suspension Coils

### Total Summary
![image](https://user-images.githubusercontent.com/76131315/114327615-c6f5b580-9b07-11eb-8dc2-2f33ed7b1cec.png)

### Lot Summary
![image](https://user-images.githubusercontent.com/76131315/114327638-e4c31a80-9b07-11eb-988f-68b0dd5d20b2.png)

When looking at the Total Summary table we can see that the variance is 62.29356 which is under 100 PSI and therefore it meets the design specifications, but looking deeper in the Lot Summary only lot 1 and 2 meet the specifications with variances of 0.9795918 and 7.4693878 respectively but lot 3’s variance is larger than the design specifications with a variance of 170.2861224 and therefore does not meet the design specifications.

## T-Tests on Suspension Coils

### T-Test Results
![image](https://user-images.githubusercontent.com/76131315/114327679-0f14d800-9b08-11eb-9c5a-61f598e47be1.png)

When looking at the T-test for al the lots we can see that the sample mean is 1498.78 and the p-value is 0.06028, now the p-value is larger than 0.05 so we cannot reject the null hypothesis which in this case is that the true mean is equal to 1500. The same can be said when looking at the T-test for lots 1 and 2, lot 1 had a sample mean of 1500 and a p-value of 1 which again is larger than 0.05 so we cannot reject the null hypothesis and with lot 2 the sample mean was 1500.2 and p-value of 0.6072 which is also bigger. In lot 3’s T-test the sample mean is 1496.14 and the p-value is 0.04168, now while this might look like it fits in with the others as it too has a sample close to 1500, the p-value is smaller that 0.05 so according to the T-test it is significantly different than 1500 and we can reject the null hypothesis.

## Study Design: MechaCar vs Competition 

In our consumer driven world, the most important thing a product could have is to have a competitive and fair  price or even below the competitors, even is some of the features are below the competition if the price is competitive and fair or even below the competitors then people would still buy the AutoRUs’ prototype, and if the features are the same or better but the price is competitive and fair or even below the competitors then more people will defiantly buy the prototype, therefore it would be best to compare the price. When doing this the null hypothesis would be that the AutoRus’ prototype the MechCar is similarly priced to its competitors. The alternative hypothesis is that the MechCar is not similarly priced compared to the competitor. The best way to do test this is a T-Test since we are looking to see if there is a significant difference in prices or not. Finally, the data we need is the prices at which the MechCar is being sold as well as the price of the competitor’s car that is comparable to the MechCar i.e., if the MechCar is a sports car we need the price of the competitor’s newest sports car. Then of course we would need to take the p-values to see the results.
