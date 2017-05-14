# XY

Simulate the [XY model](https://en.wikipedia.org/wiki/Classical_XY_model) using webgl!
Hold down the mouse button to apply a force that attracts vortices and repels anti-vortices!
The vortices and anti-vortices are emergent topological excitations with long range (2d) Coulomb interactions, similar to real world electrons and positrons!

Try it: <https://kjslag.github.io/XY/>

The spins in this simulation are soft, which means that the 2-component vector at each site is not constrained to a unit vector.
Each pixel on the computer represents a spin.
The color represents the direction of the spin vector.
Lighter colors indicate that the magnitude of the spin vector is less than 1, while darker colors indicate a magnitude greater than 1.

#### description of parameters (try adjusting these!): ####
* dx: spatial discretization of the field theory (effectively just rescales Ɣ and g)
* T: temperature of the bath
* Ɣ: coupling strength to thermal bath at temperature T
* g: energy cost for a spin to not be a unit vector
* F: strength of vortex attractive force when mouse clicking on the system
* dt: time step (increase to increase simulation speed at the expense of accuracy)
* steps: number of time steps before updating the image (decrease for more frames per second (fps), or increase for faster simulation speed if fps is already maxed out at 60fps)
