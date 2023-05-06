---
title: "How hard can it be? The computational complexity of planning"
date: 2023-04-07T23:10:17+01:00
draft: false
---

# How hard can it be? The computational complexity of planning

## Description

Understanding the computational complexity of a problem is one of the first
steps to understand the problem deeply. Automated planning problems are not an
exception, and indeed the complexity of planning is a well studied topic in the
literature of the field.

Most people in the planning community are familiar with the seminal result by
Bylander showing that classical STRIPS planning is PSPACE-complete, but the
topic is far from being exhausted by this result. Different kinds of planning
problems, such as temporal, timeline-based, FOND, conformant or numeric
planning, have been studied to prove their complexity and, in some cases, their
undecidability. The resulting picture is unexpectedly jagged and interesting,
and sheds light over the nature of these problems and of the algorithmic
techniques that one can hope to find to solve them.

This tutorial provides an introduction and a thorough overview of the
computational complexity of many kinds of planning problems, of the techniques
used to prove such complexity results, and of some implications of these results
to the practice of automated planning. The tutorial will not be a flat list of
results and proofs, but aims to give a broad intuition of the results, their
reason and implications, while going technical when needed.

The tutorial is targeted both at novices that want to obtain a solid theoretical
background of the field, and to experienced researchers aiming at an up-to-date
picture of the topic. A basic background on complexity theory will be refreshed
as needed.


## Outline

Here is a tentative outline of the tutorial:
* Introduction and complexity theory background
* The classics: complexity of classical STRIPS and PDDL
* Inside PSPACE: compilability of propositional planning formalisms
* The very hard case: undecidability of numeric planning
* Temporal planning
  - complexity over discrete time
  - complexity and undecidable cases over dense time
  - timeline-based planning
* Interacting with the world
  - conformant planning
  - FOND planning
* Concluding remarks


## Organizers

### Nicola Gigante

Nicola got his PhD at the University of Udine, Italy with a thesis on the
theoretical foundations of timeline-based planning. Now he is a researcher at
the Free University of Bozen-Bolzano, Italy, working on temporal reasoning in
the broadest sense, including temporal planning but also temporal logics and
reactive synthesis.
