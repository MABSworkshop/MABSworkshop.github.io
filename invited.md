---
layout: default
title: Invited Talk
permalink: /invited/
---

**Combining Constraint-Based and Imperative Programming in MABS**<br/>
by **Bruce Edmonds** and Gary Polhill

We argue for a combination of declarative/constraint and imperative programming approaches for MABS. In such an approach there would basically be two layers: a declarative layer of statements that specified the ontology, assumptions, types, internal and checks for a simulation and the specific imperative code that satisfied the statements of the declarative layer - instantiating the behaviours described more abstractly there. Such a system would be a generalisation of common elements of existing imperative simulations, such as: random choices, strong typing, unit/internal tests, ontologies, stubs, and APIs. The idea is that the two layers would be separately developed and communicated but work together. Using such a system one might start (a) with an ontology of entities that have been previously agreed within a field then (b) work with domain experts to implement declarative statements that reflect what is known about the system (c) develop the implementation starting with declarative internal checks (e.g. on incoming data) and the start of the outlines of the implementation (d) slowly becoming more and more imperative to fill in details, make the simulation run faster, maybe making some more arbitrary choices where the details of processes are not known (e) when the simulation has been completely verified, the declarative layer could be switched off to allow faster model result exploration.

Such a system would not only ensure a higher-quality of simulation (fewer bugs) but also ensure its consistency with common ontologies/APIs etc. It would facilitate the following: joining models together with fewer mistakes, comparing models (one could check that the declarative layers were consistent before doing model runs), provide enhanced and flexible error checking, make modules more reusable (one could check the constraints/specification of the module with the rest of your simulation before use), allow for rapid prototyping (and hence facilitate the expert-programmer dialogue), support the automation of modelling tools/add-ons, and allow the selective exploration of all possible behaviours of a sub-model using constraint programming techniques.

Separating out the specification and implementation stages of model development might allow for faster, more reliable, more modular and more comparable simulations and thus be a step towards enabling MABS to become a more reliable engineering/scientific endeavour.

**Short Biography**

**Bruce Edmonds** is the Director of the Centre for Policy Modelling and Senior Research Fellow at the Manchester Metropolitan University.  His first degree was in Mathematics, and his PhD on "Syntactic Measures of Complexity" in the philosophy of science.  He now works in the field of social simulation, but particularly using agent-based modelling techniques to understand complex social phenomena using the maximum amount of empirical evidence possible.  He publishes widely across the fields of social science, cognitive science, computer science and philosophy because he is interested in far too many things for his own good. More about him and the Centre at [http://cfpm.org](http://cfpm.org).
