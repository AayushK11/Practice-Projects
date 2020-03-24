The Model predicts the output of the OR gate

Model description: 2 input nodes (Because of 2 input features), 10 hidden nodes in the first layer, 7 hidden nodes in the second layer, 5 hidden nodes in the third layer, 3 hidden nodes in the fourth layer and 1 output node (Because OR gate gives only 1 output)

The reason for such a high percent of error is because the data size is really small and on such a small dataset with the output being between 2 choices i.e. Binary, Logistic Regression works the best.

Weights are randomized and Bias are initially set to 0. Dataset is pre-inputted. 
The learning rate and number of times the model should learn are user-inputted.
X and Y for predicting is user-inputted
