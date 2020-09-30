---
layout: archive
classes: wide
author_profile: # true
title: Research
permalink: /Research/
---
### Asynchronous Simulations
Developed, first-of-its-kind, asynchronous 3D compressible flow solver, capable of scalable simulations of turbulent flows on massively parallelized supercomputers. Allowing for asynchrony, helps mitigate the communication bottleneck, which is expected to be an insurmountable challenge in next-generation exascale machines. The simulations are done on Stampede2 and Frontera  (TACC) supercomputers to study the effect of asynchrony on physics of turbulence and computational performance up to 262144 processors. The performance of the code is analysed and optimized using profiling tools such as TAU, gprof, VTUNE Amplifier. This solver will provide a path towards simulations on turbulent flows on next generation Exascale machines at conditions unachievable using current state-of-the-art solvers.


### Optimal finite difference
Developed a unified framework for derivation of optimized numerical schemes that expose explicit trade-offs between order of accuracy, spectral accuracy and stability. Optimal schemes are spectrally flat and particularly useful for problems dominated by multi-scale physics like turbulence.

K. Kumari, R. Bhattacharya, D. Donzis, [A unified framework for deriving optimal finite differences](https://doi.org/10.1016/j.jcp.2019.108957){:target="_blank"}, Journal of Computational Physics, 2019


### Topology of fine scale motion
Investigated the invariants of Velocity Gradient Tensors (VGT) obtained from the Direct Numerical Simulations (DNS) of turbulent pipe flows to get a mechanistic view of the local flow topology. Analyzed and compared the dominant local flow topology for a subsonic and supersonic turbulent pipe with small dilatation. Studied the effect of local dilatation on flow topology for turbulent pipe, nozzle and diffuser flows

K. Kumari, S. Mahapatra, S. Ghosh, J. Mathew, [Invariants of velocity gradient tensor in supersonic turbulent pipe, nozzle, and diffuser flows, Physics of Fluids](https://doi.org/10.1063/1.5004468){:target="_blank"}, 2018

Thesis (Master of Technology, Indian Institute of Technology Kharagpur): Topology of Fine-Scale Motions in Turbulent Pipe, Nozzle and Diffuser Flows


### Large Eddy Simulation (LES) of turbulent flows
Carried out LES of supersonic pipe flows to study the effect of domain length on turbulent structures- obtained the two-point correlation coefficient and determined the domain length required to capture the important physical properties of the turbulent flows and large scale structure

Thesis (Bachelors of Technology, Indian Institute of Technology Kharagpur)-  Large-Eddy Simulations of Supersonic Pipe Flows: Effect of Streamwise Domain Size

### Numerical solvers
1. 3D compressible Navier-Stokes (NS) solver (Synchronous- explicit finite difference; Asynchronous- asynchrony-tolerant finite difference)- Fortran
1. 2D Navier-Stokes solver (Synchronous with explicit finite difference schemes and hybrid MPI/OpenMP)- Fortran
1. 1D solvers (explicit and implicit finite difference schemes)- Fortran
1. Modules for 3D  NS solver for detection of grid singularities in block meshes- C
