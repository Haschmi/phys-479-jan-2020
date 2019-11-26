---
layout: page
title: High-Performance Computational Physics Part 1 : Intro to HPC & MPI
---

Modern Computers systems are often "parallel", i.e. they have multiple processing units that can be taught to work together on a single application. Parallel computers range from multicore cell phones to huge clusters with hundreds of thousands of processors. Programming for such machines can be a daunting task. But a few basic principles can get you surprisingly far.

In the first part of the course we give a basic introduction into how to use a multi-user cluster and how to go about writing parallel programs to run on such systems. The operating system for High-Performance systems is usually "Linux". We're going to pick up some of that here as well. 

For the programming, we'll use a system called "MPI" (Message Passing Interface). There's a few reasons why we're using MPI to illustrate parallel programming:

1.  MPI works on any kind of parallel computer, irrespective of the details of the architecture;
2.  It is very explicit, i.e. everything to do with parallel processing has to be "spelled out";
3.  Python bindings are available, so we can use that programming language as a framework. We will see that this offers some greast simplifications, so it's great to learn the basics, but there are issues with performance.
4.  Although MPI is large and can get very complex, there's a lot of simlifications we can make, and we get some good parallelism out of a handful of function calls.

Note that we won't be able to make a parallel programmer out of you in a few hours. We're just using this opportunity to give you an idea of what's what. We encourage you to learn some of the trickier details of MPI programming from books and by writing your own code.

The approach we are taking here is to "parallelize" simple sample code, and then alter the reulting parallel program until it does what we want it to do. The goal is to let let multiple processors do parts of the overall work simultaneously.

On the way, we will earn a few techniques that are common when programming for clusters and other parallel systems, and test them out with sample programs.

> ## Note {.prereq}
>
> Unfortunately, this can not all be done "hands-on". It is unavoidable to introduce 
> new concepts before we are ready to apply them, there's going to be quite a bit of talking and slides. We will put exercises in there whenever possible, and at the end of the 2nd, 4th, and 5th session, there will be assignments.
>
> Some programming background in Python is a prerequisit for this, but since this is not the "native" programming language of the lecturer, you're likely to teach him more Python than he teaches you. Occasionally, we will use use pre-made programs to demonstrate things.

> ## Getting ready {.getready}
>
> All the required data and and code segements will made available as the course progresses. You will also be issued an account on the CAC "Frontenac" compute cluster for the duration of the course.

## Topics

1.  [Week 1, Session 1, Hour 1 : Getting on and around HPC systems](111.md)
2.  [Week 1, Session 1, Hour 2 : File manipulation and software](112.md)
3.  [Week 1, Session 2, Hour 1 : SLURM scheduler and Makefiles](121.md)
4.  [Week 1, Session 2, Hour 2 : Parallel Computing, MPI](122.md)
5.  [Week 2, Session 1, Hour 1 : Basic MPI, Point-2-Point Communication](211.md)
6.  [Week 2, Session 1, Hour 2 : Parallelizing Mandelbrot](212.md)
7.  [Week 2, Session 2, Hour 1 : The Master-Slave Model](221.md)
8.  [Week 2, Session 1, Hour 2 : Memory Distribution amd Matrix Multiply](222.md)
9.  [Week 3, Session 1, Hour 1 : Domain Decomposition and Heat Equation](311.md)
10. [Week 3, Session 1, Hour 2 : TBD](312.md)

## Other Resources

*   [Reference](reference.md)
