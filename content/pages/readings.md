---
content_type: page
description: This section provides a list of recommended textbooks, the schedule of
  readings by session, and selected chapters from the course notes.
learning_resource_types:
- Readings
ocw_type: CourseSection
title: Readings
uid: d49b78fe-f56d-f97f-9681-953c45ae4447
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

This section is divided into [recommended textbooks](#Recommended_Textbooks), [readings by session](#Readings_by_Session), and [course notes](#Course_Notes). There are no required textbooks for this course.

{{< anchor "Recommended_Textbooks" >}}{{< /anchor >}}Recommended Textbooks
--------------------------------------------------------------------------

A list of relevant textbooks is given below:

Strogatz, Steven H. _Nonlinear Dynamics and Chaos: With Applications to Physics, Biology, Chemistry, and Engineering_. Boulder, CO: Westview Press, 2001. ISBN: 9780738204536.

Slotine, Jean-Jacques E., and Weiping Li. _Applied Nonlinear Control_. Upper Saddle River, NJ: Prentice Hall, 1991. ISBN: 9780130408907.

Fantoni, Isabelle, and Rogelio Lozano. _Non-linear Control for Underactuated Mechanical Systems_. New York, NY: Springer-Verlag, 2002. ISBN: 9781852334239.

Bertsekas, Dimitri P. _Dynamic Programming and Optimal Control_. 3rd ed. Vols. I and II. Nashua, NH: Athena Scientific, 2007. ISBN: 9781886529083 (set).

[![Buy at MIT Press](/images/mp_logo.gif)](https://mitpress.mit.edu/9780262193986) Sutton, Richard S., and Andrew G. Barto. [_Reinforcement Learning: An Introduction_](https://mitpress.mit.edu/9780262193986). Cambridge, MA: MIT Press, 1998. ISBN: 9780262193986.

Bertsekas, Dimitri P., and John N. Tsitsiklis. _Neuro-Dynamic Programming_. Nashua, NH: Athena Scientific, 1996. ISBN: 9781886529106.

LaValle, Steven M. _Planning Algorithms_. New York, NY: Cambridge University Press, 2006. ISBN: 9780521862059.

{{< anchor "Readings_by_Session" >}}{{< /anchor >}}Readings by Session
----------------------------------------------------------------------

The readings below come from the course notes "Underactuated Robotics: Learning, Planning, and Control for Efficient and Agile Machines."

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
SES #
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
READINGS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}


Fully- vs. under-actuated systems

Preliminaries


{{< tdclose >}}
{{< tdopen >}}
Chapter 1 and Appendix A
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
Nonlinear dynamics of the simple pendulum
{{< tdclose >}}
{{< tdopen >}}
Chapter 2
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}


Introduction to optimal control

Double-integrator examples


{{< tdclose >}}
{{< tdopen >}}
Chapter 9
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}


Double integrator (cont.)

Quadratic regulator (Hamilton-Jacobi-Bellman (HJB) sufficiency), min-time control (Pontryagin)


{{< tdclose >}}
{{< tdopen >}}
Chapter 10
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Dynamic programming and value interation: grid world, double integrator, and pendulum examples
{{< tdclose >}}
{{< tdopen >}}


Chapter 9 (cont.)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
Acrobot and cart-pole: controllability, partial feedback linearization (PFL), and energy shaping
{{< tdclose >}}
{{< tdopen >}}
Chapter 3
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
Acrobot and cart-pole (cont.)
{{< tdclose >}}
{{< tdopen >}}
Chapter 3 (cont.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Policy search: open-loop optimal control, direct methods, and indirect methods
{{< tdclose >}}
{{< tdopen >}}
Chapter 12
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
Policy search (cont.): trajectory stabilization, iterative linear quadratic regulator (iLQR), differential dynamic programming (DDP)
{{< tdclose >}}
{{< tdopen >}}
Chapter 12 (cont.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
Simple walking models: rimless wheel, compass gait, kneed compass gait
{{< tdclose >}}
{{< tdopen >}}
Chapter 5
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
Feedback control for simple walking models
{{< tdclose >}}
{{< tdopen >}}
Chapter 5 (cont.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Simple running models: spring-loaded inverted pendulum (SLIP), Raibert hoppers
{{< tdclose >}}
{{< tdopen >}}
Chapter 6
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
Motion planning: Dijkstra's, A-star
{{< tdclose >}}
{{< tdopen >}}
Chapter 13
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
Randomized motion planning: rapidly-exploring randomized trees and probabilistic road maps
{{< tdclose >}}
{{< tdopen >}}
Chapter 13 (cont.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Feedback motion planning: planning with funnels, linear quadratic regulator (LQR) trees
{{< tdclose >}}
{{< tdopen >}}
Chapter 14
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Function approximation and system identification
{{< tdclose >}}
{{< tdopen >}}
Chapter 8 and Appendix B
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
Model systems with uncertainty: state distribution dynamics and state estimation
{{< tdclose >}}
{{< tdopen >}}
Chapter 8 (cont.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
Stochastic optimal control
{{< tdclose >}}
{{< tdopen >}}
Chapter 15
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
Aircraft
{{< tdclose >}}
{{< tdopen >}}
Chapter 7
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Swimming and flapping flight
{{< tdclose >}}
{{< tdopen >}}
Chapter 7 (cont.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
Randomized policy gradient
{{< tdclose >}}
{{< tdopen >}}
Chapter 17
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
Randomized policy gradient (cont.)
{{< tdclose >}}
{{< tdopen >}}
Chapter 17 (cont.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}
Model-free value methods: temporal difference learning and Q-learning
{{< tdclose >}}
{{< tdopen >}}
Chapter 16
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
24
{{< tdclose >}}
{{< tdopen >}}


Actor-critic methods

Final project presentations


{{< tdclose >}}
{{< tdopen >}}
Chapter 18
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
25
{{< tdclose >}}
{{< tdopen >}}
Final project presentations
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

{{< anchor "Course_Notes" >}}{{< /anchor >}}Course Notes
--------------------------------------------------------

Selected chapters from the course notes are available below. Updated revisions of the course notes are available [here](http://groups.csail.mit.edu/locomotion/pubs.html).

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
CHAPTERS
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Front
{{< tdclose >}}
{{< tdopen >}}
Title page, table of contents, and preface ({{% resource_link 0b4b18db-9bed-2aa7-1c38-259d7502ca64 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Fully actuated vs. underactuated systems ({{% resource_link e338b121-e92a-a7ae-9593-2d0a1d8a80b2 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="2" >}}
**I. Nonlinear dynamics and control**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
The simple pendulum ({{% resource_link 3cef43ed-c881-9f9f-3df4-dd2d8c18abfa "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
The acrobot and cart-pole ({{% resource_link 72bc06c4-dc73-315b-f49c-28a81dc2b996 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Manipulation
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
Walking ({{% resource_link 6e83e589-17c4-03fd-c98d-2d96260661ce "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
Running
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
Flight
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
Model systems with stochasticity
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="2" >}}
**II. Optimal control and motion planning**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
Dynamic programming ({{% resource_link c227804e-f2d3-1ebb-60f8-3acacd9b9ff5 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
Analytical optimal control with the Hamilton-Jacobi-Bellman sufficiency theorem ({{% resource_link 3c209912-afeb-0131-2a67-81c3f1b5e5c3 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
Analytical optimal control with Pontryagin's minimum principle
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Trajectory optimization ({{% resource_link 2edea610-1a80-fc20-2f5e-f7472956b580 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
Feasible motion planning
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
Global policies from local policies
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Stochastic optimal control
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Model-free value methods
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
Model-free policy search ({{% resource_link 918e59f4-891f-e977-08b6-aed1e4112a4f "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
Actor-critic methods
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen colspan="2" >}}
**IV. Applications and extensions**
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
Learning case studies and course wrap-up
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Appendix
{{< tdclose >}}
{{< tdopen >}}


A. Robotics preliminaries ({{% resource_link cb77224e-9452-d4c1-1592-2e12a2fcb113 "PDF" %}})

B. Machine learning preliminaries


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Back
{{< tdclose >}}
{{< tdopen >}}
References ({{% resource_link 96759558-56dc-cca5-400c-50d2dceb3aa6 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}