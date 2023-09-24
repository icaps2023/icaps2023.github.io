---
title: "PLATO"
date: 2023-02-01T14:30:17+01:00
draft: false
---


# PLanning And onTology wOrkshop (PLATO)

ICAPS'23 Workshop \
Prague, Czech Republic \
July 10, 2023

## Aim and Scope of the Workshop

Automated Planning and Ontology are two well-established fields of Artificial Intelligence (AI). The former investigates techniques to formally model and reason about the effects of actions, and decide the combinations of actions that allow an agent to achieve goals. The latter investigates techniques to formally define knowledge (by formally describing domain entities and their interrelations), allowing agents to process information about objects, and events, and incrementally build and verify beliefs. 

Both Automated Planning and Ontology generally rely on logic to model knowledge and organize reasoning mechanisms. They support the development of cognitive capabilities that autonomous agents need to effectively act in the real world. In this context, the PLanning And onTology wOrkshop (PLATO) aims at bringing together researchers in these two fields of AI to address new research challenges, share their experiences, and learn from each other. 

The workshop aims at investigating the synergetic contributions of technologies and methods from these two fields. There are examples in the literature that have investigated the use of Ontology to generate planning models, find effective plans, and contextualize plans and action execution to domain features. 

### Topics of Interest

The workshop is open to both application and theoretical contributions that see the integration of ontology and planning as a mechanism to enhance the efficacy of AI-based solutions. Here is a list of (some) topics: 

- Ontological analysis of concepts related to planning/scheduling (e.g., capability, capacity, action, etc)
- Domain ontologies supporting tasks related to planning/scheduling
- Reuse of foundational ontologies (e.g., DOLCE, BFO, UFO) in order to strive the interoperability among multiple ontologies, among other goals
- Semantic Web ontologies and technologies for reasoning, (FAIR) data management, interoperability, etc
- Ontologies supporting the interoperability of heterogeneous planning frameworks
- Ontologies supporting Plan and Schedule Execution
- Plan Recognition, plan management, and goal reasoning
- Partially observable and unobservable domains
- Knowledge acquisition and engineering for planning and scheduling
- Situation assessment for contextualized planning decisions
- Explainability of plans and planning models
- Trustworthy, safety, and ethics in planning
- Benchmarking and evaluation metrics of plans and plan-based controllers
- Out-of-the-box research challenges at the intersection between Automated Planning and Ontology

## Workshop Proceedings

The proceedings of **PLATO 2023** are published by [CEUR-WS](https://ceur-ws.org) and are available at [https://ceur-ws.org/Vol-3493/](https://ceur-ws.org/Vol-3493).


## Workshop Program

The workshop is scheduled on Monday **July 10 from 2:00 PM to 18:00 PM (CET) in room N6**

[2:00 PM - 2:05 PM] - Workshop Open - **NOTE:** in PLanRob's room T1

---
[2:00 PM - 3:00 PM] - <a href="#beetz">Keynote Talk by Porf. Michael Beetz</a> - **NOTE:** In PlanRob's room T1

---
[3:00 PM - 3:30 PM] - **First Session**
- "Plan and Ontology-Based Dialogue Policies for Healthcare" Milene Santos Teixeira and Mauro Dragoni
- "Planning with Ontology-Enhanced States Using Problem-Dependent Rewritings" Tobias John and Patrick Koopmann

---
[3:30 PM - 4:00 PM] Coffee Break

---
[4:00 PM - 5:00 PM] - <a href="#borgo">Keynote Talk by Dr. Stefano Borgo</a>

---
[5:00 PM - 5:45 PM] - **Second Session**
- "Ontology-guided Knowledge Graph Construction to Support Scheduling in Train Maintenance Depot" Emmanuel Papadakis, Thomas Leo McCluskey, Hassna Louadah and Gareth Tucker
- "Challenges on Deriving Planning Problems for Ontologies" Milene Santos Teixeira, Michael Welt, Birte Glimm and Raphael Chis
- "Building and Using a Planning Ontology from Past Data for Performance Efficiency" Bharath Muppasani, Vishal Pallagani, Biplav Srivastava and Raghava Mutharaju

---
[5:45 PM - 5:50 PM] - Workshop Conclusions

---

### List of Accepted Papers

- **Challenges on Deriving Planning Problems from Ontologies**, Milerie Santos Texeira, Michael Welt, Birte Glimm (University of Ulm)
- **Plan and Ontology-Based Dialogue Policies for Healthcare**, Milene Santos Texeira (University of Ulm), Mauro Dragoni (FBK)
- **Ontology-Guided Knowledge Graph Construction to Support Scheduling in a Train Maintenance Depot**, Emannuel Papadakis, Thomas Leo McCluskey, Hassna Louadah, Gareth Tucker (University of Huddersfield)
- **Planning with Ontology-Enhanced States Using Problem-Dependent Rewritings**, Tobias John (University of Oslo), Patrick Koopmann (TU Dresden)
- **Building and Using a Planning Ontology from Past Data for Performance Efficiency**, Bharath Muppasani, Vishal Pallagani, Biplav Srivastava (University of South Carolina), Raghava Mutharaju (IIIT-Delhi)


### Keynote Speakers


<div style="width: 100%; margin: 0; padding: 3%;">

<h3><a href="https://ai.uni-bremen.de/team/michael_beetz" target="_blank" name="beetz">Prof. Michael Beetz</a></h3>
<!-- <br><br> -->
<div style="display: inline-block; width: 25%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:90%; border-radius: 3%; vertical-align: middle; margin-left: 5%" src="/img/beetz.jpg" />
</div>

<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">


<div style="margin:0; padding: 0; padding-left: 2%">
<!-- <h5>Short Bio</h5> -->

<p>
Michael Beetz is a professor for Computer Science at the Faculty for Mathematics & Informatics of the University Bremen and head of the Institute for Artificial Intelligence (IAI). IAI investigates AI-based control methods for robotic agents, with a focus on human-scale everyday manipulation tasks. With his openEASE, a web-based knowledge service providing robot and human activity data, Michael Beetz aims at improving interoperability in robotics and lowering the barriers for robot programming. Due to this the IAI group provides most of its results as open-source software, primarily in the ROS software library.
</p>

</div>

</div>

<div style="width: 100%; padding: 2%; margin: 0;">
<h4>Plan-based control of robot agents -- reasoning with one's eyes and hands</h4>
<p>
Robotic agents that can accomplish manipulation tasks with the competence of humans have been
one of the grand research challenges for AI planning and robotics research for more than 50 years.
However, while the fields made huge progress over the years, this ultimate goal is still out of reach. I
believe that this is the case because the knowledge representation and reasoning methods --
including task and motion planning -- that have been proposed in AI so far are necessary but too
abstract. In this talk I propose to address this problem by endowing robots with the capability to
internally emulate and simulate their perception-action loops based on realistic images and faithful
physics simulations, which are made machine-understandable by casting them as virtual symbolic
knowledge bases. These capabilities allow robots to generate huge collections of machine-
understandable manipulation experiences, which robotic agents can generalize into commonsense
and intuitive physics knowledge applicable to open varieties of manipulation tasks. The combination
of learning, representation, reasoning, and planning will equip robots with an understanding of the
relation between their motions and the physical effects they cause at an unprecedented level of
realism, depth, and breadth, and enable them to master human-scale manipulation tasks. This
breakthrough will be achievable by combining leading-edge simulation and visual rendering
technologies with mechanisms to semantically interpret and introspect internal simulation data
structures and processes. Robots with such planning and plan execution capabilities can help us to
better deal with important societal, humanitarian, and economic challenges of our aging societies.
</p>
</div>

</div>

<hr />



<div style="width: 100%; margin: 0; padding: 3%;">

<h3><a href="https://istc.cnr.it/people/stefano-borgo" target="_blank" name="borgo">Dr. Stefano Borgo</a></h3>
<!-- <br><br> -->
<div style="display: inline-block; width: 25%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:90%; border-radius: 3%; vertical-align: middle; margin-left: 5%" src="/img/borgo.jpg" />
</div>

<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">


<div style="margin:0; padding: 0; padding-left: 2%">
<!-- <h5>Short Bio</h5> -->

<p>
I studied math at the University of Padova (Bachelor), logic at Indiana University (Master) and knowledge representation at the Free University of Bozen-Bolzano (PhD). Since 2019 I'm head of the Laboratory for Applied Ontology (LOA). My research develops in the areas of information and social systems where logic, artificial intelligence and cognitive science overlap. I like to start with an ontological approach to clarify the domain and to identify the problem. You can see this, for example, in my work on engineering function and product modeling and, for a different domain, on space representation. In general, I like to work with people with different backgrounds because I'm attracted to interdisciplinary topics.
</p>

</div>

</div>

<div style="width: 100%; padding: 2%; margin: 0;">
<h4>Layering physical and social interactions for planning via ontology</h4>
<p>
Robots with social skills and knowledge are requested to match our expectations at both the physical and the social levels. These expectations were fairly low ten years ago. After the more recent successes in the fields of AI and Robotics, expectations have raised considerably, and our communities are struggling to cope with the new demands.
One problem is that the physical and the social worlds follow different sets of rules (and those in the latter set can be quite vague and context-sensitive), and yet remain strictly intertwined. Social interactions determine and regulate what humans do and communicate, they also coordinate how things should be done and talked about. Briefly put, today it is not enough to navigate and manipulate things in the world, these actions must be done in ways that match the social circumstances. Such interactions are usually only partially constrained, and require coping with unexpected or undesired situations.
Among the many problems we face in developing plans for social robots (e.g., starting from the acquisition and integration of needed social knowledge), in this talk we discuss different layers of knowledge to target functional and social disruptions that should be anticipated and evaluated in planning for social environments. These disruptions are traced back to core notions like capabilities, roles and proximity. We will introduce a simple use case to exemplify interaction procedures and disruptions’ consequences, raising the problem of how to use this knowledge to manage disruptions in practice.
</p>
</div>

</div>

<hr />


## Submission Details

We welcome two categories of paper submission:
- **Short papers** - _6 pages_ (including references) formatted as LNCS one-column paper. These should describe concrete problems, open issues concerning planning and ontology, or methodologies/approaches pointing out the added values of the integration between planning and ontology.
- **Full papers** - _13 pages_ (including references) formatted as LNCS one-column paper. These should report work-in-progress, novel designed technologies or systems relying on the integration of panning and ontology.


Submissions should be made in PDF through **EasyChair** using the link [https://easychair.org/my/conference?conf=plato2023](https://easychair.org/my/conference?conf=plato2023).

Authors of **accepted short and full papers** will give a talk about their work during the workshop. 

Papers should be formatted according to **CEUR-WS style**. From 2022 onwards, CEUR-WS requires that authors use the new **CEUR-ART style** for writing papers. An **Overleaf template** for **LaTeX** users is available at the following link: [https://www.overleaf.com/read/gwhxnqcghhdt](https://www.overleaf.com/read/gwhxnqcghhdt). It is also possible to download an offline version with the style files from [http://ceur-ws.org/Vol-XXX/CEURART.zip](http://ceur-ws.org/Vol-XXX/CEURART.zip). More information on the [CEUR-WS website](http://ceur-ws.org/index.html).

### Workshop Proceedings

Accepted papers will be published with **CEUR-WS proceedings**, under the [**IAOA series**](https://ceur-ws.org/iaoa.html).

### Important Dates

- Submission: ~~March 31, 2023 (EXTENDED)~~
- Notification: ~~May 2, 2023~~
- Camera-ready: ~~May 27, 2023~~
- Workshop: **July 10, 2023**
- Conference: July 8-13, 2023

The reference time-zone for all deadlines is **UTC-12**. Your submissions will be on time so long as there is still some place in the world where the deadline has not yet passed.



## Workshop Committee

### Oranizing Committee

- Emilio M. Sanfilippo, CNR - Institute of Cognitive Sciences and Technologies (ISTC-CNR), Italy
- Alessandro Umbrico, CNR - Institute of Cognitive Sciences and Technologies (ISTC-CNR), Italy

### Program Committee

- Iman Awaad, Bonn-Rhein-Sieg University, Germany
- Daniel Bessler, University of Bremen, Germany
- Stefano Borgo, CNR-ISTC, Italy
- Chiara Di Francescoromano, University of Trento, Italy
- Lucia Goméz Alvaréz, TU Dresden, Germany
- Masoumeh Iran Mansouri, University of Birmingham, UK
- Marianna Nicolosi Asmundo, University of Catania, Italy
- Andrea Orlandini, CNR-ISTC, Italy
- Ron Petrick, Herriot-Watt University, UK
- Daniele Francesco Santamaria, University of Catania, Italy
- Guillaume Sarthou, LAAS CNRS, France
- Uli Sattler, University of Manchester, UK
- Biplav Srivastava, University of South Carolina, USA
- Walter Terkaj, CNR-STIIMA, Italy
- Mauro Vallati, University of Huddersfield, UK

### Contact

For inquiries please send an email to <plato2023@easychair.org>




