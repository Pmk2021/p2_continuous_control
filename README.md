# p2_continuous_control
Project 2 for the Deep Reinforcement Learning Course on Udacity

## Environment
Each state is represented by an array with a length of 33. There are 20 agents in the environment in order to increase the speed that it takes to gather trajectories. This is helpful with certain algorithms such as PPO, which require a large number of trajectories to train.

There are 4 continuous actions. They control 2 joints and have to be between -1 and 1.

The goal of the agent is position the end of the arm to be inside of the target area.

The environment is considered solved, when the agent achieves an average reward of 30 over 100 episodes and all agents

## Getting Started
To start, you need to download the environment by clicking on the link.

Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip

Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip

Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip

Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip

Then after downloading the repository, unzip the file into the folder, making sure the file name in the second cell of reacher.ipyb matches the download
