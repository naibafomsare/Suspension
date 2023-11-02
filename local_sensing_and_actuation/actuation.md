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
   1. Apply forces on the four actuation points, and take note of how much such points move *and the angle of the beams*.
   2. Use different force magnitudes until the actuation points move the required distance $d_{max}$. Let's call this force $F_{max}$.
   3. Create a plot of force versus displacement.

The following task is, therefore, to design an *electrostatic* actuation system capable of delivering a maximum force of $F_{max}$. Consider then a parallel plate capacitor. The questions that must be answered are the following:
1. How close the parallel plates must be from each other? This must be a reasonable gap.
2. What material should be used? Take into account that the system will be cryogenic and the electrodes on the beams should not peel off due to the thermal cycle in case they are deposited films.
3. What's the required minimum thickness of the electrodes?
4. The electrodes on the beams will likely be floating, whereas the ones on the actuator units will be kept at a voltage. How does the electrostatic actuation works in this case? I think they do this type of actuation in LIGO and there should be a document in the DCC explaining the situation.
5. Do the floating electrodes need to be discharged somehow before using them?
6. In case it's not possible to get rid of residual charges on the floating electrodes, is there a way to get rid of the stray forces they generate? I think there is, but I need corrobo
