---
permalink: /Projects/
---

Here are the reports/posters I have wrote/presented.

# 1. (Poster) Analyzing the benefits of Adaptive Mesh Refinement in Highly-Resolved VoF Simulations of Atomization
- Conference: 2019 Direct-injection Engine Research Consortium
- Venue: Department of Mechanical Engineering, University of Wisconsin - Madison
- Date: Jun, 2019
<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2019-Poster.png' width="100%">
</p>

&nbsp;
&nbsp;

---

# 2. (Poster)  Fin designs of TEFC motor: heat dissipation enhancement
- Conference: The 22th Computational Fluid Dynamics Conference in Taiwan
- Venue: The Great Roots Forestry Spa Resort, Taiwan
- Date: Aug, 2015
<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2015-Poster.png' width="75%">
</p>

&nbsp;
&nbsp;

---

# 3. (Report) Heat dissipation enhancement of an industrial totally-enclosed-fan-cooled motor through frame designs
- Research Report
- Department of Mechanical Engineering, National Taiwan University
- Date: Jul, 2016

New frame structures of an industrial totally-enclosed-fan-cooled (TEFC) motor were designed and numerically explored for the sake of heat dissipation enhancement. Several attempts were made in removing hot spots. First of all, the few large cooling ducts which are usually embedded within the frame for forming a closed internal flow are replaced by numerous small cooling ducts, uniformly distributed along the azimuthal direction. The walls between neighboring cooling ducts act like inner fins which help heat transfer from the interior of the motor to the outer surface of the frame; optimally spaced outer fins pass heat to the ambient air next. Secondly, a flat plate is added to cover the outer fins in the bottom of the motor for suppressing the flow leakage and therefore enhancing the heat dissipation there. Two new frames are so designed and simulations confirm that both successfully achieve the designing goals: a maximum frame temperature below 130 C and a maximum azimuthal temperature difference below 10 C.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2016-CFD-1.png' width="40%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2016-CFD-3.jpeg' width="40%">
</p>

[Download report here](https://phxiranter.github.io/chiaweikuo.github.io/files/2016-Report.pdf)

&nbsp;
&nbsp;

---

# 4.  (Report) Green's function solutions for 2D non-homogenous diffusion equations
- PhD-level Math Course Project
- Department of Mathematics, University of Wisconsin - Madison
- Date: Dec, 2018

An analytical expression for a 2D inhomogeneous transient diffusion problem and a linear advection-diffusion problem can be obtained using Green’s function. Based on the homogeneous Dirichlet boundary conditions, the general expression for the Green’s function, including the source terms in 2D Cartesian coordinate, is derived. The reduction of a 2D problem into a 1D problem using the multiplicative property of Green’s function is discussed. Examples involving a point source (using delta function) and a constant source throughout the entire field are solved using Green’s function. The results are verified by comparing them with the numerical solutions. The idea of using Green’s function in solving diffusion equations is applied to recognize the four different structures naturally existing in two-phase flow simulations. An illustrative example is solved to give an idea of the implementation of Green’s function solution.


*Analytical solutions to point-source problems:* 
<img src='https://phxiranter.github.io/chiaweikuo.github.io/Projects/images/point_source.png'>
<img src='https://phxiranter.github.io/chiaweikuo.github.io/Projects/images/image_point_source.png'>

[Download report here](https://phxiranter.github.io/chiaweikuo.github.io/files/math703_report.pdf)

&nbsp;  
&nbsp;

---

# 5.  (Report) Parallelizing advection equation using OpenMP, MPI and CUDA
- PhD-level High-Performance Computing Course Project
- Department of Mechanical Engineering, University of Wisconsin - Madison
- Date: Dec, 2017

In this project, the two-phase flow solver developed by our group for solving 2D pure-advection problems is parallelized for performing parallel computation. This solver was developed in the C++ platform and had been well verified with accurate fourth-order accuracy. However, there were two limitations of this solver. One was that the code was developed based on serial computing using one computing node; hence, this solver's speed performance significantly deteriorated when applied to high mesh resolution cases. Besides, the code is not optimized either, which would make the user hard to access. To solve these problems, we would first optimize the serial code by further dividing the code into several files, including a main program and header files that declare all variables and functions. We also try a different optimization choice in the Makefile. Moving from serial optimization is code parallelization. We would attempt the three popular approaches, i.e., OpenMP, MPI, and CUDA, and compare their performance against the original serial code. Based on the scaling analysis, it is found all of the three parallelization approaches could substantially speedup the code, in which CUDA has the largest improvement. In contrast, MPI has a minor enhancement, and OpenMP is ranked between them. The successful implementation of code parallelization could be extended to more realistic 3D cases in the future.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/Projects/images/CUDA.png' width="49%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/Projects/images/MPI.png' width="49%">
</p>
[Download report here](https://phxiranter.github.io/chiaweikuo.github.io/files/HPC_report.pdf)




