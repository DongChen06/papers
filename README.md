# Papers
Papers related to machine learning, deep learning and reinforcement learning

## Contents
* [Reinforcement Learning](#reinforcement-Learning)
  * [Single Agent](#single-agent)
    * [Survey](#survey)
    * [Value-based](#value-based)
    * [Policy-based](#policy-based)
  * [Multi Agent](#multi-agent)
    * [Survey](#survey)
    * [Value-based](#value-based)
    * [Policy-based](#policy-based)


# Reinforcement Learning

## Single Agent
### Survey

### Value-based

- **DRQN: Hausknecht, Matthew, and Peter Stone. "Deep recurrent q-learning for partially observable mdps." arXiv preprint arXiv:1507.06527 (2015).**
> To explore well in the particial observed environment, this article investigates the effects of adding recurrency to a Deep Q-Network (DQN) by replacing the first post-convolutional fully-connected layer with a recurrent LSTM. 


### Policy-based


## Multi Agent

### Survey

### Value-based
- **VDN: Sunehag, Peter, et al. "Value-decomposition networks for cooperative multi-agent learning." arXiv preprint arXiv:1706.05296 (2017).**
> novel learned additive value-decomposition approach over individual agents. Implicitly, the value decomposition network aims to learn an optimal linear value decomposition from the team reward signal, by back-propagating the total Q gradient through deep neural networks representing the individual component value functions. 

- **DIAL: Foerster, Jakob, et al. "Learning to communicate with deep multi-agent reinforcement learning." Advances in neural information processing systems. 2016.**
> DQN, parameter sharing: the message is generated together with action-value estimation by each DQN agent, then it is encoded and summed with other input signals at the receiver side. Dial pushes gradients from one agent to another through the communication channel.


### Policy-based

- **ConsensusNet: Zhang, Kaiqing, et al. "Fully decentralized multi-agent reinforcement learning with networked agents." arXiv preprint arXiv:1802.08757 (2018).**
> Actor-Critic: the actor step is performed individually by each agent without the need to infer the policies of others. For the critic step, each agent shares its estimate of the value function with its neighbors on the network, so that a consensual estimate is achieved, which is further used in the subsequent actor step.

- **NeurComm: Chu, Tianshu, Sandeep Chinchali, and Sachin Katti. "Multi-agent Reinforcement Learning for Networked System Control." arXiv preprint arXiv:2004.01339 (2020).**
> Actor-Critic: introduce a spatial discount factor to stabilize training, especially for non-communicative algorithms. We propose a new neural defferentiable communication protocol to adaptively share information on both system states and agent behaviors. 

