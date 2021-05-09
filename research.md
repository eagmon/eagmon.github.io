---
layout: page
title: Research
permalink: /research/
---

I am interested in the organization of biological agency – what makes certain physical systems alive? 
As a computational systems biologist, I encode biological mechanisms in numerical models and simulate their emergent behavior.
While most computational biologists target single mechanisms in isolation and with a single modeling approach, 
I have kept focus on distinctly *multi-scale* and *multi-modal phenomena*. 
These have challenged me, and driven me to develop new computational methods that simplify and streamline model construction, 
while extending their reach. 
My research has focused on bacteria and protocells – by refining our technologies with minimal organisms, 
we will one day be able to scale the approach and simulate more complex cells with internal compartments, 
multi-cell interactions in biofilms, tissues, and organ systems.
Eventually the paradigms we establish for single cells will scale to more complete representations of multi-cellular organisms .

As a postdoc, I led the development of [Vivarium](https://github.com/vivarium-collective) – an open-source platform that synthesizes 
whole-cell modeling with agent-based modeling to simulate many interacting whole-cells in shared spatial environments. 
In building this platform, we made several breakthroughs that simplify how we build hybrid models. 
These include 1) a modular interface that allows different sub-models to plug together within a hierarchy of embedded compartments; 
2) an engine that takes these sub-models and simulates their interactions at multiple timescales; 
and 3) collaborative coding practices that improve how models are reused, recombined, and reconfigured. 
These advances allow us to iterate on model design and create increasingly complex simulations by building off of prior work.

![BigPicture](https://raw.githubusercontent.com/eagmon/eagmon.github.io/master/images/molecule-cell-environment.png)
**The big picture – modeling multiple scales of cell biology.**
Cells are compartments of active molecular processes. 
One level down – molecules have their own structure and interactions, driven by fluxes of matter and energy. 
One level up – cells are embedded in environments within which they exchange signals and engage in behaviors such as predation, 
reproduction, and cooperation. 
Over extended periods of time, populations of cells develop and evolve. 
To simulate this functional organization, our modeling technology must also be multi-scale and support the ongoing, 
collaborative refinement of a complex mechanistic representation.