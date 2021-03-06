This project demonstrates a network with 5 inputs, two fully connected hidden layers with 25 and 8 nodes and 5 output nodes. 

![Block diagram of system](https://github.com/cceroici/Stochastic-Neural-Network/blob/master/FullyConnectedSNN/readmeImages/fullyConnectedParallel.png?raw=true)

To run the project in ModelSim, navigate to the .../FullyConnectedSNN/ directory and run the compilation + simulation macro file with: "do nn.do"

The waveform window will show the training progress including the netowork parameters and stochastic error:

![Image of Training Window](https://github.com/cceroici/Stochastic-Neural-Network/blob/master/FullyConnectedSNN/readmeImages/trainingProgress.jpg?raw=true)


The project can also be compiled for an FPGA with some modification of the top-level TOPsim.v file.

