---
title: "On the role of Large Language Models in Planning"
date: 2023-04-07T23:10:17+01:00
draft: false
---

# On the role of Large Language Models in Planning

## Description

Large Language Models (LLMs, or n-gram models on steroids) that have been trained originally to generate text by repeatedly predicting the next word in the context of a window of previous words, have captured the attention of the AI (and the world) community. Part of the reason for this is their ability to produce meaningful completions for prompts relating to almost any area of human intellectual endeavors. This sheer versatility has also led to claims that these predictive text completion systems may be capable of abstract reasoning and planning. In this tutorial we take a critical look at the ability of LLMs to help in planning tasks–either in autonomous modes, or in assistive modes. We are particularly interested in characterizing these abilities–if any–in the context of problems and frameworks widely studied in the AI planning community.  The tutorial will both point out the fundamental limitations of LLMs in generating plans that will normally require resolving subgoal interactions with combinatorial search, and also show constructive uses of LLMs as complementary technologies to the sound planners that are developed in the AI Planning community. In addition to presenting our own work in this area, we provide a critical survey of many related efforts, including by researchers outside of the planning community. 

### URL for Tutorial Material

[http://rakaposhi.eas.asu.edu/llm-planning-tutorial.html](http://rakaposhi.eas.asu.edu/llm-planning-tutorial.html)

### Tutorial Length  

Half day  (July 10th preferred)


## Target Audience

This tutorial will be accessible to all the ICAPS attendees. We will provide the needed background on LLMs.

## Outline

The preliminary list of  topics to be covered in this tutorial includes:  

* Background on LLMs, and patterns of LLM use–including prompting techniques
* Differentiating the use of transformer architectures vs. Pre-trained LLMs in planning
	* Mention Word2vec to plan, decision transformers, Our ongoing work on using GPT2 with fine tuning , learning verifiers
* LLMs & Planning - Autonomous mode
	* Prompting in natural language or direct PDDL; effect of fine tuning; chain-of-thought prompting etc. 
* LLMs as heuristics/idea generators for planning
	* Connections to Case-Based and Model-Lite planning
* Search by Back-prompting LLMS
	* Automated vs. Human-driven back-prompts (and the Clever Hans problem with the latter)
* LLMs as model acquisition techniques
* LLMs as vehicles to support general types of planning
	* Incompletely specified (highly disjunctive) goals; HTN planning; “generalized planning” 
	* Use of LLMs in RL settings (to get rewards, preferences)


## Organizers

* Subbarao Kambhampati 
* Karthik Valmeekam
* Matthew Marquez
* Lin Guan 



