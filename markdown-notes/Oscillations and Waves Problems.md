# Oscillations and Waves Problems

## Homework 1: # 1 - 9

### 1

> Is the acceleration of a simple harmonic oscillator ever zero? If so, where?

Yes at the equilibrium position, the distance from the equilibrium goes to zero, which means that the restoring force is also zero ($F = -kx = 0$).

### 2

> Real springs have mass. Will the true period and frequency be larger or smaller than given by the equations for a mass oscillating on the end of an idealized massless spring? Explain.

The period of oscillation will be larger as the period is equal to: $2\pi \sqrt{\frac{m}{k}}$. If one increases the mass that is away from the equilibrium position as the spring will also stretch beyond the equilibrium. In addition, since the frequency is the inverse of the period, we can see that frequency will decrease in turn. 

### 3

> How could you double the maximum speed of a simple harmonic oscillator (SHO)?

$$
PE = \dfrac12 kx^2 = \dfrac12 mv^2 = KE\Longrightarrow v = \sqrt{\frac{kx^2}{m}}
$$

With this equation, one can double the maximum speed by dividing their mass by $4$, multiplying the spring constant by $4$, or by multiplying the starting distance by $2$.

### 4

> Estimate the stiffness of the spring in a child’s pogo stick if the child has a mass of 32 kg and bounces once every 2.0 seconds.

$$
f = \dfrac{1}{2\pi}\sqrt{\dfrac{k}{m}} \longrightarrow T^2 = 4\pi^2\dfrac{m}{k}\Longrightarrow k = 4\pi^2 \dfrac{32\;\mathrm{kg}}{(2.0\;\mathrm{s})^2} = \boxed{315.8\;\mathrm{N/m}}
$$

### 5

 >A fisherman’s scale stretches 3.6 cm when a 2.4-kg fish hangs from it. (a) What is the spring stiffness constant and (b) what will be the amplitude and frequency of oscillation if the fish is pulled down 2.1 cm more and released so that it oscillates up and down?

#### Part A

$$
F = F_g = (2.4)(9.8) = -k(0.036)\Longrightarrow k = 653.333 
$$

#### Part B

Amplitude = 2.1 cm because the force of gravity essentially moves the equilibrium point 3.6 cm down. 
$$
f = \dfrac{1}{2\pi}\sqrt{\dfrac{k}{m}} = \boxed{2.625\;\mathrm{Hz}}
$$

### 6

>  A small fly of mass 0.22 g is caught in a spider’s web. The web oscillates predominantly with a frequency of 4.0 Hz. (a) What is the value of the effective spring stiffness constant k for the web? (b) At what frequency would you expect the web to oscillate if an insect of mass 0.44 g were trapped?

#### Part A

$$
k = 4\pi^2\left(\dfrac{m}{T^2}\right) = 4\pi^2 \left(\dfrac{0.00022}{4^{-2}}\right)=\boxed{0.139\;\mathrm{N/m}}
$$

#### Part B

As shown by $f = \frac{1}{2\pi}\sqrt{\frac{k}{m}}$, we can see that the square root of the mass varies indirectly with the frequency, so if the mass doubles, the frequency would be $2\sqrt2\;\mathrm{Hz}$.

### 7

>  A mass m at the end of a spring oscillates with a frequency of 0.83 Hz. When an additional 780-g mass is added to m, the frequency is 0.60 Hz. What is the value of m?

$$
f = \dfrac{1}{2\pi}\sqrt{\dfrac{k}{m}}\longrightarrow mf^2 = \text{constant}\Longrightarrow m (0.83)^2 = (m + 0.78)(0.60)^2\Longrightarrow \boxed{m = 0.85\;\mathrm{kg}}
$$

### 8

>  A vertical spring with spring stiffness constant 305 N/m oscillates with an amplitude of 28.0 cm when 0.235 kg hangs from it. The mass passes through the equilibrium point (y = 0) with positive velocity at t = 0. (a) What equation describes this motion as a function of time? (b) At what times will the spring be longest and shortest?

#### Part A

$$
\omega = \sqrt{\frac{k}{m}} = 36.026\;\mathrm{rad/s}\\
y(t) = (0.280)\sin\left[\left(36.026\;\dfrac{\text{rad}}{\text{s}}\right)t\right]
$$

#### Part B

We are looking for the maximum and the minimum of the sine function from Part A. The sine function is maximized and minimized at $\frac{\pi}{2}$ and $\frac{3\pi}{2}$, respectively. So, the respective times are $4.36\times 10^{-2}\;\mathrm{s}$ and $1.31\times 10^{-1}\;\mathrm{s}$ with each occurring at 0.174-second intervals.

### 9

>  <img src="../images/Problem%2011-9.png" style="zoom:50%;float:left" /> The figure shows two examples of SHM, labeled A and B. For each, what is (a) the    amplitude, (b) frequency, and (c) period?  

| Graph A                                                      | Graph B                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Amplitude**: 2.5 meters <br />**Frequency**: 0.25 Hz <br />**Period**: 4.0 seconds | **Amplitude**: 3.5 meters <br />**Frequency**: 0.5 Hz <br />**Period**: 3.0 seconds |

### 10

$$
f = \dfrac{1}{2\pi}\sqrt{\dfrac{k}{m}}\Longrightarrow k = 4\pi^2 mf^2 = 18.476\;\mathrm{N/m} = \boxed{18\;\mathrm{N/m}}
$$

$$
f = \dfrac{1}{2\pi}\sqrt{\dfrac{k}{m}} = 1.293\;\mathrm{Hz} \approx \boxed{1.3\;\mathrm{Hz}}
$$

### 11

$$
E_{\text{pot}} = \dfrac12 E_{\text{tot}} \longrightarrow \dfrac12 kx^2 = \dfrac12 \left(\dfrac12 kA^2\right) \Longrightarrow \boxed{x = \pm \dfrac{1}{\sqrt2} A}
$$

### 12

$$
\sum F_{\text{vert}} = kx_0 - mg \Longrightarrow T = 2\pi\sqrt{\dfrac{m}{k}} = 2\pi\sqrt{\dfrac{m}{(mg/x_0)}} = 2\pi \sqrt{\dfrac{x_0}{g}} = \boxed{0.75\;\mathrm{s}}
$$

## Homework 2: Questions # 4-27

### Questions

4. > If a pendulum clock is accurate at sea level, will it gain or lose time when taken to high altitude? Why?

$$
T = 2\pi \sqrt{\dfrac{\ell}{g}}\\
\textsf{Therefore, as the altitude increases, gravity's force decreases. This means an overall increase in the period.}
$$

5. > A tire swing hanging from a branch reaches nearly to the ground. How could you estimate the height of the branch using only a stopwatch?

$$
\textsf{Since the tire almost reaches the ground, }h = \ell \textsf{ and one can find the period of the tire as }T\textsf{. With this,} \\
\begin{align*}
T &= 2\pi\sqrt{\dfrac{h}{g}}\\
\left(\dfrac{T}{2\pi}\right)^2 &= \dfrac{h}{g}\\
h &= \boxed{\dfrac{g\cdot T^2}{4\pi^2}}
\end{align*}
$$

6. > For a simple harmonic oscillator, when (if ever) are the displacement and velocity vectors in the same direction? When are the displacement and acceleration vectors in the same direction?

$$
\textsf{The displacement and velocity vectors are in the same direction when the pendulum is at its equilibrium position.}\\ \textsf{The acceleration and displacement vectors are never in the same direction. }
$$

7. > Two equal masses are attached to separate identical springs next to one another. One mass is pulled so its spring stretches 40 cm and the other is pulled so its spring stretches only 20 cm. The masses are released simultaneously. Which mass reaches the equilibrium point first?

   They both reach at the same time as the period of the simple harmonic oscillator is dependent only on the mass and the spring constant, both of which are equal in this situation.

8. > What is the approximate period of your walking step?

   It approximately 1 second.

9. > What happens to the period of a playground swing if you rise up from sitting to a standing position?

   The moment of inertia decreases, allowing for a greater mass closer to the center of rotation, shortening the period significantly.

10. > Why can you make water slosh back and forth in a pan only if you shake the pan at a certain frequency?

    You need to match the period, and therefore frequency, of the water as it sloshes back and forth to create this motion in the first place. The water then is in resonance, or in a standing wave pattern, and the amplitude of oscillation gets large. That natural frequency is determined in part by the size of the pan—smaller pans will slosh at higher frequencies, corresponding to shorter wavelengths for the standing waves. 

11. > Is the frequency of a simple periodic wave equal to the frequency of its source? Why or why not?

    The frequency of a simple periodic wave is equal to the frequency of its source. The wave is created by the source moving the wave medium that is in contact with the source. If you have one end of a taut string in your hand, and you move your hand with a frequency of 2 Hz, then the end of the string in your hand will be moving at 2 Hz, because it is in contact with your hand. Then those parts of the medium that you are moving exert forces on adjacent parts of the medium and cause them to oscillate. Since those two portions of the medium stay in contact with each other, they also must be moving with the same frequency.

12. > Explain the difference between the speed of a transverse wave and the speed of a tiny piece of the cord.

    The speed of the transverse wave is the speed at which the wave disturbance moves along the cord. For a uniform cord, that speed is constant and depends on the tension in the cord and the mass density of the cord. The speed of a tiny piece of the cord is how fast the piece of cord moves perpendicularly to the cord as the disturbance passes by

13. > What kind of waves do you think will travel along a horizontal metal rod if you strike its end (a) vertically from above and (b) horizontally parallel to its length?

    

14. > Since the density of air decreases with an increase in temperature, but the bulk modulus B is nearly independent of temperature, how would you expect the speed of sound waves in air to vary with temperature?

15. > If a rope has a free end, a pulse sent down the rope behaves differently on reflection than if the rope has that end fixed in position. What is this difference, and why does it occur?

16. > How did geophysicists determine that part of the Earth’s interior is liquid?



## Homework 3: Pg. 323 # 10 - 20



## Homework 4: Pg. 323 # 20 - 26 + 33 - 34