# RL Tutorial
by Diana Borsa

_Designed for education purposes. Please do not distribute without permission_.

**Questions/Correspondence**: 2018tmlss@gmail.com

_Special thanks to_: Hado van Hasselt, Matteo Hessel

## Content
In this tutorial, we will investigate the properties of 4 distinct reinforcement learning algorithms:

* Policy Evaluation
* Online Control: SARSA, Q-learning
* Experience Replay
* REINFORCE Algorithm

Some dimensions of the RL problems we will be considering:

* Tabular vs Function Approximation
* Off-policy/On-policy Control
* Online vs Replay
* Exploration vs Explotation

## Background reading
* Sutton and Barto (2018), Chapters 3-8
* RL Basics lecture notes (@Lucian, @Doina)

## Objectives
You will use Python to implement several reinforcement learning algorithms. Only the second part will deal with functional approximation for which we will be using neural networks to approximate value functions and policies.

You will then run these algorithms on a few problems, to understand their properties and different emerging behaviour. In this tutorial we will focus primary on fundamental algorithms in RL and explore them in a simple gridworld setting. That being said, these are algorithms that have now been shown to scale very well with (non-linear) functional approximations.
