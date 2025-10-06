# Reinforcement Learning for CarRacing-v2

This repository implements a reinforcement learning agent for the continuous control task CarRacing-v2, using PyTorch.
The goal is to train an agent that can learn effective driving strategies to complete randomly generated tracks while maximizing its cumulative reward.

# Problem Description
The CarRacing-v2 environment is a continuous control benchmark in the OpenAI Gym suite.
The agent must learn to steer, accelerate, and brake to navigate procedurally generated tracks. This task requires handling continuous action spaces, long-horizon planning, and balancing exploration with stable policy optimization.

The current implementation focuses on the TD3 (Twin Delayed Deep Deterministic Policy Gradient) algorithm.

An example of a trained agent driving behavior is shown below:

![Demo](src/video/demo.gif)

## Features
- PyTorch-based TD3 implementation for continuous control

Training and evaluation pipeline on CarRacing-v2