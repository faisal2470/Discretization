# Navier Stokes Solver

A Navier Stokes solver does a numerical computation of the conservation laws governing the flow of a fluid. The general form of the conservation laws in 3 dimensions for a calorically perfect gas are given as follows.

### Convservation of Mass
The mass conservation equation is given by,

$$ \frac{\partial \rho}{\partial t} + \frac{\partial (\rho u)}{\partial x} + \frac{\partial (\rho v)}{\partial y} + \frac{\partial (\rho w)}{\partial z} = 0 $$

### Conservation of Momentum (Navier-Stokes)
The momentum conservation equation is given by,

$$ 
\begin{align\*}
  \frac{\partial (\rho u)}{\partial t} + u\frac{\partial (\rho u)}{\partial x} + v\frac{\partial (\rho u)}{\partial y} + w\frac{\partial (\rho u)}{\partial z} &= -\frac{\partial p}{\partial x} + \mu\left(\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + \frac{\partial^2 u}{\partial z^2} \right) + f_x \\
  \frac{\partial (\rho v)}{\partial t} + u\frac{\partial (\rho v)}{\partial x} + v\frac{\partial (\rho v)}{\partial y} + w\frac{\partial (\rho v)}{\partial z} &= -\frac{\partial p}{\partial y} + \mu\left(\frac{\partial^2 v}{\partial x^2} + \frac{\partial^2 v}{\partial y^2} + \frac{\partial^2 v}{\partial z^2} \right) + f_y \\
  \frac{\partial (\rho w)}{\partial t} + u\frac{\partial (\rho w)}{\partial x} + v\frac{\partial (\rho w)}{\partial y} + w\frac{\partial (\rho w)}{\partial z} &= -\frac{\partial p}{\partial z} + \mu\left(\frac{\partial^2 w}{\partial x^2} + \frac{\partial^2 w}{\partial y^2} + \frac{\partial^2 w}{\partial z^2} \right) + f_z \\
\end{align\*}
$$

### Conservation of Energy
The energy conservation equation is given by,

$$ 
\begin{align\*}
  \frac{\partial (\rho E)}{\partial t} + u\frac{\partial (\rho E)}{\partial x} + v\frac{\partial (\rho E)}{\partial y} + w\frac{\partial (\rho E)}{\partial z} &= 
\end{align\*}
$$

