The Model predicts the output of the OR gate using Dropout.

Model description:

2 input nodes (Because of 2 input features),

20 hidden nodes in the first layer,

50 hidden nodes in the second layer,

30 hidden nodes in the third layer,

20 hidden nodes in the fourth layer and

1 output node (Because OR gate gives only 1 output)

All the layers except the last use "ReLU" activation. The last layer uses "sigmoid" activation.

Error Percentage is comparatively less than the Model without Regularization and with Regularization.

Weights are randomized and Bias are initially set to 0. Dataset is pre-inputted. The learning rate and number of times the model should learn are user-inputted. Keep Probab is user-inputted.
