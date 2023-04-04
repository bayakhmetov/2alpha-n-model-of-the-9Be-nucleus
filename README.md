# 2alpha+n model of the 9Be nucleus
Here I represent the test of the wave functions of relative motion of the 9Be nucleus in the frameworj of the 2alpha+neutron-model with Buck-Friedrich-Wheatley alpha-alpha-potential and alpha+n-potential with even-odd split. In this program the normalization of the wave function, charge radius and quadrupole moment of 9Be in the ground 1.5^- state are provided.

Parameters of the wave functions are given in be9.dat. Clebsch-Gordan coefficients, 6j- and 9j-symbols are given in CGC.py. The main file is written in Jupyter Notebook based on Python. The project is totally written in Python.

Designations: 

lam - relative orbital momentum of 2 alpha-particles

lmal - relative orbital momentum of the neutron and the center of mass of 2 alpha-particles
              
LL - total orbital momentum of 9Be (LL_vector = lam_vector + lmal_vector)

SS = 1/2 - spin of the neutron

JJ = 3/2 - spin of the 9Be nucleus

alpha - coefficients of gaussian expansion for the relative coordinate of 2alpha-particles

beta - coefficients of gaussian expansion for the relative coordinate of the centre of mass of 2alpha-particles and the neutron

cgamma - eigenvectors

PS radial part of the wave function of relative motion in 9Be is represented by gaussians: 

R(x, y) = cgamma_i * (x^lam_i) * (y^lmal_i) * exp(-alpha_i * x^2) * exp(-beta_i * y^2)

x - Jacobi coordinate between 2 alpha-particles, y - between the centre of mass of 2 alpha-particles and the neutron
