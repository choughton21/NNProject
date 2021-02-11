# NNProject
CHoughton's Neural Network Project

Battle Ship

I will use reinforcement learning to teach a computer to play battleship. The steps I plan to take/ goals are: 

1. Write battleship game in python
2. Make battleship game compatible with openai gym environment
 
3. Find a suitable reinforcement learning algorithm
   possibly a deep Q learning implementation will work
4. Get deep Q learning implementation working on machine with the default environment.
5. Modify the network of the deep Q learning implementation to work with battleship gym environment
   - change the dqn network to take battleship observations as input
   - set up reward from battleship to the dqn network
   (now the computer can learn)
   - connect output of dqn to gym environment so that it can take actions in my battleship game
6. Train, Evaluate, and update hyper-parameters 
   - One evaluation method: when the network plays a random agent, how often does it win?
7. Repeat step 6, trying to improve machine's ability to win battleship games

