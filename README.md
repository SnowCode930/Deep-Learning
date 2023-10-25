
### Summary

#The target accuracy of 75% will be attempted in this analysis. I made 3 attempts with an accuracy off 72.71%, 72.67% and 72.81%
#Results from each model attempt are detailed below:

##1 - First attempt: 2 layers 72.65% of the model’s predicted values align with the dataset’s true values.
#The hyperparameters used were: layer1 = 8 neurons : activation function = ‘relu’ layer2 = 17 neurons : activation function = ‘relu’ epochs = 100

##2 - Second attempt: added a hidden layer 72.67% of the model’s predicted values align with the dataset’s true values.
#The hyperparameters used were: layer1 = 15 neurons : activation function = ‘relu’ layer2 = 22 neurons : activation function = ‘relu’ layer3 = #32 neurons : activation function = ‘relu’ epochs = 25

##3 - Third attempt: 3 layers, changing the activation function for layers 1 and 2 72.81% of the model’s predicted values align with the #dataset’s true values.
#The hyperparameters used were: layer1 = 18 neurons : activation function = ‘tanh’ layer2 = 38 neurons : activation function = ‘sigmoid’ layer3 #= 45 neurons : activation function = ‘relu’ epochs = 100


#Although my attempts did not make the 75% target accuracy the final attempt results were the most accurate. I retained the 100 epochs from the #first attempt and added neurons to all 3 layers.

