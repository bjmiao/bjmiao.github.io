---
title: "CUBE-a new generation of cosmological N-body simulator"
collection: HPC
type: "Research Assistant"
permalink: /project/5-CUBE
venue: "Center for High Performance Computing, SJTU"
date: 2019-09-01
location: "Shanghai, China"
---
Co-developed *CUBE*, a memory-efficient, PM-method cosmological N-body simulator in Coarray-Fortran, and rewrote it to MPI-paradigm C for further optimization potential (contributed 3000+ lines code)
![main](/images/cube/CUBEmain.png "Cube Main Structure")

*CUBE* uses a novel strategy to store the particle velocity. It can store a particle with 2 bytes instead of 8 bytes(DFP).
![main](/images/cube/velocity.png "Velocity Storage")

