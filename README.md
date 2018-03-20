# Reinforcement-Learning-TicTacToe
An implementation of an algorithm that plays TicTacToe. The algorithm is based in reinforcement learning, using the Monte Carlo Algorithm.

Author: Oliver Zhang <br>
Last Modified: 3/19/18

Goal: Learn how to play Tic Tac Toe. I'm using the implementation of
TicTacToe by nczempin:
https://github.com/nczempin/gym-tic-tac-toe/blob/master/gym_tic_tac_toe/envs/tic_tac_toe_env.py#L1
 
# Overall Design:
I use Monte Carlo Learning to train a model which predicts the value of an 
action given a state. Observation is the board state. My code then makes every possible move,
and picks the best resulting board state.

Then it can learn from its wins/losses and figure out which board state is actually the best.
 
For learning reinforcement learning, I suggest David Silver's youtube lectures
https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PL7-jPKtc4r78-wCZcQn5IqyuWhBZ8fOxT

# How to Run:
1. Copy the files tic_tac_toe_env.py and ExperiencedTTTAI.py to your computer.
2. Add the TicTacToe environment to your gym. Check here for more details: https://github.com/openai/gym/wiki/Environments
3. Modify path variable to point to a folder for saving weights.
4. Run it on python3.

# Options:
1. By changing 'debug' variable to true, you can print debugging information.
2. By changing 'display_img' variable to true, you can visualize what your program is doing.

Note: This version is pretty messy; I will be cleaning up the code in the future.
