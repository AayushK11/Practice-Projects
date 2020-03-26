The Model predicts the output of the AND gate using Momentum Optimization.

Model description:

3 input nodes (Because of the 3 input AND gate),

30 hidden nodes in the first layer,

20 hidden nodes in the second layer,

10 hidden nodes in the third layer,

5 hidden nodes in the fourth layer and

1 output node (Because AND gate gives only 1 output)

All the layers except the last use "ReLU" activation. The last layer uses "sigmoid" activation.

Accuracy is near perfect.

Weights are initially randomized and Bias are initially set to 0. Dataset is pre-inputted. The learning rate and epochs the model should learn are user-inputted. Dataset is divided into mini-batches of size 1. Momentum Optimization is used
