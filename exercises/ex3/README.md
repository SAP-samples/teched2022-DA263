# Exercise 3 - Add a new node and re-run simulation

Duration: approx. 15 minutes

In this exercise, we will add a new influencer factor to the simulation model which should be considered in the simulations as well.
After completing these steps you will have extend the existing simulation model with a new node linked to an existing node and re-run the simulation.

## Exercise 3.1 Create new node with link

1. From the modelling view, navigate to the "Control" tab and create a new node labelled "GDP" of type "random_literal" with the min value 1.8 and max value 2.5, normally distributed.  If you want to know about GDP, read more [here](https://tradingeconomics.com/forecast/gdp-annual-growth-rate?continent=america). 
![](/exercises/ex3/images/ex3_1_1.png)

2. Add a link from the new created node to node XXX with the relationship of XXX. //RESEARCH  WHAT MAKES SENSE.
![](/exercises/ex3/images/ex3_1_2.png) //REPLACE

3. Name the adjusted model model like your user ID "DA263-XXX"" and save it.
![](/exercises/ex3/images/ex3_1_3.png) // REPLACE

4. You can now see GDP as influencer. To include the factor into the simulation re-run the simulation.
![](/exercises/ex3/images/ex3_1_4.png) // REPLACE

## Summary

You've now have included an new uncertainty to the simulations. 

Continue to - [Exercise 4 - Optimize outcome or compare outcomes](../ex4/README.md)