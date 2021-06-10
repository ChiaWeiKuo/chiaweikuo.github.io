---
title: "Parallelizing Advection Equation using OpenMP, MPI and CUDA"
collection: talks
type: "Coure Project"
permalink: /talks/HPC_project
venue: "Department of Mechanical Engineering, University of Wisconsin - Madisonesting"
date: 2017-12-21
---

In this project, we would try to parallelize the two-phase flow C++ solver made by our group in 2015. This solver could well reproduce the 2D pure-advection problem with a accurate fourth-order accuracy. However, there are some drawbacks associated with the use of the code. One is that the code is developed based on sequential calculation perspective. Therefore, the code would be of limited use when it comes a high mesh resolution calculation. Besides, the code is not optimized either, which would make the user hard to access. To solve these problems, we would first optimize the serial code by further dividing the code into several files, including a main program and header files that declare all variables and functions. We also try a different optimization choice in the Makefile. Moving from the serial optimization is the code parallelization. We would attempt the three popular approaches, i.e. OpenMP, MPI, and CUDA, and compare their performance against the original serial code. Based on the scaling analysis, it is found all of the three parallelization approaches could substantially speedup the code, in which CUDA has the largest improvement while MPI has the least enhancement, and OpenMP is ranked between them. The successful implementation of code parallelization could be extended to account for momentum equation solver or in a more realistic but complex 3D simulation in the future.

[Download report here](https://phxiranter.github.io/chiaweikuo.github.io/files/HPC_report.pdf)
