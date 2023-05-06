---
title: "IntEx"
date: 2023-02-04T21:00:17+01:00
draft: false
---

# IntEx: Integrated Acting, Planning and Execution

ICAPS'23 Workshop \
Prague, Czech Republic \
July 9-10, 2023

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

## Important Dates

* Paper submission deadline: ~~March 31, 2023~~ **April 7, 2023 AoE**
* Notification of acceptance/rejection: May 1, 2023
* Camera-ready deadline: May 22, 2023 AoE
* Workshop: July 9-10, 2023

## Submission Details

Submissions may be regular papers (up to 8 pages plus references)  or short position/challenge papers (up to 4 pages plus references). All papers should conform to the AAAI formatting guidelines and  style ([https://aaai.org/Publications/Templates/AuthorKit23.zip](https://aaai.org/Publications/Templates/AuthorKit23.zip)).

The papers must be submitted in a PDF format via EasyChair system ([https://easychair.org/my/conference?conf=intex2023](https://easychair.org/my/conference?conf=intex2023)). Submissions will be reviewed by at least two referees.

We welcome existing publications from other venues that are appropriate for discussion at this workshop.  Please note in the title area if this work is already accepted at  another venue. If the work is under review at another venue  (e.g., IJCAI-2023) please notify the organizers so we can avoid  potential reviewing conflicts.


## Workshop Committee

### Oranizing Committee

* Sunandita Patra, JPMorgan AI Research, sunandita.patra at jpmchase.com
* Wiktor Piotrowski Palo Alto Research Center, wiktorpi at parc.com
* Mark "Mak" Roberts Naval Research Laboratory, mark.roberts at nrl.navy.mil
* Tiago Vaquero Jet Propulsion Laboratory, vaquero at jpl.nasa.gov

### Program Committee

TBD

## List of Accepted Papers

TBD

## Workshop Schedule

TBD


