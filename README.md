## Sigma-Pi Neuron for XOR
This repository contains a Python implementation of a Sigma-Pi neuron used to model the XOR function. The neural network is visualized in 3D using matplotlib and mpl_toolkits.mplot3d for understanding how the Sigma-Pi neuron interacts with the XOR inputs.

# Overview
The Sigma-Pi neuron is a type of artificial neuron that can model complex logic functions such as XOR. The network includes a multiplicative interaction term, in addition to the usual linear summation of inputs, which is crucial for solving non-linear problems like XOR.

In this project:

A Sigma-Pi neuron is used to predict the output of XOR for different combinations of inputs.

A 3D plot is generated to visualize the decision surface of the neuron.

The plot includes:

A scatter plot of the XOR input points with labels indicating their (x1, x2) coordinates and corresponding output.

A decision surface that separates the two output classes (0 and 1).

# Requirements
To run the code, make sure you have the following Python libraries installed: numpy, matplotlib

# 3D Plot
The code generates a 3D plot using matplotlib:

Scatter plot: The XOR inputs are plotted, colored according to their output (blue for output=1, red for output=0).

Decision surface: The decision boundary of the Sigma-Pi neuron is plotted in 3D, using the output of the neuron for a grid of input points.

# Legend
A legend is included to differentiate the outputs in the plot:

Blue represents Output = 1

Red represents Output = 0

![image](https://github.com/user-attachments/assets/fc91358f-f36a-417a-a814-5c85079a379f)

# Contributions
Feel free to fork the repository and contribute by opening issues or submitting pull requests.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
