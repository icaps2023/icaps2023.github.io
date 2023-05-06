---
title: "Recent Advances in Temporal Networks for Planning and Scheduling"
date: 2023-04-07T23:10:17+01:00
draft: false
---

# Recent Advances in Temporal Networks for Planning and Scheduling

## Description

Temporal networks are structures for representing and reasoning about time (e.g., in planning and scheduling applications).  Different flavors of temporal networks differ in their expressiveness and the complexity of the algorithms for solving relevant problems.  The most basic kind of temporal network is a Simple Temporal Network (STN). STNs have a solid theoretical foundation and numerous practical algorithms for manipulating STNs have been presented in the literature over the past 30 years. 

STNs with Uncertainty (STNUs) accommodate actions with uncertain durations.  Although STNUs have been studied for over 20 years, much more efficient algorithms have been presented recently, not only for determining the important "dynamic controllability" (DC) property, but also for converting DC STNUs into a "dispatchable" form that preserves maximum flexibility while requiring minimal computation during real-time execution.  Recent advances in the theory and practice of Conditional STNs (CSTNs) and Conditional STNUs (CSTNUs) have also brought these more expressive kinds of temporal networks closer to practical application.  

This tutorial surveys the recent advances in temporal networks while also providing hands-on experience with a recently developed library of related algorithms implemented in the Python/Cython framework.

## Target Audience

This tutorial is aimed at researchers and developers interested in practical algorithms for representing and reasoning about time.  No special theoretic or algorithmic background is required.

## Outline

* Simple Temporal Networks (STNs)
	* Basic definitions of STN, STN graph, distance matrix, and STN consistency
	* Brief survey of consistency-checking algorithms, including: Floyd-Warshall,
	* Bellman-Ford, Johnson, Directed and Partial Path Consistency
	* Dispatchability: Efficient execution of STNs in real time
	* Python/Cython for STN algorithms

* Simple Temporal Networks with Uncertainty (STNUs)
	* Basic definitions of STNU, STNU graph, and dynamic controllability (DC)
	* Survey of most recent (2016-2022) DC-checking algorithms for STNUs
	* Dispatchability for STNUs
	* Python/Cython for STNU algorithms

* Extensions of STNs and STNUs
	* Conditional STNs; Conditional STNs with Uncertainty
	* Chance-Constrained Probabilistic STNs

## Organizers

### Luke Hunsberger

Luke Hunsberger earned his B.A. and M.A. in Mathematics from the University of Oregon, and his Ph.D. in Computer Science from Harvard University.  He is currently a Professor of Computer Science at Vassar College in Poughkeepsie, NY USA, where he has been teaching and doing research since 2002.  Initially, Luke's research was in collaborative multi-agent systems, presenting (with Barbara Grosz) an architecture for collaboration-capable computer agents that highlighted how constraints on intentions in the group context motivated agents to participate in group decision making mechanisms.  Luke's interest in temporal reasoning grew out of an initial attempt to build a collaborative computer agent.  Initially, he focused on Simple Temporal Networks (STNs) and STNs with Uncertainty (STNUs), contributing both theoretical foundations and practical algorithms. Later, in joint work with Roberto Posenato (University of Verona), he published several new algorithms for managing STNUs, Conditional STNs (CSTNs) and Conditional STNUs (CSTNUs).  In addition, their  collaboration with researchers from the University of Trento led to an explication of the connections between various kinds of Temporal Networks and Timed Game Automata (TGAs).

