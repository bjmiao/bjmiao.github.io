---
title: "PRCL: Parallel Texture-aware Lubrication Simulation Program"
collection: HPC
type: "Research Assistant"
permalink: /project/6-PRCL
venue: "Center for High Performance Computing, SJTU"
date: 2019-10-01
location: "Shanghai, China"
---
A large scale lubrication simluation program to study the effect of texture on reducing the friction of engine surface.
![texture](/images/prcl/texture.png "texture")

Cooperated with School of Mechanism, 
- I developed MPI-paradigm Lubrication Simulation Program 
- The parallel version has good scalability. It reaches linear scalability on nodes, and reaches a 160x on 320 cores.

![scaling](/images/prcl/scaling.png "Scaling")

- The math kernel is *Stencil*, so I applied block-partition optimization to accelerate the kernel.
- I further guess the initial value by solving linear system to decrease the number of iterations for stencil.
