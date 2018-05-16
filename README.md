## MAB.ai
# Multi-Armed Bandit AI

<p align="center">
  <img width="460" height="300" src="https://github.com/TechTouchABI/MAB-AI/blob/master/icon.png">
</p>

MAB.ai V2 has achieved 10x performance of MAB.ai V1 { https://github.com/TechTouchABI/MAB.ai } using state-of-the-art neural networks on a Intel Moviduis NCS USB stick, compared to our CPU and yours :)
Check out the MAB.ai V2 performance on vimeo:https://vimeo.com/270219767
 
 
 We have also added an AR scene to enhance the experience

Reinforcement learning is learning what to do - how to map situations to actions - so as to maximize a numerical reward signal.
The learner is not told which actions to take, as in most forms of machine learning, but instead must discover which actions
yield the most reward by trying them. In the most interesting and challenging cases, actions may affect not only
the immediate reward, but also the next situation and, through that, all subsequent rewards. 

# The multi-armed bandit problem

Maximize the reward obtained by successively playing gamble machines (the ‘arms’ of the bandits)
Invented in early 1950s by Robbins to model decision making under uncertainty when the environment is unknown
The lotteries are unknown ahead of time

# Assumptions

Each machine 𝑖 has a different (unknown) distribution law for rewards with (unknown) expectation 𝜇𝑖:
    Successive plays of the same machine yeald rewards that are independent and identically distributed
    Independence also holds for rewards across machines
     Reward = random variable 𝑋𝑖,𝑛 ; 1 ≤ 𝑖 ≤ 𝐾, 𝑛 ≥ 1
     𝑖 = index of the gambling machine
     𝑛 = number of plays
     𝜇𝑖 = expected reward of machine 𝑖.
A policy, or allocation strategy, 𝐴 is an algorithm that chooses the next
machine to play based on the sequence of past plays and obtained
rewards.

# Many applications have been studied:
Clinical trials
Adaptive routing in networks
Advertising: what ad to put on a web-page?
Economy: auctions
Computation of Nash equilibria

# Get Started
1. Download or Clone this repo
2. Unzip the Assets zip file
3. Start a new 3D project in Unity3D Game Engine
4. Drag the Assets into the Assets Folder inside Unity3D
5. Go the Build Settings make sure platform selected is UWP
6. Enable XR and Vuforia in the player settings inspector
7. Now that we have set up our environment lets open the ARscene and hit Play

# Demo Application is also included in the zip file, if you don't have Unity3D installed on your machine. Just double click the MAB.ai.exe and your all set

This project was inspired by Unity Technologies project: https://github.com/Unity-Technologies/BanditDungeon



