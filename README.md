# FinalRLmario - This is a mario game in which we try to make the computer learn and play on its own, with the help of reinforcement learning thus clearing the 1st level by itself.
  We first install the gym-super-mario-bros, an opemAI environment for the original Super Mario Bros.
  We dont incorporate all the movements, but only simple-movements including 7 of them.
  Now, we want to display frame by frame, with movements, using javascript animation.
  Finally then we apply the concept of reinforcement learning, including Q learning and double Q learning. In which environment takes the next action based on       given policy and it uses epsilon-greedy action selection for this. Then we calculate and minimise the loss and update the target.
  At last, we try to run the algorithm as many times as possible to increase the accuracy of the model, keeping the track of the progress, thus finally showing     the developed model.
