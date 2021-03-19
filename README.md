# BACON

<b>B</b>in<b>A</b>ry <b>C</b>lassificati<b>O</b>n <b>N</b>etwork is a simple project inspired to the popular L-layer network devoloped as exercize during the famous Andrew Ng's course <i>"Neural Networks and Deep Learning"</i>. <br>
As the name says, the network can be used to perform binary classification. It exploits the RELU activation function for the first L-1 layers, while the sigmoid function is used in the latest neuron.
<br>
# Implementation
I tried to make it more object oriented than the original implementation, incapsulating the forward pass, the cost computation, the backward pass and the weights update in a class called "model".
<br>
# Experimentation
I tested some topology of network on two dataset, which you can find in the datasets folder: Catvnocat and Pima Indians Diabetes.
I got 80% test accuracy for the first dataset and 71% test accuracy for the second dataset. Obviously the results are not so exciting but this is only an exercize. Tuning the hyperparameters and normalizing the data could help in achieving better performance.
