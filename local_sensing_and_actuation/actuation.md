# Actuation

The goal of the exercise is
1. To calculate the required actuation on the upper ends of the suspension beams in order to allow the lock acquisition of the main interferometer.
2. Design a system capable delivering such a required actuation.

The steps to follow are:

1. Fabián should ask KAGRA people the maximum distance the mirror needs to move in order to allow the lock acquisition.
   This shoud be a length expressed as a factor of the wavelength $\lambda$. Let's call this distance $\epsilon \lambda$.
2. Calculate how much the selected actuation points, at the upper ends of the beams, move when the mirror moves a distance $\epsilon \lambda$. Let's call this distance $d_{max}$. The actuation point is where the actuators will be mounted.
3. In COMSOL, take the complete 3D-CAD: include the marionette, four beams with their respective upper and lower flexures, mirror, etc.
4. In a static analysis in COMSOL do the following:
   1. Keep the marionette fixed in space.
   1. Apply forces on the four actuation points, and take note of how much such points move.
   2. Use different force magnitudes until the actuation points move the required distance $d_{max}$. Let's call this force $F_{max}$.
   3. Create a plot of force versus displacement.

The force $F_{max}$ is the maximum force that the actuation system must deliver. The following task is, therefore, deliver 
