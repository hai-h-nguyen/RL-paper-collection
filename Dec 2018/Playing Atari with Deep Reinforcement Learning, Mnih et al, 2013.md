Reward signals in RL: sparse, noisy and delayed
Using: experience replay and target network to stabilize the learning
Single neural network to play several games (same architecture + hyperparameters)

Loss function is different in supervised learning. Target is dependent on the weights.
DQN is model-free and off-policy.
epsilon-greedy strategy: follow the greedy strategy with probability 1 - epsilon, select random action at probability epsilon

Success of TD-gammon (learn the state value function + on-policy)

restricted Boltzman machine???


deep autoencoder?

experience replay and replay memory. 

DQN works on fixed-length representation of histories produced by a function Phi.

Problem of on-policy learning:
Third, when learning on-policy the current parameters determine the next
data sample that the parameters are trained on