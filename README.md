# XY

Simulate the [XY model](https://en.wikipedia.org/wiki/Classical_XY_model) using webgl! Hold down the mouse button to apply a force that attracts vortices and repels anti-vortices!
Run using this link (requires webgl):

<https://cdn.rawgit.com/kjslag/XY/6e5a9db4/XY.html>

The spins in this simulation are soft, which means that the 2-component vector at each site is not constrained to a unit vector.
The color represents the direction of the spin vector.
Lighter colors indicate that the magnitude of the spin vector is less than 1, while darker colors indicate a magnitude greater than 1.

#### description of parameters (play with these!): ####
* a: lattice constant (just rescales Ɣ and g)
* T: temperature of the bath
* Ɣ: coupling strength to thermal bath at temperature T
* g: energy cost for a spin to not be a unit vector
* F: strength of vortex attractive force when mouse clicking on the system
* dt: time step
* steps: number of time steps before updating the image
