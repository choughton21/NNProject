# NNProject
CHoughton's Neural Network Project

Battle Ship

I will use deep learning to teach a computer to play battleship. The steps I plan to take/ goals are: 

1. Write battleship game in python
2. Make battleship game compatible with openai gym environment
 
3. Find a suitable reinforcement learning algorithm
   possibly a deep Q learning implementation will work
4. Get deep Q learning implementation working on machine with the default environment.
5. Modify the network of the deep Q learning implementation
   - change the dqn network to take battleship observations as input
   - set up reward from battleship to the dqn network
   (now the computer can learn)
   - connect output of dqn to gym environment so that it can take actions in my battleship game
6. Tweak Deep Q network implementation to work with battleship gym environment
7. Train, Evaluate, and update hyper-parameters 
8. Repeat step 5, trying to improve machine's ability to win battleship games

Take existing Deep Q learning 
      - is a model-free deep learning, and it works by having the network estimate the value of a board state, is it a board that is about to win (high value) give you this board state, game is just begun (less valuble), etc.)
      - make decisions to get closer to winning boards (will look at the value of each board action possible and then look at the highest q value and take that action, then . 
4. Evaluate and keep repeating steps: How long are the games? When plays a random agent, how often does my machine win?
