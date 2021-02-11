# NNProject
CHoughton's Neural Network Project

Battle Ship

I will use deep learning to teach a computer to play battleship. The steps I plan to take/ goals are: 
1. Write battleship game in python
2. Make battleship game compatible with openai gym
   - launce fastai deep learning rainbow dqn, launches cartpool
  change this so the input to network is to battleship game and it will expect atari and I will need to change it to text based thing. So that it connects action of network to the battleship environment and when says x, we do x)
  run and see if this works
3. Deep Q learning 
      - is a model-free deep learning, and it works by having the network estimate the value of a board state, is it a board that is about to win (high value) give you this board state, game is just begun (less valuble), etc.)
      - make decisions to get closer to winning boards (will look at the value of each board action possible and then look at the highest q value and take that action, then . 
4. Evaluate and keep repeating steps: How long are the games? When plays a random agent, how often does my machine win?
