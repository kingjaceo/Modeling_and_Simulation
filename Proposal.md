# Proposal: Systems and Simulations

_a 1-semester course on:_
* _the principles of systems design, their basic principles (stocks, flows, and feedback loops), and analysis of many diverse systems we encounter;_
* _simulation modeling, including the simulation of simple and complex dynamic, self-reinforcing systems, and use simulation modeling to test hypotheses about the world;_
* _and actual project development, including github/gitflow, collaboration, management, and organization_

**Philosophy:**
* we want the lowest floor and highest ceiling possible
* we want the students to be as self-motivated as possible
* we want the grade to reflect actual learning and growth

  
**Text(s):**
* _Thinking in Systems_ by Donella Meadows

**Topics by Week:**

Part 1: Thinking in Systems
* Week 1: Godot (project: build a single-stock, single-flow, non-reinforcing system model -- scripts attached to labels, a loop generating sprites and a script moving them, etc)
* Week 2: Simple Systems (project: build a multi-stock, multi-flow system model -- should be iterated upon from the previous project, A: requires a graph displaying a changing stock over time)
* Week 3: Feedback Loops (project: iterate on prior project to accomodate for a a stabilizing or destabilizing feedback loop -- the level of one resource (eg, a population) depends on how much of that resource there is)
* Week 4: Personal Systems (project: students must organize themselves into small work teams and perhaps a class manager; from now on, projects will be completed by the entire class; the class presents its proposal for division of labor and makes justifications
* Week 5: Linearity and Nonlinearity (class project: the class builds one exemplar model using only linear relationships and one exemplar model using nonlinear relationships)
* Week 6: Composition of Systems (class project: re-model some component of an existing system so that it is more "system-like")
* Week 7: System Traps and Opportunities (class project: model some system trap and implement a solution)
* Week 8: Leverage (systems case study, part 1: class designs and builds a system they all exist within or around, which has problems they can identify, eg food distribution, tax collection, traffic, etc)
* Week 9: Changing Systems (systems case study, part 2: individuals hypothesizes interventions which might change the system they want changed in the way they want it changed, presentations)

Part 2: Building an Open-Source Ant Engine, aka "Game Design"
* Week 10: AsecendANT (class project: class identifies concrete goals for the development of AscendANT and organizes itself to accomplish them; present proposals for teams/tasks)
* Week 11: Github: (class project: create appropriate branches, practice a merge on last of the week, progress on tasks)
* Week 12: UI and Design Patterns (class project: progress, github)
* Week 13: Testing and Playtesting (class project: progress, github)
* Week 14: "Shipping" and the Final Merge (class project: finished)
* Week 15: Agreements and Cooperation (class project: make agreements about the future of AscendANT)

**Grading Contract:**
* A: I learned something new during this project, and I definitively improved upon my prior work or changed directions and made definitive progress.
* B: I learned something better that I already knew, and I think I improved upon my prior work or changed directions and made some progress.
* C: I learned a little bit, but I don't think I tried hard enough; I can't say my work is really an improved or I changed directions and couldn't really get started.
* D: I hardly tried at all, and I barely learned a thing. My work hasn't really improved and I don't know what to do next.
* F: I didn't try, I didn't learn anything, and I haven't done anything.
Final grade is the mode of your 14 project grades.

**Open Source Ant Engine: Why?**

In my own time, I am developing a game about ants, called AscendANT. It is a pet passion project of mine. The potential for learning in the context of the development of a "full stack" project is unrivaled. Students can and will set the bar high for themselves, pushing themselves to learn more as they take ownership of their contributions. The experience will be invaluable: working on a large project with a diverse team, managing deadlines for practical reasons (eg, my colleague needs this code!), and making decisions as a group are benefits of this structure. Unfortunately, the opportunities for this sort of experiential learning are scarce, due to the high floor of development projects. This project, however, uses Godot and its programming language gdscript (nearly identical to Python), and already has many important components "pre-assembled" as examples. Students must investigate the codebase they've inherited (which must be thoughtfully and carefully organized), idenfity lacking or potential features, and contribute in any way that interests them. As the most basic aspects of Godot would take even the most scrambled user only a day to understand, students can start learning about their interests on Day 1, be it art, music, animation, code, data, design, marketing, etc. So the project is naturally low-floor, and can be designed with an even lower floor, with careful and considerate planning and iterating. At the same time, the project is an honest-to-god full-scale project, so the only ceiling a students' skill. The class aims to demonstrate, encourage, and enable good object-oriented design, with good examples of inheritance, composition, and loose coupling. It also aims to promote several ubiquitously useful design patterns, like singletons and state machines. Importantly, this class requires not only github, but the use of a git workflow, an essential skill for any decent developer. Finally, the class encourages the self-motivated group work: groups self-organize by interest, ability, and learning goals, and set their own deadlines and development goals.
