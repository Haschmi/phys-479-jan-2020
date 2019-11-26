---
layout: page
title: High-Performance Computational Physics : Intro to HPC programming
subtitle: Reference
---

##  [Week 1, Session 1, Hour 1 : Getting on and around HPC systems](111.md)
* Research Computing in Canada and at Queen's
* The Frontenac Compute Cluster
* Accessing HPC systems
* Getting around using bash
* Monitoring the system

##  [Week 1, Session 1, Hour 2 : File manipulation and software](112.md)
* File manipulation with bash
* Editing
* Software, the CVMFS stack, and lmod
* Setting upo software and running it
* Compiling and building programs
* Using python and installing packages

##  [Week 1, Session 2, Hour 1 : SLURM scheduler and Makefiles](121.md)
* The SLURM scheduler
* Single jobs and array jobs
* Serial and parallel jobs
* Workflows and makefiles

##  [Week 1, Session 2, Hour 2 : Parallel Computing, MPI](122.md)
* Parallel computing and parallel programming
* Multithreading and shared-memory machines
* MPI and distributed clusters
* MPI Runtime environments
* Simple examples : Hello World, Sum of Square Roots

##  [Week 2, Session 1, Hour 1 : Basic MPI, Point-2-Point Communication](211.md)
* Basic features of MPI : Communicators
* Simple MPI data types, MPI4Py
* Simple MPI functions
* Point-2-Point Communication
* Blocking and non-blocking communication, Wait
* Collective Operations

##  [Week 2, Session 1, Hour 2 : Parallelizing Mandelbrot](212.md)
* The Mandelbrot set
* Serial implementation
* Parallelization of MB (naive approach)
* Static scheduling, load imbalances

##  [Week 2, Session 2, Hour 1 : The Master-Slave Model](221.md)
* Dynamic scheduling
* The Master-Slave Model
* Faking a workload to test an algorithm
* Applying MS model to Mandelbrot set
* Collecting results

##  [Week 2, Session 2, Hour 2 : Memory Distribution amd Matrix Multiply](222.md)
* Matrix multiplication in serial and parallel
* Simple approach : Broadcast/reduce
* Implementation of simple matmul
* Memory distribution
* The hard way: point-2-point (Fortran, if time allows)
* Collective memory distribution : Scatter/Gather

##  [Week 3, Session 1, Hour 1 : Domain Decomposition and Heat Equation](311.md)
* Domain decomposition
* General considerations
* Finite Differences
* Simple example : 1D Heat Equation
* Bare Bones Implementation

##  [Week 2, Session 1, Hour 2 : TBD](312.md)
* Extensions to 2D and 3D in general
* Cyclic block distribution
* Stuff we have not touched
* Higher-Level packages and libraries

