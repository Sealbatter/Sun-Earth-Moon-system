# Sun-Earth-Moon-system
## Musings
Does the size of the moon as how we observe it change as the moon cycles through its lunar cycle? Anecdotally, I am inclined to say no... but does it really change? Does the apparent size of the moon from Earth where we observe the moon vary throughout its lunar cycle? How certain can we be that we obtain exactly equal results if we make precise measurements on the observed apparent size on a new moon and a full moon? 

In truth, the apparent size of a moon changes as the moon orbits around the Earth and can be explained with Newton's Law of Universal Gravitation (which is a good enough approximation for the gravity of the moon and earth). We know from our everyday lives that the further something is to us, the smaller they appear to be (this has to do with trigonometry and the angle that is formed by lines extending from the opposite edges of objects to our eyes). So it is indeed possible to account for tiny variations in the apparent size of the moon with a changing separation distance between the moon and the earth that is a direct consequence of Newton's Law of Universal Gravitation. 

But if the separation distance between the moon and the earth are changing with time, then would that not mean that the moon orbits the earth in a path that is non-circular? Yes. If you have a precognition that the moon travels in a circular orbit around the earth, then you technically may be taking for granted how bodies of masses orbit one another. In fact, circular orbits are very very rare, almost impossibly rare. In reality, basically all orbiting bodies travel in an elliptical orbit[^1] (including the moon around the earth), which can be thought of as a 'generalised idea of a circle', if it helps to make sense of this.

However, the moon's orbit around the earth IS actually very circular. How 'circular' an ellipse is can be measured by **eccentricity** of the ellipse, which is simply the ratio of (distance between centre of ellipse and the focus) to the length of the semi-major axis, with a perfect circle having an eccentricity of 0 and 1 being a perfect ellipse. It turns out that the eccentricity of the moon's orbit around earth is $0.0549$.

![Ellipse alt ><](https://github.com/Sealbatter/Sun-Earth-Moon-system/assets/85449286/4889d411-c809-4d78-895a-850a4ea1d8ab)

*Source: GeeksforGeeks*

![ellipses](https://github.com/Sealbatter/Sun-Earth-Moon-system/assets/85449286/93803c3d-8eba-454d-b2ce-986df521a680)

*Source: utexas*

[^1]: This is a consequence of Newton's Law of Universal Gravitation

## animation2.gif
Simulating the orbit of the Earth and the Moon around the Sun in our solar system with a very crude mathematical model that models orbital trajectories as simple circles. 
The Sun is located at the origin while the Earth orbits around it, with the moon orbiting the Earth simultaneously.

## 2body.gif
Incorporating an Differential Equations solver from the scipy.integrate library to solve the differential equation set up by Newton's 2nd Law and Newton's Universal Law of Gravitation to obtain a simulation of Earth orbitting Sun in circular motion

## plan.gif
An animation that is produced from simulating orbits of 3 bodies that are gravitationally attracting each other according to Newton's Law of Universal Gravitation. In this specific animation, we investigate a very specific configuration (very specific masses on the three bodies as well as initial separation distances) to observe a stable orbit between 3 bodies
