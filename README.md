# MechaCar_Statistical_Analysis
M15

### Deliverable 1 Written Summary

- vehicle_length and ground_clearance provided a non-random about of variance to the mpg values in the the dataset
- The slope of the linear model is not considered to be zero. See the vehicle_length and ground_clearance provide a positive slope.
- This linear model does predict mpg of MechaCar prototypes effectively. The Multiple R^2 is 5.35e-11, smaller than 0.5.

## Summary Statistics on Suspension Coils

- Overall, cars's PSI has a mean of 1498.78, median of 1500, with variance of 62.29356 and s.d. of 7.892627. Specifically, Lot 1 has variance of 0.9795918 with s.d. of 0.9897433; Lot 2 has 7.4693878 with 2.733; Lot 3 of 170.2861224 with 13.0493725.
- Overall, the currently manufacturing data meet this design specification with exception of Lot 3. Lot 3 experiences high variance PSI, which exceeds 100 pounds per square inch.

## T-Tests on Suspension Coils

- Overall across 3 lots, 1500 is within the CI of the PSI, with p-value=.06.
- In Lot1, 1500 is within the CI of the PSI, with p-value=1.
- In Lot2, 1500 is within the CI of the PSI, with p-value=0.6.
- In Lot3, 1500 is outside the CI of the PSI, with p-value=0.04.
