# Sun-Earth-Moon-system
Does the size of the moon as how we observe it change as the moon cycles through its lunar cycle? Anecdotally, I am inclined to say no... but does it really change? Does the apparent size of the moon from Earth where we observe the moon vary throughout its lunar cycle? How certain can we be that we obtain exactly equal results if we make precise measurements on the observed apparent size on a new moon and a full moon? 

In truth, the apparent size of a moon changes as the moon orbits around the Earth and can be explained with Newton's Law of Universal Gravitation (which is a good enough approximation for the gravity of the moon and earth). We know from our everyday lives that the further something is to us, the smaller they appear to be (this has to do with trigonometry and the angle that is formed by lines extending from the opposite edges of objects to our eyes). So it is indeed possible to account for tiny variations in the apparent size of the moon with a changing distance between the moon and the earth that is a direct consequence of Newton's Law of Universal Gravitation.

## animation2.gif
Simulating the orbit of the Earth and the Moon around the Sun in our solar system with a very crude mathematical model that models orbital trajectories as simple circles. 
The Sun is located at the origin while the Earth orbits around it, with the moon orbiting the Earth simultaneously.

## 2body.gif
Incorporating an Differential Equations solver from the scipy.integrate library to solve the differential equation set up by Newton's 2nd Law and Newton's Universal Law of Gravitation to obtain a simulation of Earth orbitting Sun in circular motion

## plan.gif
An animation that is produced from simulating orbits of 3 bodies that are gravitationally attracting each other according to Newton's Law of Universal Gravitation. In this specific animation, we investigate a very specific configuration (very specific masses on the three bodies as well as initial separation distances) to observe a stable orbit between 3 bodies
