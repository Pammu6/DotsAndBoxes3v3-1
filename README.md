# DotsAndBoxes3v3
We have implemented a 3 player version of the Dots and Boxes game. This game starts with an empty grid of dots. In this implementation 3 players take turns to add a single horizontal or vertical line in the grid, between two dots which are already not joined. Any player who completes the fourth side of the box earns one point and then takes another turn. This game will end when there are no more lines which can be placed in the grid and the player with maximum points wins the game.

We have implemented minimax tree search algorithm for 3 players and have also implemented a neural network model using 4 configurations:

1. Model with Adam (adaptive learning rate optimization algorithm) & Tanh (Activation function)
2. Model with Adam (adaptive learning rate optimization algorithm) & ReLU (Rectified Linear Unit for activation function)
3. Model with SGD (Stochastic Gradient descent algorithm) & Tanh (Activation function)
4. Model with SGD (Stochastic Gradient descent algorithm) & ReLU(Rectified Linear Unit for activation function)

Steps to run this notebook:

Sign into https://colab.research.google.com/ and upload this notebook.
Click on Runtime -> Run all cells

This project is implemented as a term project for CIS 667 - Intro to AI by :

Husen Bhagat
Kartheek Sunkara
Pranav Kulkarni
Sreekar Reddy Sykam
