# Exercise 2 - Launch Business Decision Simulator and run simulations

Duration: approx. 15 minutes

In this exercise, you will run simulations in Business Decision Simulator to analyze how different influencers impact the probability of certain scenarios.
After completing these steps, you will have run several simulations and have the respective probability of the outcomes.


## Exercise 2.1 Load the simulation model into Business Decision Simulator.
1. You can launch the Business Decision Simulator either by navigating to the fourth page as it is embedded in SAP Analytics Cloud. But we recommend to launch the Business Decision Simulator [(Link)](/https://budesi-techedsac-da263.cfapps.eu12.hana.ondemand.com/) in a new tab due to caching issues.

2. Open the modelling view.
![](/exercises/ex2/images/ex2_1_1.png)

3. Navigate to MODELS tab and load the simulation model "spend_simulation_model".
![](/exercises/ex2/images/ex2_1_2.png)

4. Change the name of the simulation model according to you user ID "DA263-XXX", where XXX should be your specific number and save the simulation model.
![](/exercises/ex2/images/ex2_1_2_1.png)


> In case, the simulation model is not imported in the system, please follow the instructions below to upload it manually. 
> - Download the simulation model [here](/data/spend_simulation_model.json.json).
> - In the modelling view, navigate to MODELS tab and use the import functionality
![](/exercises/ex2/images/ex2_1_3.png)
> - Navigate to the downloaded file on your local environment and open file to upload.
![](/exercises/ex2/images/ex2_1_5.png)
> - Name the simulation model "DA263-XXX" and save it. The simulation model is successfully imported when it is listed under MODELS.
![](/exercises/ex2/images/ex2_1_4.png)

5. You see that the factors of "spend_data.xlsx" and "Focused_CPI_PPI.xlsx" are modelled as a knowledge graph. The knowledge is used to compute the probabilities of the scenarios. You can observe the simulation model by 
- zooming-in
- click on one node and see to which other node it is connected
- select one node via the drop-down menu and click EXECUTE to see the exact values of the selected node.

## Exercise 2.2 Change value of influencer and run simulations

1. Adjust the lower range of the BASE RESIN - PPI COEFFICIENT influencer to 0.3.
![](/exercises/ex2/images/ex2_2_1.png)

2. Make sure SAVINGS AMOUNT is selected as out variable and run the simulation.
![](/exercises/ex2/images/ex2_2_2.png)


3. The simulation is now executed and the results are displayed. Explore the details of the scenarios by expanding DETAILS section.
![](/exercises/ex2/images/ex2_2_3.png)

4. Take a moment to observe the results. What do you think?

## Exercise 2.3. Play around with the simulator
1. Now, it is time to play around with the simulation capabilities. Adjust the values of the influencers as you like, re-run the simulation and observe the outcome. For example, changing the COLOR MASTERBATCH slightly will have a significant impact on the probabilities of the realistic scenario.
![](/exercises/ex2/images/ex2_3_1.png)


## Summary

You've now run your first simulations.

Continue to - [Exercise 3 - Add a new node](../ex3/README.md)
