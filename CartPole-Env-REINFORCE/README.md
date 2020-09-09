## CartPole Environment - REINFORCE

REINFORCE algorithm is based on finding the **local maximum** of a function using a procedure known as **gradient ascent**.

<img src="https://github.com/ashutoshtiwari13/Unity-PyBullet-DRL-Hub/blob/master/CartPole-Env-REINFORCE/output/sim-1.gif" height="425px" width="380px" hspace="20"/><img src="https://github.com/ashutoshtiwari13/Unity-PyBullet-DRL-Hub/blob/master/CartPole-Env-REINFORCE/output/sim-2.gif" height="425px" width="400px"/>

## Class Policy

This class implements the simple Convolution Neuron Network (CNN) model containing only 2 fully-connected levels. In this CNN model, the function __reinforce()__ approximizes the return value (= sum of all rewards with discounts).
The environment is solved in 791 episodes!

## Training log

Episode 100	Average Score: 34.47   
Episode 200	Average Score: 66.26   
Episode 300	Average Score: 87.82   
Episode 400	Average Score: 72.83   
Episode 500	Average Score: 172.00   
Episode 600	Average Score: 160.65    
Episode 700	Average Score: 167.15   

<p align="center">
<img src="https://github.com/ashutoshtiwari13/Unity-PyBullet-DRL-Hub/blob/master/CartPole-Env-REINFORCE/output/plot_791.png" height="425px" width="380px"/>
</p>   

Environment solved in 791 episodes!	Average Score: 196.69   
