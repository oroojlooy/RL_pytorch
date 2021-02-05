# RL_pytorch
An implementation of DQN algorithm via pytorch to use multiple gpu in a single node. I use `DataParallel` API for this purpose.
The REINFORCE/Actor-Critic algorithm works only with CartPole. 

The `general_dqn` is a general DQN algorithm for any non-image env, and it is possible to define fully connected layer of any size. 
The `reinforce_AC_CartPole_torch` notebook, includes a naive implementation of `REINFORCE`, `REINFORCE` with `Reward to Go`, `AC`, and `AAC` algorithms. 

