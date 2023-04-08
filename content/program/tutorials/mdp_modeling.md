---
title: "Introduction to MDP Modeling and Interaction via RDDL and pyRDDLGym"
date: 2023-04-07T23:10:17+01:00
draft: false
---


# Introduction to MDP Modeling and Interaction via RDDL and pyRDDLGym


## Description

RDDL (pronounced riddle) is the Relational Dynamic Influence Diagram Language, the domain modeling language used in the ICAPS 2011, 2014, 2018 and the current 2023 Probabilistic Planning and Reinforcement Learning track of the International Planning Competitions. RDDL has been developed to compactly model real-world stochastic planning problems, i.e., Markov Decision Processes (MDPs), and specifically factored MDPs with highly structured transition and reward functions.  In this tutorial we will cover the basics of RDDL and present recent language extensions and capabilities through the incremental development and extension of running examples based on real-world domains.  We will also introduce pyRDDLGym, a new Python framework for the generation of Gym environments from RDDL descriptions, allowing for standard Gym interaction with RL agents, while also exposing the model for Planning agents.  We will also demonstrate additional capabilities of pyRDDLGym including DBN and XADD-based conditional probability function generation, generic and custom visualization, and baseline planners including MCTS (via PROST) and Planning by Backpropagation (via JaxPlan).


## Outline

- Introduction to Problem types and languages
	- General overview
	- MDP and Stochastic problems with introduction of a running example

- RDDL overview
	- Language overview capabilities
	- Domain and problem components
	- Modeling of the running example in RDDL (grounded)
	- Scaling up by lifting up

- Introduction to pyRDDLGym
	- Vision, structure and aux tools
	- Running the running example with the built-in visualizer and random policy
	- Custom visualization

- Solution
	- A gentle introduction to JaxPlan
	- Closing the loop: from model to policy with pyRDDLGym and JaxPlan


## Organizers

### Scott Sanner

Scott Sanner is an Associate Professor in Industrial Engineering and Cross-appointed in Computer Science at the University of Toronto. Scott's research focuses on a broad range of AI topics spanning sequential decision-making, (conversational) recommender systems, and applications of machine/deep learning. Scott is currently an Associate Editor for ACM Transactions on Recommender Systems (TORS), the Machine Learning Journal (MLJ), and the Journal of Artificial Intelligence Research (JAIR). Scott was a co-recipient of paper awards from the AI Journal (2014), Transport Research Board (2016), CPAIOR (2018) and a recipient of a Google Faculty Research Award (2020).

### Ayal Taitler

Ayal Taitler is a Postdoctoral Fellow at the University of Toronto, working with Prof. Scott Sanner. His research interests lie at the intersection of reinforcement learning, automated planning, and control theory for decision-making, and its application to robotics and intelligent transportation. Ayal received his PhD from the Technion focusing on hybrid planning problems. Before that he received his MSc working on reinforcement learning for robotic Air-Hockey, and a BSc both from the faculty of Electrical and Computer Engineering at the Technion. Ayal has over 10 years of industry experience in software engineering and AI research, and was a lecturer at the Technion faculty of Electrical and Computer Engineering.


