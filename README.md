# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
  -For this project, I created a linear model that would predict the miles per gallon(mpg) of the Mechacar prototypes. I used vehicle leength, weight, the spoiler angle, ground clearance and all wheel drive(AWD) as indepenedent variables. THis is illustrated with the screenshot below:
  
![image](https://user-images.githubusercontent.com/101299252/180668927-dc01cce5-cd23-42ea-b414-88a97c080716.png)

  -When it comes to the Vehicle length and ground clearance, these were the two variables that created a non-random amount of variance to the miles per gallon values within the datasheet.
  -Furthermore, the slope of the linear modes is a nonzero number. This in part to the p-value of the model which was smaller than the level of significance. This provides evdence that the null hypothesis is not true.
  -Lastly, with the r-squared value being .715, this means there is at least a 71.5% chance that the future points with fit this model. This results in the linear model not properly predicting the miles per gallon of the prototypes.

## Summaryy Statistics on Suspension Coils 
  -Two data frames were created for this deliverable, both highlighted the statistics about the suspension coil's PSI across the 3 manufactering lots.With the specifications of the suspension coils to not exceed 100 pounds per square inch, the data that was gathered shows that the current maufactering is able to meet this demand. When it comes to the individual specifications, lots 1 and 2 are able to keep up with specifics while lot 3 is unable too. This highlighted by the variance of 1.15 for lot 1 and 10.13 for lot 2 whereas lot 3 has a variance of 220.1 which doubles the inital specification. 
  ![image](https://user-images.githubusercontent.com/101299252/180670676-ed29d200-089b-4596-9c7a-e1ff049314df.png)
  ![image](https://user-images.githubusercontent.com/101299252/180670691-5ae1ea17-f60f-4966-ad13-8cb298915c08.png)
  
## T-Tests on the Suspension Coils
  -T-tests were performed on each individual lot to determine if the populations within those lots differ or are the same from the popuilation mean of 1500 pounds per square inch; with my null hypthesis stating that there was no difference while the alternative being that there is a statistical difference. One of the outcomes of this tests was that the p value for all of the lots resulted in 0.51 which can lead the conclusion being tthat there is not enough statistics to reject the null. The conclusion to this test means that all of the lots are not statisticall different from the population mean. The images below highlight each lot.
T-Test for all lots:
 ![image](https://user-images.githubusercontent.com/101299252/180671097-a628db79-dacf-4a19-a473-238213cf9fef.png)
 
Lot 1 T-Test
![image](https://user-images.githubusercontent.com/101299252/180671131-50aafe55-2f56-4908-a20d-5357db672315.png)

Lot 2 T-Test
![image](https://user-images.githubusercontent.com/101299252/180671149-a04e4c4b-769e-4b90-8950-75f5619b30bc.png)

Lot 3 T-Test
![image](https://user-images.githubusercontent.com/101299252/180671168-0300f923-1771-4b97-a902-cabaefab499c.png)

## Study Design: MechaCar vs Competition
  - A study that I would like to preform would try to determine if we are able to predict the values of matenience by using a linear model and the cost value. By comparing mateninece and cost we would be able to determine the proper ratio in order to have the best outcome. This would be a good comparison with the competition becuase it can highlight profit margins that the company would be able to visually see as well as through an organized lense, they would be able to create the appopriate actions in order to get the company there as a whole. 
  When it comes to the design, I would use the R-Squared value in order to predict that the future data would compare to the linear model. My null hypothesis would be that the slope of the linear model would be 0; and my alternative would be that the slope of the linear model woul
