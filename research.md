---
layout: article
titles:
  en:       Ph.D Research
  zh:       博士研究
  zh-Hans:  博士研究
  zh-Hant:  博士研究
key: page-research
sidebar:
  nav: docs-en
---

## Videos:

<div>{%- include extensions/youtube.html id='HMS0nygMNNU' -%}</div>

<div>{%- include extensions/youtube.html id='eJsnG9DZjgM' -%}</div>

<div>{%- include extensions/youtube.html id='oo4CWKWyfvQ' -%}</div>

<div>{%- include extensions/youtube.html id='hs1mGolTXEI' -%}</div>

<div>{%- include extensions/youtube.html id='ei1_3EUhwk8' -%}</div>

<div>{%- include extensions/youtube.html id='HTPzwa7z8so' -%}</div>

<div>{%- include extensions/youtube.html id='M5gxI9sZKHg' -%}</div>

## Related Websites:

[VSPARC](http://vsparc.org/)

[LTLMoP](http://ltlmop.github.io)

## Publications:

D. Daudelin, **G. Jing**, T. Tosun, M. Yim, H. Kress-Gazit, M. Campbell  "An Integrated System for Perception-Driven Autonomy with Modular Robots." *Science October 2018 Robotics, Volume 3, Issue 23*.
> Abstract—The theoretical ability of modular robots to reconfigure
in response to complex tasks in a priori unknown
environments has frequently been cited as an advantage, but has
never been experimentally demonstrated. For the first time, we
present a system that integrates perception, high-level mission
planning, and modular robot hardware, allowing a modular
robot to autonomously reconfigure in response to an a priori
unknown environment in order to complete high-level tasks.
Three hardware experiments validate the system, and demonstrate
a modular robot autonomously exploring, reconfiguring,
and manipulating objects to complete high-level tasks in unknown
environments.
We present system architecture, software and hardware in a
general framework that enables modular robots to solve tasks
in unknown environments using autonomous, reactive reconfiguration.
The physical robot is composed of modules that support
multiple robot configurations. An onboard 3D sensor provides information
about the environment and informs exploration, reconfiguration
decision making and feedback control. A centralized
high-level mission planner uses information from the environment
and the user-specified task description to autonomously compose
low-level controllers to perform locomotion, reconfiguration, and
other behaviors. A novel, centralized self-reconfiguration method
is used to change robot configurations as needed.

**G. Jing**, T. Tosun, M. Yim, H. Kress-Gazit "Accomplishing high-level tasks with modular robots." *Autonomous Robots October 2018, Volume 42, Issue 7, pp 1337–1354*
> Abstract—The advantage of modular self-reconfigurable
robot systems is their flexibility, but this advantage can
only be realized if appropriate configurations (shapes)
and behaviors (controlling programs) can be selected
for a given task. In this paper, we present an integrated
system for addressing high-level tasks with modular
robots, and demonstrate that it is capable of accomplishing
challenging, multi-part tasks in hardware
experiments. The system consists of four tightly integrated
components: (1) A high-level mission planner,
(2) A large design library spanning a wide set of functionality,
(3) A design and simulation tool for populating
the library with new configurations and behaviors,
and (4) modular robot hardware. This paper build on
earlier work by the authors [9], extending the original
system to include environmentally adaptive parametric
behaviors, which integrate motion planners and feedback
controllers with the system.

T. Tosun, D. Daudelin, **G. Jing**, H. Kress-Gazit, M. Campbell, M. Yim "Perception-Informed Autonomous Environment Augmentation with Modular Robots." *2018 IEEE International Conference on Robotics and Automation,* Brisbane, Australia, May 21-25, 2018.
> Abstract—We present a system enabling a modular robot
to autonomously build structures in order to accomplish high-level
tasks. Building structures allows the robot to surmount
large obstacles, expanding the set of tasks it can perform. This
addresses a common weakness of modular robot systems, which
often struggle to traverse large obstacles.
This paper presents the hardware, perception, and planning
tools that comprise our system. An environment characterization
algorithm identifies features in the environment that can be
augmented to create a path between two disconnected regions
of the environment. Specially-designed building blocks enable
the robot to create structures that can augment the environment
to make obstacles traversable. A high-level planner reasons
about the task, robot locomotion capabilities, and environment
to decide if and where to augment the environment in order to
perform the desired task. We validate our system in hardware
experiments.

**G. Jing**, T. Tosun, M. Yim, H. Kress-Gazit "An End-to-End System for Accomplishing Tasks with Modular Robots: Perspectives for the AI community." *Proceedings of the Twenty-Sixth International Joint Conference on Artificial Intelligence Best Sister Conferences.* Melbourne, Australia 2017, Pages 4879-4883.
> Abstract—The advantage of modular robot systems lies in their
flexibility, but this advantage can only be realized if
there exists some reliable, effective way of generating
configurations (shapes) and behaviors (controlling programs)
appropriate for a given task. In this paper, we
present an end-to-end system for addressing tasks with
modular robots, and demonstrate that it is capable of
accomplishing challenging multi-part tasks in hardware
experiments. The system consists of four tightly integrated
components: (1) A high-level mission planner,
(2) A design library spanning a wide set of functionality,
(3) A design and simulation tool for populating
the library with new configurations and behaviors, and
(4) Modular robot hardware. This paper condenses the
material originally presented in [Jing et al., 2016] into
a shorter format suitable for a broad audience.

**G. Jing**, T. Tosun, M. Yim, H. Kress-Gazit "An End-To-End System for Accomplishing Tasks with Modular Robots." *Robotics: Science and Systems* Ann Arbor, Michigan, USA, 2016.
> Abstract—The advantage of modular robot systems lies in
their flexibility, but this advantage can only be realized if there
exists some reliable, effective way of generating configurations
(shapes) and behaviors (controlling programs) appropriate for
a given task. In this paper, we present an end-to-end system
for addressing tasks with modular robots, and demonstrate
that it is capable of accomplishing challenging multi-part tasks
in hardware experiments. The system consists of four tightly
integrated components: (1) A high-level mission planner, (2) A
large design library spanning a wide set of functionality, (3) A
design and simulation tool for populating the library with new
configurations and behaviors, and (4) modular robot hardware.
The broader goal of this project is enabling users to address
real-world tasks using modular robots. We believe this work
represents an important step toward this larger goal.

T. Tosun, **G. Jing**, H. Kress-Gazit, M. Yim (2018) "Computer-Aided Compositional Design and Verification for Modular Robots." In: Bicchi A., Burgard W. (eds) Robotics Research. *Springer Proceedings in Advanced Robotics,* vol 2. Springer, Cham
> Abstract—To take full advantage of the flexibility of a modular robot system, users
must be able to create and verify new configurations and behaviors quickly. We
present a design framework that facilitates rapid creation of new configurations and
behaviors through composition of existing ones, and tools to verify configurations
and behaviors as they are being created. New configurations are created by combining
existing sub-configurations, for example combining four legs and a body to
create a walking robot. Behaviors are associated with each configuration, so that
when sub-configurations are composed, their associated behaviors are immediately
available for composition as well. We introduce a new motion description language
(Series-Parallel Action Graphs) that facilitates the rapid creation of complex behaviors
by composition of simpler behaviors. We provide tools that automatically verify
configurations and behaviors during the design process, allowing the user to identify
problems early and iterate quickly. In addition to verification, users can evaluate
their configurations and behaviors in a physics-based simulator.

**G. Jing** and H. Kress-Gazit, "Improving the continuous execution of reactive LTL-based controllers," *2013 IEEE International Conference on Robotics and Automation, Karlsruhe,* 2013, pp. 5439-5445.
> Abstract—Recently, formal methods have been used to
transform high-level robot tasks into correct-by-construction
controllers. While correctness is guaranteed, these inherently
discrete methods often lead to behaviors that are not optimal
in the continuous sense, i.e. they induce robot paths that are
significantly suboptimal. This paper proposes an algorithm for
dynamically reordering the robot goals and connecting them
via the shortest path with respect to a given continuous metric.
The generated robot trajectories are close-to-optimal while
satisfying the task specification in a dynamic environment. This
method is implemented and simulation results are shown.

**G. Jing**, R. Ehlers and H. Kress-Gazit, "Shortcut through an evil door: Optimality of correct-by-construction controllers in adversarial environments," *2013 IEEE/RSJ International Conference on Intelligent Robots and Systems,* Tokyo, 2013, pp. 4796-4802.
> Abstract—A recent method to obtain correct robot controllers
is to automatically synthesize them from high-level
robot missions that are specified in temporal logic. In this
context, we aim for controllers that are optimal, i.e., do not
let the robot take unnecessarily costly paths to reach its
goals. Previous work on obtaining optimal synthesized robot
controllers either ignored interactions with the environment,
or assumed a cooperative environment.
In this paper, we solve the problem of obtaining optimal robot
controllers for adversarial environments. Our main observation
is that the quality of a path to a goal has two dimensions:
(1) the number of phases in which the robot waits for the
environment to perform some actions and (2) the cost of the
robot’s actions to reach the goal. Our synthesis algorithm can
take any prioritization over the possible cost combinations
into account, and computes the optimal strategy in a symbolic
manner, despite the fact that the action costs can be non-integer.
We show the scalability of the new algorithm by example of a
delivery problem.

**G. Jing**, C. Finucane, V. Raman and H. Kress-Gazit, "Correct high-level robot control from structured English," *2012 IEEE International Conference on Robotics and Automation,* Saint Paul, MN, 2012, pp. 3543-3544.
> Abstract—The Linear Temporal Logic MissiOn Planning
(LTLMoP) toolkit is a software package designed to generate a
controller that guarantees a robot satisfies a task specification
written by the user in structured English. The controller can
be implemented on either a simulated or physical robot. This
video illustrates the use of LTLMoP to generate a correct-by-construction
robot controller. Here, an Aldebaran Nao
humanoid robot carries out tasks as a worker in a simplified
grocery store scenario.


C. Finucane, **G. Jing** and H. Kress-Gazit, "Designing Reactive Robot Controllers with LTLMoP," *Automated Action Planning for Autonomous Mobile Robots 2011,* San Francisco, California, USA, 2011.
> Abstract—This paper shows an example application of the LTLMoP
mission planning toolkit, in which an Aldebaran Nao and an
iRobot Create each play a very basic game of hide-and-seek.

C. Finucane, **G. Jing** and H. Kress-Gazit, "LTLMoP: Experimenting with language, Temporal Logic and robot control," *2010 IEEE/RSJ International Conference on Intelligent Robots and Systems,* Taipei, 2010, pp. 1988-1993.
> Abstract—The Linear Temporal Logic MissiOn Planning
(LTLMoP) toolkit is a software package designed to assist in
the rapid development, implementation, and testing of high-level
robot controllers. In this toolkit, structured English and
Linear Temporal Logic are used to write high-level reactive
task specifications, which are then automatically transformed
into correct robot controllers that can be used to drive either a
simulated or a real robot. LTLMoP’s modular design makes it
ideal for research in areas such as controller synthesis, semantic
parsing, motion planning, and human-robot interaction.
