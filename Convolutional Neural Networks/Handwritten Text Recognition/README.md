The program identifies the handwritten digit with close to 99% accuracy.



Dataset Used - Mnist imported from Keras



Optimizer used - Adam



Epochs - 20



Batch Size - 250



Accuracy - 99%



Architecture - 

Conv Layer1 - 16 filters, 3x3 filter size, Stride of 1 and Same Padding 

Conv Layer2 - 16 filters, 3x3 filter size, Stride of 1 and Same Padding

Max Pool Layer1 - Pool Size of 2x2 and Stride of 2

Conv Layer3 - 32 filters, 3x3 filter size, Stride of 1 and Same Padding 

Conv Layer4 - 32 filters, 3x3 filter size, Stride of 1 and Same Padding

Max Pool Layer2 - Pool Size of 2x2 and Stride of 2

Conv Layer5 - 64 filters, 3x3 filter size, Stride of 1 and Same Padding 

Conv Layer6 - 64 filters, 3x3 filter size, Stride of 1 and Same Padding

Max Pool Layer3 - Pool Size of 2x2 and Stride of 2

Fully Connected Layer 1 - 500 Nodes, Relu activation

Fully Connected Layer 2 - 250 Nodes, Relu activation.

Fully Connected layer 3 - 10 Nodes, Softmax activation.
