# Proposal: Simulation and Modeling

**Description**

This course is an introduction to simulation and modeling, studying fundamental features of dynamic systems, 

**Topics Covered**

This class will use systems design and simulation modeling to reinforce principles of object oriented design (eg, the SOLID principles). The course will be an exploration of the features of dynamic systems, like stocks, flows, and feedback loops. The course will utilize the open source video game engine Godot to teach design principles and patterns and user interaction. The course will also survey statistical topics related to randomness, variance, and simulation, in particular output analysis and variance reduction. The course will project-based, with weekly projects for the first thirds of the course and a class project in the last third. The course will seek to simulate what it is like to work on a real development project, with students using git to push, pull, and merge code for large projects.

_course topics:_
* _the principles of systems design, fundamental features of systems (stocks, flows, and feedback loops), and analysis of many systems we encounter;_
* _simulation modeling including: the simulation of simple/complex, dynamic, self-reinforcing systems, and using simulation modeling to develop/test hypotheses about the world;_
* _project management including: github/gitflow, collaboration, self- and group management, and self- and group organization;_
* _object-oriented design principles/patterns including: composition and inheritiance, loose coupling, state machines, observer pattern, and singleton pattern_*

**Philosophy:**
* we want the lowest floor and highest ceiling possible, to encourage participation and enable self-learning
* we want the students to be as self-motivated as possible, to cultivate internal motivation and self-interest
* we want the grade to reflect actual learning and self-growth

  
**Text(s):**
* _Thinking in Systems_ by Donella Meadows

**Course Overview**
* **Part 1 -- Thinking in Systems (weeks 1-9)**: students learn to use Godot game engine and Github by building increasingly complex/interconnected system models
* **Part 2 -- Building an Open Source Ant Engine (weeks 10-15)**: students use their knowledge of Godot, Github, and systems to collaborate on and contribute to a larger pre-existing project

**Educational Units (~2 weeks each)**
weekly projects (something you're proud of), biweekly reports (1-3 paragraphs on achievements, goals, and questions)?
* Introduction to Systems and Simulation, with Godot
* Linearity, Nonlinearity, and Feedback
* Object Oriented Design, Inheritance, and Composition in Practice 
* Personal Systems and a Composite System Model
* User Interaction and Design Patterns
* Class Project:
* 1) choose one complex system to implement altogether,
* 2) elect to participate in the open-source ant engine,
* 3) elect to develop the Systems and Simulation package

  
**Topics by Week:**

* Week 1: Introduction to Godot -- students learn basics of Godot and build small, simple systems
* Week 2: Introduction to Simple Systems -- students learn about systems, stocks, and flows
* Week 3: Feedback Loops -- students learn about feedback loops and their stabilizing or destabilizing affects
* Week 4: Personal Systems -- students apply their systems knowledge to put themselves in effective work-groups
* Week 5: Linearity and Nonlinearity -- students learn about the unpredictable affects of nonlinearity
* Week 6: Composition of Systems -- students learn that all systems are in fact systems of systems
* Week 7: System Traps and Opportunities -- students learn about the ways systems get "stucK" and how these can also be opportunities
* Week 8: Leverage -- students learn about finding the leverage points in systems
* Week 9: Changing Systems -- students learn about how to change systems
* Week 10: Introduction to the Open Source Ant Engine -- students begin exploring the ant engine
* Week 11: Proposals and Github
* Week 12: UI and Design Patterns
* Week 13: Testing and Playtesting
* Week 14: "Shipping" and the Final Merge
* Week 15: Agreements and Cooperation

**Projects by Week:**
* Week 1: **My First System** -- build a single-stock, single-flow, non-reinforcing system model -- scripts attached to labels, a loop generating sprites and a script moving them, etc
* Week 2: **My Second System** -- build a multi-stock, multi-flow system model -- should be iterated upon from the previous project, A: requires a graph displaying a changing stock over time
* Week 3: **Feedback Loops** -- iterate on prior project to accomodate for a a stabilizing or destabilizing feedback loop -- the level of one resource (eg, a population) depends on how much of that resource there is
* Week 4: **Personal Systems** -- students must organize themselves into small work teams; from now on, projects will be completed by the entire class; the class presents its proposal for division of labor and makes justifications
* Week 5: **Nonlinearity** the class builds one exemplar model using only linear relationships and one exemplar model using nonlinear relationships
* Week 6: **Composition** -- re-model some component of an existing system so that it is more "system-like"
* Week 7: **System Traps** -- model some system trap and implement a solution
* Week 8: **Case Study Part 1** -- class designs and builds a system they all exist within or around, which has problems they can identify, eg food distribution, tax collection, traffic, etc)
* Week 9: **Case Study Part 2** -- individuals hypothesizes interventions which might change the system they want changed in the way they want it changed, presentations

* Week 10: **Ant Engine** -- class identifies concrete goals for the development of AscendANT and organizes itself to accomplish them; present proposals for teams/tasks
* Week 11: **Ant Engine, cont**
* Week 12: **Ant Engine, cont**
* Week 13: **Ant Engine, cont**
* Week 14: **Debugging, Polishing, and Shipping** -- class wraps up their features, debugs, and merges into main development branch
* Week 15: **Agreements and Cooperation** -- class develops an agreement for the use of their work (it can/can't be shared publicly, it can/can't be profited from, it can/can't be used in future courses, etc)

**Grading Scheme:**
Each week, students will compose a weekly demonstration of their progress. This will take place as scheduled 15-minute meeting with the professor. The student will also perform a self-assessment of their progress. The grade they give themselves should reflect the grades defined in the grading contract.
  
**Grading Contract:**
* A+: I learned many new things, and I made as much progress as I reasonably could.
* A: I learned something new during this project, and I definitively improved upon my prior work or changed directions and made definitive progress.
* B: I learned something better that I already knew, and I think I improved upon my prior work or changed directions and made some progress.
* C: I learned a little bit, but I don't think I tried hard enough; I can't say my work is really an improved or I changed directions and couldn't really get started.
* D: I hardly tried at all, and I barely learned a thing. My work hasn't really improved and I don't know what to do next.
* F: I didn't try, I didn't learn anything, and I haven't done anything.
Final grade is the mode of your 14 project grades.

**Open Source Ant Engine: Why?**

As a hobby, I am developing a "game" which models an ant colony (ie, an ant engine). The ants need food, water, and defense, and there are several different kinds of ants with different abilities (eg, descendANTs dig down, defendANTs defend the colony). There are threats in the form of drought, famine, predators, and enemy ants. The goal of the engine is to facilitate the production of ant-related games and simulations. All components of the engine should be reusable and easy-to-understand.

The project is being developed in Godot, an open-source game engine with its own language, gdscript, which is very similar to Python. Godot is lightweight, easy-to-use, and enables rapid iteration, and gdscript is intuitive, forgiving, and easy to learn. Godot, by design, rewards smart object-oriented design, strongly favoring composition and the use of "signals" (ie, "events").

The nature of such a project means that contributors can be skilled at or interested in programming, art / graphic design, animation, music, UI, project management, design, data, or more and still make meaningful contributions. That is, the project aims to be naturally low-floor and high-ceiling. 

As this is a real project, participation in the second half of the class will simulate working in development professionally. The second half of the class aims to feel more like a "work project" and less like a "school project," with students organizing meetings, reporting their progress to other teams, and collaborating on many small tasks to accomplish a larger task. Students must learn Github and gitflow, and students must practice good object-oriented design, as students will undergo "code reviews".

**To Do:**
* detailed project descriptions for weeks 1-9
* starter code / starter asset library for building simulation models
  *  Stock base class, with methods for changing its stocks/flows
  *  Pre-built UI elements for displaying information about Stocks
  *  Basic graphic assets for visualizing stocks/flows
* pre-built essentials for the ant engine
  *  3 functional ant classes
  *  1 functional spider class
  *  1 functional enemy ant class
  *  food system
  *  water system
  *  reproduction system
  *  basic graphics / animations
  *  good project organization and established project organization standards

 **Course Idea Bucket**
 * Need a unit on OOD (composition, inheritiance, design patterns/principles, loose coupling, etc)
 * Need units on simulation (agent-based, discrete-event, dynamics, etc)
 * Need units on analysis
 * Variance, distributions, randomness
   
**Potential New Features to the Ant Engine**
* flying insects, which have greater sight range and pursue targets directly
* trash system (colony needs special cells dedicated to storing corpses and refuse)
* death animation
* sound effects
* debug GUI
* refactor entity classes to use reusable/modifiable-on-runtime "resource" data containers
* different layers of underground soils and rocks, based on depth
* interactable tilemap debuggers (eg, paint "diggable", paint "food", paint "water", in run time)
* UI art design
* higher-frame-number animations
* ants can build "homes" in different rooms of the colony
* ants can wear different types of clothing
* temperature system
* weather/season system
* culture system
* science system
* religion system
* "win conditions" system
* coolANT: cools colony down, develops culture
* defendANT: defends the colony from threats
* ascendANT: builds the colony up (brick pyramid > skyscraper > space needle > space elevator)
* "playable ant" system with player controller
* first person view system
* ant stats manager debugger
* unified/universal color palette
* better tilemap graphics
* consistent entity sprites
* color picker debugger (for modeulating color of entity class)


