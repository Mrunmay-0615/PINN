# PINN

This project explores physics-informed neural networks as a tool to solve
partial differential equations. Owing to the great approximating abilities of neural
networks and the growing computational power, PINNs (Physics Informed Neural
Networks) can prove to be very promising tools in scientific computing. In the first
part of this paper, the response of an undamped oscillator is found out assuming
appropriate initial conditions. The response obtained is plotted for visual analysis
and validation of the obtained result. In the second part, things are a little more
complicated where we solve the one-dimensional Burger’s equation to find the
velocity field. The governing equation involves partial derivatives. The obtained
solution is then plotted for visual analysis. However, there are still many problems
with physics-informed neural networks, such as how to better introduce physical
information into neural networks and the possible non-convergence problem in loss
function optimization, etc.

The repository contains 3 jupyter notebooks, each dedicated to solving 3 PDEs and in future, 
more additions will be done. Currently the 3 equations handled are

* The Burger's Equation
* The Equation of motion for an Undamped Harmonic Oscillator
* The Equation of motion for an underdamped Harmonic Oscillator
