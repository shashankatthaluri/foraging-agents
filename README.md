# 🐜 Ants: Epistemic Structures and Q-Learning 🐜
Welcome to the mesmerizing world, This project extends the exploration to understand how ants generate stable structures in their environment, reducing cognitive load while foraging. It utilizes the Q-learning algorithm to model this behavior and mirrors the intricate dance of ants in forming epistemic structures.

## Key Findings 📝

- Ants strategically deploy and follow pheromone trails as memory aids.
- Random exploration proves valuable for discovering new, rewarding areas.
- Maintaining an optimal exploration rate is pivotal for balancing exploitation vs. exploration.


## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Agents](#agents) 
- [World](#world)
- [Q-Learning Algorithm](#q-learning-algorithm)
- [Experimental Conditions](#experimental-conditions)
- [Analysis](#analysis)
  - [Actions](#actions)
  - [Trips](#trips)
  - [Correlations](#correlations)
  - [Transition Matrices](#transition-matrices)
- [Results](#results)
- [Conclusion](#conclusion) 
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)

## 🧑‍💻 Project Overview

Embark on a journey to uncover the mysteries of exploration strategies in reinforcement learning for multi-agent foraging. 🕵️‍♂️ Agents employ Q-learning to strategically lay pheromone markers, creating a web of guidance for their peers. What secrets lie within these interactions? Let's find out! 🚀

## 🐜 Agents

Meet our agents, the unsung heroes of this exploration! 🌟 Each agent, driven by the spirit of ants, detects home and food pheromones, making decisions to drop, follow, or move randomly. 🤖💨 Their independent learning through Q-learning without communication adds a layer of complexity to this multi-agent foraging system. 

## 🌎 World 

Picture a vast 50x50 grid adorned with randomly scattered homes and food sources, echoing the complexity of an ant colony. 🐜🌌 Agents, starting from their homes, embark on a quest to efficiently navigate to food using pheromones as their guiding light.

## 📊 Q-Learning Algorithm

Witness the power of Q-learning as agents independently learn optimal policies, updating Q-values based on rewards and discounts from each step.

## 🧪 Experimental Conditions

We throw our agents into the crucible of experimentation, testing four main conditions with variations in exploration rates and a daring strategy of replacing the worst-performing agent each iteration. Will the chaos yield surprising revelations? 🤯🤔

## 🧮 Analysis

Let's dissect the intricate details! A meticulous analysis awaits on the distribution of actions, successful trips, Pearson correlations, and state/action transition matrices. 📊✨ Unraveling the patterns within the chaos, we seek to understand the underlying dynamics.

## 📈 Results 

Surprising revelations emerge! Contrary to expectations, random actions surpass systematic pheromone actions. The Q-table functions more as condensed experience than a decision support. Condition 4, with agent replacement, emerges victorious. The unexpected is the new norm! 🎉🔍

## 🏁 Conclusion

In the grand finale, we unveil the revelation that the Q-table functions as an experience memory in a stochastic world filled with other agents. Random exploration becomes the unsung hero, aiding agents in effectively navigating their surroundings. 🤯🚀

## 🚧 Future Work

As we bid adieu to this chapter, the path ahead beckons. Future work holds promises of larger worlds, non-grid environments, decentralized learning methods, and continuous action spaces. The journey never truly ends! 🌌🌠

## 🙏 Acknowledgements

A heartfelt thank you to our guiding light, the advisor Prof. Sanjay Chandrasekharan, HBCSE, TIFR, MUMBAI, INDIA. Whose wisdom illuminated the path of this exploration! 🌟🙌
