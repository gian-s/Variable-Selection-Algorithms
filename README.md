# Variable-Selection-Algorithms
Iterative algos for selecting significant variables for linear regression


# R Functions For Variable Selection 

### Forward Algorithm:
Begin with a Null Model, create n models for each n variable. Perform t-test for signifigance on each model and choose the most significant variable, and add it the null model. Remove the variable and continue algorithm for remiaining variables until there are no more significant variables in all models.

### Backward Algorithm:
Begin with a Full Model. Perform t-test for signifigance for individual variables in model and choose the least significant variable, and remove it from full model. Remove the variable and continue algorithm for remiaining variables until all the variables are significant. 
