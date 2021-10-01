# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![MechaCar deliverable 1](https://user-images.githubusercontent.com/86164867/135530659-c9246042-72c6-4714-8ad7-a6a5bd89304d.PNG)

1. Vehicle length and ground clearance are both statistically unlikely to provide random amounts of variance to the mpg values in the dataset, thus they are likely to have a significant impact on MPG
2. The p-value is 5.35e-11, which is much smaller than the 0.05% significance level. This provides suffcient evidence to reject the null hypothesis that the slope of the line is equal to zero.
3. This linear model does not effectively predict MPG of MechaCar prototypes because onloy two of the five variable show statistical significance. This is evidence of overfitting and means that the model fails to generalize and predict future data.

## Summary Statistics on Suspension  Coils
![coil_summary](https://user-images.githubusercontent.com/86164867/135538934-46cb5e3b-84df-46db-95af-ec47c05ae21c.PNG)
![lot_summary](https://user-images.githubusercontent.com/86164867/135538946-2b9d1091-82cf-472f-affa-82580397627e.PNG)

Lots 1 and 2 meet the design specifications of a variance that does not exceed 100 psi, with respective variances of 0.98 and 7.47 psi. Lot 3 far exceeds the design specification with a variance of 170.29 psi.  Assuming that the lots are the same size, the total variance of all lots is 89.37 psi, which does not exceed the design specifications.

## T-Tests on Suspension Coils
![full_population_ttest](https://user-images.githubusercontent.com/86164867/135669131-4bd1a9b8-5a77-4519-b94c-dc617accf916.PNG)
