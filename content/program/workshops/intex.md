---
title: "IntEx"
date: 2023-02-04T21:00:17+01:00
draft: false
---

# IntEx: Integrated Acting, Planning and Execution

ICAPS'23 Workshop \
Prague, Czech Republic \
July 9, 2023

## Aim and Scope of the Workshop

Automated planners are increasingly being integrated into online acting systems. The integration may, for example, embed a domain-independent temporal planner in a manufacturing system  (e.g., the Xerox printer application) or autonomous vehicles  (e.g., a planetary rover or anunderwater glider). The integration may resemble something more like an "acting and planning stack" where an automated planner produces an activity or  task plan that is further refined by an actor before being executed  by the execution platform of the actor, such as, a reactive  controller (e.g., robotics). Or the integration may be a  domain-specific policy that maps states to actions  (e.g., reinforcement learning). Models for planning and execution can be same or different; the planning model can define 
context-dependent actions schema for online (re-)planning  or can just specify flexibility to be handled separately at  execution time. Online learning may or may not be involved,  and may include adjusting or augmenting the model, determining  when to repair versus replan, learning to switch policies, etc.  A specific focus of these integrations involves online deliberation and managing the execution of actions, bringing to the foreground  concerns over how much computational effort planning should invest over time.

In any of these systems, a planner generates action sequences that  are eventually dispatched to an executive, yet taking action in a  dynamic world rarely proceeds according to plan. When planning  assumptions are challenged during execution, or some dynamic  events occur, it raises a number of interesting questions about how  the system should respond and which is the scope of online  deliberation versus execution. Is the "acting" side of the  system responsible for a response or the "planning" side? Or do the  two need to cooperate and how much? When should the activity planner  abandon or preempt the current goals? Should the task planner repair a plan or replan from scratch? Should the executive adjust its  current policy, switch to a new one, or learn a new policy from more relevant experience?

The seventh edition of the workshop on  Integrated Planning, Acting, and Execution (IntEx) aims: (1) to provide a forum for discussing the challenges of integrating online planning, acting, and execution, and (2) to assess the potential for holding an integrated execution competition at ICAPS.

## Topics of Interest

* online planning, acting, and execution
* position papers, benchmarks, or challenge problems for integrated execution
* improving planning performance from execution experience
* anytime or incremental planning
* discussions of plan dispatching or plan executives
* execution monitoring; comparing replanning, plan repair, re-goaling, plan merging
* managing open worlds with closed-world planners; model learning from experience
* determining an observation policy; policy switching; incremental policy adjustment
* modelling, languages and knowledge engineering for interleaved planning and execution
* architectures and application for integrated planning and execution
* execution monitoring, mixed-initiative on-line re-planning and execution

## List of Accepted Papers

1. _Timothy Darrah, Marcos Quinones-Grueiro, Gautam Biswas and Jeremy Frank._	***A Health-Aware Framework for Online Replanning of Unmanned Aerial Vehicles Missions under Faulty Conditions***
2. _Jérémy Turi, Arthur Bit-Monnot and Félix Ingrand._	***Enhancing Operational Deliberation in a Refinement Acting Engine with Continuous Planning***
3. _Jeremy Frank, Gordon Aaseng, Minh Do, Chuck Fry and Adam Sweet._	***Integrating Planning, Diagnosis and Execution for Vehicle Systems Management***
4. _Annita Vapsi, Daniel Borrajo and Manuela Veloso._	***CLAPLEX A Control Language and Architecture for Planning and Execution***
5. _Victoria Jane Armstrong and Christian Muise._	***The Generalizability of FOND Solutions in Uncertain Environments***	

## Keynote Talk: Dynamic Targeting to Improve Science Return

<div style="width: 100%; margin: 0; padding: 1%;">

<!-- <br><br> -->
<div style="display: inline-block; width: 35%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="/img/intex/keynote.png" />
</div>

<div style="display: inline-block; width: 60%; padding: 1%; vertical-align: middle;">


<div style="margin:0; padding: 0; padding-left: 2%">
<!-- <h5>Short Description</h5> -->

<p>
Dynamic Targeting (DT) is an emerging concept in which data from a lookahead instrument is
used to rapidly intelligently reconfigure and point a primary instrument to enhance science
return. For example, in the Smart Ice Hunting Radar (SMICES) a forward-looking radiometer is
used to detect deep convective ice storms which are then targeted using a radar. In other
concepts, forward-looking sensors are used to detect clouds so that a primary sensor can avoid
them. To this end, we have developed several algorithms from Operations Research and
Artificial Intelligence/heuristic search to point/reconfigure the dynamic instrument. We present
simulation studies of DT for these concepts and benchmark these algorithms to show that DT is
a powerful tool with the potential to significantly improve instrument science yield. We will also
discuss plans to fly dynamic targeting.</p>

</div>

</div>


</div>



### About the Speakers:
<div style="width: 100%; margin: 0; padding: 3%;">

<h3 style="color:orange;"><strong>Alberto Candela</strong></h3>
<!-- <br><br> -->
<div style="display: inline-block; width: 20%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="/img/intex/AlbertoCandela.png" />
</div>

<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">


<div style="margin:0; padding: 0; padding-left: 2%">
<!-- <h5>Short Bio</h5> -->

<p>
Dr. Alberto Candela is a Member of Technical Staff in the Artificial Intelligence Group, Planning
and Execution Section, at the Jet Propulsion Laboratory, California Institute of Technology. He
holds a B.S. with Highest Honors in Mechatronics Engineering from Instituto Tecnológico
Autónomo de México (ITAM). He completed an M.S. and Ph.D. in Robotics at Carnegie Mellon
University, working with Prof. David Wettergreen on new methods for science-driven
autonomous robotic exploration. His methods have been deployed on rovers and drones in
remote locations around the world, including the Martian-like Atacama Desert. After arriving at
JPL, he has worked on Dynamic Targeting, advanced machine learning for imaging
spectroscopy, and spacecraft autonomy for small body mission concepts.
</p>

</div>

</div>


</div>

<div style="width: 100%; margin: 0; padding: 3%;">

<h3 style="color:orange;"><strong>Steve Chien</strong></h3>
<!-- <br><br> -->
<div style="display: inline-block; width: 20%; border: 2px solid orange; border-radius: 3%; padding: 1%; vertical-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="/img/intex/SteveChien.png" />
</div>

<div style="display: inline-block; width: 68%; padding: 1%; vertical-align: middle;">


<div style="margin:0; padding: 0; padding-left: 2%">
<!-- <h5>Short Bio</h5> -->

<p>
Dr. Steve Chien is a JPL Fellow, Senior Research Scientist, and Head of the Artificial
Intelligence Group, at the Jet Propulsion Laboratory, California Institute of Technology. He has led the deployment of AI software to a wide range of missions including: Autonomous
Sciencecraft on EO-1, Earth Observing Sensorweb, WATCH on MER, IPEX, ESA’s Rosetta,
ECOSTRESS, and OCO-3. He is currently supporting the development of an onboard scheduler
for the Mars 2020 rover mission as well as formulating future AI-driven space mission concepts.
Dr. Chien has received numerous awards for these efforts. In 1995 he received the Lew Allen
Award for Excellence. He has been recognized four times in the NASA Software of the Year
competition (1999, 1999, 2005, and 2011). He has received four NASA Medals for his work in AI
for Space (1997, 2000, 2007, 2015). In 2011 He was awarded the inaugural AIAA Intelligent
Systems Award, for his contributions to Spacecraft Autonomy. In 2015 He was awarded a JPL
Magellan Award as well as the NASA Exceptional Achievement Medal for his contributions to
automated science scheduling for ESA&#39;s Rosetta mission. Dr. Chien has supported the Office of
the Secretary of Defense, the Defense Sciences Board studies on Autonomy, and 2018-2021 he
served as a commissioner on the National Security Commission on Artificial Intelligence.

</p>

</div>

</div>

<hr />

</div>


## Workshop Schedule

The IntEx workshop will be held on July 9, 14:00 to 17:05 local time at Prague, Czech Republic.

<div style="display: inline-block; width: 75%;  border-radius: 3%; padding: 1%; vertical-align:middle; horizontal-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="/img/intex/Session1.png" />
</div>

<div style="display: inline-block; width: 75%; border-radius: 3%; padding: 1%; vertical-align:middle; horizontal-align:middle;">
<img style="width:100%; border-radius: 3%; vertical-align: middle;" src="/img/intex/Session2.png" />
</div>


## Important Dates

* Paper submission deadline: April 7, 2023 AoE
* Notification of acceptance/rejection: May 1, 2023
* Camera-ready deadline: May 22, 2023 AoE
* Workshop: July 9, 2023

## Submission Details

Submissions may be regular papers (up to 8 pages plus references)  or short position/challenge papers (up to 4 pages plus references). All papers should conform to the AAAI formatting guidelines and  style ([https://aaai.org/Publications/Templates/AuthorKit23.zip](https://aaai.org/Publications/Templates/AuthorKit23.zip)).

The papers must be submitted in a PDF format via EasyChair system ([https://easychair.org/my/conference?conf=intex2023](https://easychair.org/my/conference?conf=intex2023)). Submissions will be reviewed by at least two referees.

We welcome existing publications from other venues that are appropriate for discussion at this workshop.  Please note in the title area if this work is already accepted at  another venue. If the work is under review at another venue  (e.g., IJCAI-2023) please notify the organizers so we can avoid  potential reviewing conflicts.


## Workshop Committee

### Oranizing Committee

* Sunandita Patra, JPMorgan AI Research, sunandita.patra at jpmchase.com
* Wiktor Piotrowski, Palo Alto Research Center, wiktorpi at parc.com
* Mark "Mak" Roberts, Naval Research Laboratory, mark.roberts at nrl.navy.mil
* Tiago Vaquero, Jet Propulsion Laboratory, vaquero at jpl.nasa.gov

### Program Committee

* Andrea Micheli, Fondazione Bruno Kessler
* Jeremy Frank, NASA
* Mark Roberts, Naval Research Laboratory
* Marco Roveri, Department of Information Engineering and Computer Science - DISI	
* Michael Floyd, Knexus Research
* Oscar Lima, German Research Center for Artificial Intelligence - DFKI
* Roni Stern, PARC/Ben-Gurion University of the Negev
* Ron Alford, The MITRE Corporation	
* Riccardo De Benedictis, CNR - National Research Council of Italy	
* Shakil Khan, University of Regina
* Sunandita Patra, JPMorgan AI Research
* Wiktor Piotrowski, Palo Alto Research Center

