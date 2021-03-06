.. _elasticity:

Structural analysis
===================
Structural analysis is the determination of the effects of loads on physical structures and their components.
 

Equation
^^^^^^^^

.. math::
     -\, (\lambda + \mu)~\grad \div \vec{u} -\, \mu \triangle \vec{u} - \alpha_\mathrm{T} \left( 3 \lambda + 2 \mu \right) \grad T = \vec{f},\,\,\, \lambda = \frac{\nu E}{(1 + \nu) (1 - 2 \nu)},\,\, \mu = \frac{E}{2(1 + \nu)}, 

where

* $\vec{u}$ is displacement vector,      
* $T$ is thermodynamic temperature,
* $E$ is the Young modulus of elasticity,
* $\nu$ is the Poisson coefficient of the transverse contraction,
* $\alpha_\mathrm{T}$ is the coefficient of the linear thermal dilatability, 
* $\vec{f}$ denotes vector of internal volume forces  and
* $\varphi \geq 0$, $\psi > 0$  are material parameters.
 

Boundary conditions
^^^^^^^^^^^^^^^^^^^

* Fixed - fixed constraint

.. math::
    u_x = u_{0,x},\,\,\, u_y = u_{0,y}
    
* Fixed - free constraint

.. math::
    u_x = u_{0,x},\,\,\, F_y = F_{0,y}
    
* Free - fixed constraint

.. math::
    F_x = F_{0,x},\,\,\, u_y = u_{0,y}
    
* Free - free constraint

.. math::
    F_x = F_{0,x},\,\,\, F_y = F_{0,y}

 
.. include:: elasticity.gen