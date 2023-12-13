# orbital-decay-rl
Reinforcement Learning for Orbital Decay Final Project for EN.525.637.81.FA23 Foundations of Reinforcement Learning

### Project Abstract

In very low Earth orbit (VLEO), satellites must compensate for the effects of orbital decay to stay in orbit by applying occasional propulsive bursts. How a satellite applies these bursts can be considered a controls problem where the satellite must maintain a stable orbit for as long as possible before running out of fuel. This paper attempts to address the problem of orbital decay from a reinforcement learning approach to generate an optimal, fuel-efficient control policy to compensate for the effects of orbital decay. A reinforcement learning environment is constructed in python to model and simulate exaggerated orbital decay scenarios. Two standard reinforcement learning algorithms, Q-Learning and N-step SARSA, are used to train policies in this environment, and initial results are presented and analyzed.

### Project Conclusion

In this paper the application of reinforcement learning to the problem of controlling a satellite undergoing orbital decay is presented. Utilizing a custom reinforcement learning physics environment for orbital decay, two algorithms, Q-Learning and N-step SARSA, are applied to the problem to learn optimal control policies to maintain the orbit of a satellite. Only the results for the Q-Learning algorithm are obtained. The results are compared to the baseline and far exceeded the expectations of the team and of the baseline, but these results are not enough to confirm the hypothesis that RL can be used to maintain a stable orbit, nor do they confirm the use of RL for generating the optimal, fuel-efficient controls to maintain a stable circular orbit. The hypothesis is not yet achieved, but much work can be done to improve future results.

The next step for future work would be to reincorporate a reward to promote more circular orbits. Training the policy with more episodes also sounds appropriate since neither of the results seemed to plateau. Fixing the N-step SARSA code to work and running bootstrapping would also improve the results. Additionally, it would be nice to have a better graphical representation of the policy to better understand what it is actually learning. Finally, the simulation can be improved to slowly incorporate more realistic physics such as better drag dynamics or more realistic masses and distances. 

### Personal Note
This is some of the most disgusting code I have written, but I got the job done in time. I intend to separate the code into actual files and have it run on the command line instead of a notebook, and to clean the code to make the gym environment easier to run and train on with various algorithms.
