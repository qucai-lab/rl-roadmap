<!-- Badges: -->
[![Contributions](https://img.shields.io/badge/contributions-welcome-orange?style=flat-square)](https://github.com/qucai-lab/rl-roadmap/pulls)
[![License](https://img.shields.io/github/license/QuCAI-Lab/rl-roadmap.svg?logo=CreativeCommons&style=flat-square)](https://github.com/qucai-lab/rl-roadmap/blob/main/LICENSE.md)

<!-- Logo: -->
<div align="center">
  <a href="https://qucai-lab.github.io/">
    <img src="https://github.com/qucai-lab/qucai-lab.github.io/blob/main/assets/QuCAI-Lab.png" height="500" width="500" alt="Logo">
  </a>
</div>

<!-- Title: -->
<div align="center">
  <h1><b> Reinforcement Learning Roadmap </b></h1>
</div>
<br>

<!-- ################################################################################################################################################ -->

# About

Resort to the references section for the mainstay textbooks in reinforcement learning \[[1](#1)] and deep learning \[[2](#2)].

<!-- ################################################################################################################################################ -->

# Algorithms

Resort to the [rl-theory.ipynb](/theory/rl-theory.ipynb) notebook for an introduction to the RL framework.

- [VPG](algorithms/vpg/vpg.ipynb).
- [DDPG](algorithms/ddpg/ddpg.ipynb).
- [TRPO](algorithms/trpo/trpo.ipynb).
- [PPO](algorithms/ppo/ppo.ipynb).

<!-- ################################################################################################################################################ -->

# Theory

- **Math Notation**
- **The RL Framework/Problem**
- **Glossary**
    - Learning frameworks
    - Markov Decision Process (MDP)
    - Markov Chain
    - Agent, Environment and Model
    - Agent types
    - Environment types
    - State space and Observation
    - Action space
    - State transition probability distribution
    - History/Trajectory/Episode/Rollout
    - Horizon and Experience
    - Reward signal, Reward function and Return
    - Policy
    - Value Functions
    - Bellman Equations
    - Advantage Function
    - Exploitation vs Exploration: the RL tradeoff
    - $\epsilon$-greedy policy
    - Importance sampling
    - Bootstrapping
    - Deadly triad issue
- **Taxonomy (extended)**
    - Model-based RL
    - Model-free RL
    - Dynamic programming methods
        - Policy Iteration
        - Value Iteration
            - Q-learning
        - Modified Policy Iteration
    - Policy optimization methods
        - Derivative-free Optimization
        - Policy Gradient
    - Deep RL
        - Deep Q-Network (DQN)
        - Actor-Critic Methods
- **Open Challenges in RL**
    - Sparse rewards
    - Alignment problem
- **Policy Optimization Algorithms**
    - Derivative-free Optimization Algorithms
        - Cross Entropy Method (CEM)
    - Policy Gradient Algorithms
        - Introduction
    - Actor-Critic Algorithms
        - Introduction
- **Avoiding memory bottlenecks in deep neural networks**
- **References**

<!-- ################################################################################################################################################ -->

# References 

<a name="1"></a> \[1] "Reinforcement Learning: An Introduction." Richard S. Sutton and Andrew G. Barto. Cambridge, MA: The MIT Press, March 22, 2018, 548 pp.
    
- Complementary materials: 
    - Courses
        - [UCL COMPM050/COMPGI13 (2015): RL by David Silver](https://www.davidsilver.uk/teaching/).
        - [UC Berkeley CS285 (Fall 2022): Deep RL by Sergey Levine](http://rail.eecs.berkeley.edu/deeprlcourse/).
        - [Deep RL Bootcamp, Berkeley CA](https://sites.google.com/view/deep-rl-bootcamp/lectures).
        - [Spinning Up in Deep RL](https://spinningup.openai.com/en/latest/).
    - Thesis
        - [John Schulman's PhD Thesis](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2016/EECS-2016-217.html).
    - Papers
        - [Williams, R.J. Simple statistical gradient-following algorithms for connectionist reinforcement learning. Mach Learn 8, 229–256 (1992).](https://doi.org/10.1007/BF00992696)

<a name="2"></a> \[2] Deep Learning (Ian J. Goodfellow, Yoshua Bengio and Aaron Courville), MIT Press, 2016.

<!-- ################################################################################################################################################### -->

# License

This work is licensed under a [Creative Commons Zero v1.0 Universal](LICENSE.md) license.
