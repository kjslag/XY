# XY

Simulate the [XY model](https://en.wikipedia.org/wiki/Classical_XY_model) using webgl! Hold down the mouse button to apply a force that attracts vortices and repels anti-vortices!
Run using this link (requires webgl):

<https://cdn.rawgit.com/kjslag/XY/6e5a9db4/XY.html>

The spins in this simulation are soft, which means that the 2-component vector at each site is not constrained to a unit vector.
Each pixel on the computer represents a spin.
The color represents the direction of the spin vector.
Lighter colors indicate that the magnitude of the spin vector is less than 1, while darker colors indicate a magnitude greater than 1.

#### description of parameters (play with these!): ####
* a: lattice constant (distance between spins) (just rescales Ɣ and g)
* T: temperature of the bath
* Ɣ: coupling strength to thermal bath at temperature T
* g: energy cost for a spin to not be a unit vector
* F: strength of vortex attractive force when mouse clicking on the system
* dt: time step (increase to increase simulation speed at the expense of accuracy)
* steps: number of time steps before updating the image (decrease for more frames per second (fps), or increase for faster simulation if fps is already maxed out at 60fps)
