# MechaCar_Statistical_Analysis-

Summary:

This project was about how MechaCar performs against its competition. In the first part of the analysis, a linear regression model is used to see how vehicle length and weight, spoiler angle, ground clearance, and AWD affects its gas mileage. The intention is to see how each factor impacts mpg.

The second test, examines the statistical differences in the PSI of suspension coils from 3 different manufacturing lots. Then a t-test is used to determine if there are any significant statistical differences between the lots.

Linear Regression:

  Images:
  ![d1](https://user-images.githubusercontent.com/50600624/117625772-396bac80-b12b-11eb-816d-50827796f711.PNG)
  ![summary](https://user-images.githubusercontent.com/50600624/117627785-5acd9800-b12d-11eb-840c-dcb6a6861bc6.PNG)
  
  1. In linear regression analysis, one can see that vehicle length and ground clearance have a higher coefficient that can impact MPG on cars based on the p-values we generated.
  2. The slope isnt zero becuase the p value is 5.35 whihc is in the range of the .05 signifance level. 
  3. The model has a r value of .71 which is a high moderate correlation. The .29 maybe fro test factors for the day such as road conditions, driver, tire conditoins, weather, which can impact tire inflation. So the model is decent but a confidence interval test must be done to validated the model accuracy. 


Suspension Coil Summary:

![d2sum](https://user-images.githubusercontent.com/50600624/117627808-602ae280-b12d-11eb-9823-19f9c97f7a10.PNG)
![d2lotsum](https://user-images.githubusercontent.com/50600624/117627822-61f4a600-b12d-11eb-9d82-66da2e7aeb83.PNG)
![lot 3](https://user-images.githubusercontent.com/50600624/117627849-6751f080-b12d-11eb-814e-084ce41c3908.PNG)
![lot 1](https://user-images.githubusercontent.com/50600624/117627856-67ea8700-b12d-11eb-94dc-3295c68a2fcf.PNG)
![lot 2](https://user-images.githubusercontent.com/50600624/117627857-68831d80-b12d-11eb-8c4c-84b0b8359d06.PNG)
![t test full](https://user-images.githubusercontent.com/50600624/117627863-691bb400-b12d-11eb-93c1-0e44ab9bf241.PNG)


  The current design specs are not to exceed 100psi. If of the lots are averaged together the average comes to be around 70 psi. If lot 3 is looked at specifically though it would fail the manufactures criteria since that lots is around 117 psi. 
  
  The t tests show that lot one and 2 are nearly identical in terms of manufacturing but lot 3 is significantly different. 
  
  
Design Study: Mecha vs Competition

  To quatify how Mecha compares to its competitors in terms of value for its cost. The study could be set up by Mecha getting the same tpye of suspension part that is made by its competetiors. That part would be match up against one made by Mecha randomly selcted. Endurance test testing, stress tests and a technical analysis of the quality of the part would be done. Using a weighted measurment system with price being the heaviest weight the parts can be compared based on the test results. Serval questions will be asked for each of the weighted categories such as how much does the part cost, how long did it last in the endurance testing and stress testing. Then a hypothesis test would be done to detemrine the relability of said parts. Using that R value from that test then can be used to explain the value provided by mecha car parts compared to its competitors.
  
  Data required:
  The competitors parts would need to be sourced and than the data must be retrieved when the parts are tested. 
  
Challenges:

Loading the libraries was a bit difficult mostly due to hardware limitations. 
  
  
