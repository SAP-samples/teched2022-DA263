# Exercise 2 - Launch Business Decision Simulator and run simulations

Duration: approx. 15 minutes

In this exercise, you will run simulations in Business Decision Simulator to analyze how different influencers impact the probability of certain scenarios.
After completing these steps, you will have run several simulations and have the respective probability of the outcomes.


## Exercise 2.1 Load the simulation model into Business Decision Simulator.
1. In [Business Decision Simulator](https://budesi-techedsac-da263.cfapps.eu12.hana.ondemand.com/) open the modelling view.
![](/exercises/ex2/images/ex2_1_1.png)

2. Navigate to MODELS tab and load the simulation model "placeholder_simulation_model". //REPLACE NAME OF MODEL?
![](/exercises/ex2/images/ex2_1_2.png)


> In case, the simulation model is not imported in the system, please follow the instructions below to upload it manually. 
> - In the modelling view, navigate to MODELS tab and use the import functionality
![](/exercises/ex2/images/ex2_1_3.png)
> - Navigate to the downloaded file on your local environment and open file to upload.
![](/exercises/ex2/images/ex2_1_5.png)
> - Name the simulation model XXX and save it. The simulation model is successfully imported when it is listed under MODELS.
![](/exercises/ex2/images/ex2_1_4.png)

3. You see that the factors of "spend_data.xlsx" are modelled as a knowledge graph. The knowledge is used to compute the probabilities of the scenarios. You can observe the simulation model by zooming-in or you can select one node and see to which other node it is connected.

## Exercise 2.2 Change value of influencer and run simulations

1. Adjust data range of the BASE RESIN - PPI COEFFICIENT influencer to 0.3 by entering the value in the text field. //PROVIDED A FIRST HAPPY PATH TO INTRODUCE THE TOOL?
![](/exercises/ex2/images/ex2_2_1.png)

2. Run the simulation.
![](/exercises/ex2/images/ex2_2_2.png)


3. The simulation is now executed and the results are displayed. Explore the details of the scenarios by expanding DETAILS section.
![](/exercises/ex2/images/ex2_2_3.png)

4. Take a moment to view the results. What do you think?

## Exercise 2.3. Play around with the simulator
1. Now, it is time to play around with the simulation capabilities. Adjust the values of the influencers as you like, re-run the simulation and observe the outcome.
![](/exercises/ex2/images/ex2_3_1.png) For example, changing the values of  have a huge impact on the probabilities of the scenarios. 


## Summary

You've now run your first simulations.

Continue to - [Exercise 3 - Add a new node](../ex3/README.md)
