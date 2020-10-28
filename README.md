# AutosRUs’ MechaCar

## Linear Regression to Predict

-	Vehicle length and ground clearance have a correlation with the car and mpg
-	The slope is not 0 and shows a positive slope with about 70% of the data points falling on the line
-	This model shows statistical significance with mpg and its relation to aspects of the car.  Shape and wind resistance on the car make sense as to why they would have an impact on how on the mpg of the car.

![Linear Regression](/Images/Linear_Regression.PNG)

## Summary Statistics on Suspension Coils

-	The design of all the cars meet the requirement of not exceeding 100 pounds per square inch.  However the manufacturing lot 3 cars surpass that requirement by 100.  Further analysis could be done to see if the weight/length of the car is related to lot 3 car’s PSI being higher then the recommended variance.

![Lot Summary](/Images/Lot_Summary.PNG)
![Total Summary](/Images/Total_Summary.PNG)

## T-Tests on Suspension Coils

-	With PSI across all manufacturing lots and each lot individually, there is no statistical difference from the population mean of 1,500 pounds per square inch.

![All Lots](/Images/All_Lots.PNG)
![Lot 1](/Images/Lot1_TTest.PNG)
![Lot 2](/Images/Lot2_TTest.PNG)
![Lot 3](/Images/Lot3_TTest.PNG)

## Study Design: MechaCar vs Competition

To test MechaCar versus the competition I believe we should focus on reliability/safety rating, fuel efficiency, maintenance cost/cost effectiveness, and technology rating. The null hypothesis would be that there is not statistical difference between the cars and the alternative would be that there is any kind of significance and difference in the cars.  I would use independent sample t-tests to compare the mean scores on the categories listed above. Ratings, mpg for highway and roads, and costs comparisons and maintenance costs would  need to be collected to compare with MechaCar.

## Resources
- Data Source: MechaCar_mpg.csv, Suspension_Coil.csv
- Software: R, R Studio
