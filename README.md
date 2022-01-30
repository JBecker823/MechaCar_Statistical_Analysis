# MechaCar_Statistical_Analysis

Summary 

## Summary Statistics on Suspension Coils

The Suspension Coil CSV was converted into a dataframe. Then it was used to create two subset tables: Total Summary and Lot Summary. The Total Summary table is looking at PSI statistics across all lots, while the Lot Summary shows statistics of each lot. Lot 1 and Lot 2 are very similar while Lot 3 has a smaller mean with a bigger variance and standard deviation. 

<img width="1009" alt="Total_Summary SS" src="https://user-images.githubusercontent.com/91567484/151718918-f010a7ca-4833-4fbe-974d-05828efe05a9.png">
<img width="1007" alt="Lot_Summary " src="https://user-images.githubusercontent.com/91567484/151718922-4c81aa9d-45aa-46b2-b18e-6a5eb00ce583.png">

## T-Test on Suspension Coils

The P-values from single T-Test on PSI values verse the standard of 1500 PSI for suspension coils were: All PSI = .06028 Lot 1 PSI = 1, Lot 2 PSI = .6072 & Lot 3 PSI = .04168. 
Assuming that the significant value should be below p = 0.05, standard deviation, then only Lot 3 is significantly different. All other lots perform the same, not significantly different, to the standard 1500 PSI. The difference from Lot 3 with the lower mean of Lot 3 and high variance, could indicate that Lot 3 is under-performing. 

<img width="1012" alt="Test Lot 3 Suspencion Coils p1" src="https://user-images.githubusercontent.com/91567484/151718934-0556138a-4f81-44ea-8144-689eed370836.png">
<img width="1004" alt="T-test All lot p2" src="https://user-images.githubusercontent.com/91567484/151718938-c44b08e7-3f83-46c9-848c-659b5f694650.png">
<img width="1004" alt="T-test all Lots p3" src="https://user-images.githubusercontent.com/91567484/151718939-f5fd7fe6-a5f7-4221-a32d-7e01d4211c3c.png">

## Summary 

According to the analysis, the major impacts of MPG are spoiler angle, car wight, and AWD capability. This would mean for any improvement on the MPG of the MechaCar, the car engineers would have to consider these variables. Also, when looking at the suspension coils, Lot 3 has the most variance and lower PSI average. Lot 3 should not be used within the MechaCar. 

Study Design: Competition VS MechaCar

The most efficient way to compare MechaCar to its competition would be the use the ANOVA test. This test can compare the MechaCar in various categories that customers would care about the most. These would include cost, city and highway fuel efficiency, horsepower, safety rating, and maintenance cost. The ANOVA test can test to check if the mean from multiple samples is significantly similar or different. This means that eh averages of different cars in these categories can be compared to the average of MechaCar. 

If the P-Value is greater than 0.05, then the MechaCar has the same or similar performance with these categories. This would also be the null hypothesis. If the P-Value is less than 0.05, then MechaCar is significantly different in the stated categories. If it is significantly different, then looking at the average of the MechaCar is the next step. If Machacar’s average is below or above, the other averages would show how it is performing against the competitors. A rating of below would mean it is performing worse, and a rating of above would mean it is performing better.  
