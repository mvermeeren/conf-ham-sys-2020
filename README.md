# conf-ham-sys-2020
Support code for 
"Structure preserving discretization of time-reparametrized Hamiltonian systems with application to nonholonomic mechanics" 
by Luis García Naranjo and Mats Vermeeren

There are two main files corresponding to different aspects of the paper:
* "Modified Lagrangian.ipynb" (runs in SageMath 8.1) implements the symbolic calculation of modified quantities.
* "nonholonomic_particle.ipynb" (runs in Python 3) implements numerical experiments on the nonholonomic particle.

In addition:
* "modified_quantities.py" contains a list of modified quantities, produced by "Modified Lagrangian.ipynb" and used in "nonholonomic_particle.ipynb"
* "600cell.4.120.txt" contains coordinates of vertices of a 600-cell (source: http://neilsloane.com/packings/) used in "nonholonomic_particle.ipynb" to track a spherical region in phase space.
