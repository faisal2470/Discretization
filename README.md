# Navier Stokes Solver

A Navier Stokes solver does a numerical computation of the conservation laws governing the flow of a fluid. The general form of the conservation laws in 3 dimensions for a calorically perfect gas are given as follows.

### Convservation of Mass
The mass conservation equation is given by,

$$ \frac{\partial \rho}{\partial t} $$

### Conservation of Momentum (Navier-Stokes)
The momentum conservation equation is given by,

$$ \frac{\partial \rho u}{\partial t} + \nabla \cdot (\rho \vec u \vec u) = -\nabla p + \nabla \cdot (\mu \nabla \vec u) + \vec f $$
