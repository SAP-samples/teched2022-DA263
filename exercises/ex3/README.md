# Exercise 3 - Add a new node and re-run simulation

Duration: approx. 15 minutes

In this exercise, you will add a new influencer factor to the simulation model which should be considered in the simulations as well. After completing these steps, you will have extend the existing simulation model with a new node linked to an existing node and re-run the simulation.

## Exercise 3.1 Create new node with link

1. From the modelling view, navigate to the CONTROL tab and add a new node labelled "Interest Rate" of type "range value" with the min value equal "0.025" and max value equal "0.0325", normally distributed. Click [here](https://tradingeconomics.com/united-states/interest-rate) to find out more information about interest rates.
![](/exercises/ex3/images/ex3_1_1.png)

2. As we added a new uncertainty, we need to update some existing nodes to ensure the interest rate will be included into the simulations. In the CONTROL tab, choose UPDATE NODE to update the INTERIM node. It should be of type MULTIPLICATION and has edges to ACTUAL PLANT/ CAPITAL COST and INTEREST RATE.
![](/exercises/ex3/images/ex3_1_2.png) 

3. Next, update the CAPITAL/ FIXED COST node by changing the dividend to PLANT/ CAPITAL COST.
![](/exercises/ex3/images/ex3_1_3.png) 

3. Save the adjusted simulation model.
![](/exercises/ex3/images/ex3_1_4.png) 

4. You can now see interest rate as influencer on the left side. Re-run the simulation to include the factor into the outcomes.
![](/exercises/ex3/images/ex3_1_5.png) 


> In case, adding the new influencer does not work, please follow the instructions below to upload it manually. 
> - Download the simulation model [here](/data/spend_simulation_model_interest_rate.json).
> - In the modelling view, navigate to MODELS tab and use the import functionality
![](/exercises/ex2/images/ex2_1_3.png)
> - Navigate to the downloaded file on your local environment and open file to upload.
![](/exercises/ex2/images/ex2_1_5.png)
> - Name the simulation model according to your user ID "DA263-XXX" and save it. The simulation model is successfully imported when it is listed under MODELS.
![](/exercises/ex2/images/ex2_1_4.png)


## Summary

You've now included a new uncertainty to the simulation model. 

Continue to - [Exercise 4 - Optimize outcome or compare outcomes](../ex4/README.md)