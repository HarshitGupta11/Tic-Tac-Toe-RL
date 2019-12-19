# Tic-Tac-Toe-RL
This project uses Reinforcement Learning to train a software agent play tic-tac-toe from scratch. It uses Game Theory,Minimax Theory and Temporal Difference Learning.
<br/>
The agents learns to play tic-tac-toe by playing against each other. Both the agents are trying to maximize rewards and trying to win against one another.The q-values of each state and action are stored and later used to play the game.
<br/>
<br/>
## There are two versions of this game :
**Simple** :We visit all the states and actions and take actions based on the q-values.<br/>
**Exploring Starts**: During the start of the game the agent trys to take random actions but as the training proceeds or the agent matures the number of random actions taken by the agent are reduced. This helps to get to the states which
could not have been reached if only q-values were considered.This also provides stability and faster convergence.<br/>
