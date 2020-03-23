# Chapters 5 - 8 Review

## Chapter 5: Circular Motion + Gravitation

### 14

> On an ice rink two skaters of equal mass grab hands and spin in a mutual circle once every 2.5 s. If we assume their arms are each 0.80 m long and their individual masses are 55.0 kg, how hard are they pulling on one another?

$$
F_R = \dfrac{mv^2}{r} = \dfrac{(55\;\mathrm{kg})\left(\left(\dfrac{1\;\mathrm{rev}}{2.5\;\mathrm{s}}\right)\left(\dfrac{2\pi\cdot 0.80\;\mathrm{m}}{1\;\mathrm{rev}}\right) \right)^2}{0.80\;\mathrm{m}} = 277.6463 \approx \boxed{278\;\mathrm{N}}
$$

### 16

> <img src="../images/Problem%205-16.png" style="zoom:50%;float:right;" /> The design of a new road includes a straight stretch that is horizontal and flat but that suddenly dips down a steep hill at 18°. The transition should be rounded with what minimum radius so that cars traveling 95 km/h will not leave the road (see figure)?

$F_R = mg\cos\theta - F_N = \dfrac{mv^2}{r}$
$r = \dfrac{mv^2}{mg\cos\theta - F_N}$

As the car is about the leave the road, the normal force would be zero, so we get:

$r = \dfrac{mv^2}{mg\cos\theta} = \dfrac{v^2}{g\cos\theta} = \dfrac{2638.9^2}{9.8\cdot \cos(18^\circ)} = 2831\;\mathrm{m} = \boxed{2.8\;\mathrm{km}}$

### 21

> A pilot performs an evasive maneuver by diving vertically at 270 m/s. If he can withstand an acceleration of 8.0 g’s without blacking out, at what altitude must he begin to pull his plane out of the dive to avoid crashing into the sea?

$a_R = \dfrac{v^2}{r} \Longrightarrow r = \dfrac{270^2}{8\cdot 9.8} = 929.85\;\mathrm{m} = \boxed{0.93\;\mathrm{km}}$

### 22

> <img src="../images/Problem%205-22.png" style="zoom:90%;float:right" />If a curve with a radius of 95 m is properly banked for a car traveling 65 km/h, what must be the coefficient of static friction for a car not to skid when traveling at 95 km/h?

From the circular motion chapter[^1], we have
$$
\theta = \arctan\left(\dfrac{v^2}{rg}\right) = \arctan\left( \dfrac{\left(\left(65 \;\mathrm{\dfrac{km}{hr}}\right) \times \left(\dfrac{1000\;\mathrm{m/km}}{3600\;\mathrm{s/hr}} \right) \right) ^2}{(95\;\mathrm{m})(9.8\;\mathrm{m/s^2})}\right) = 19.3^\circ
$$

Since $F_{fr} = \mu_s F_N$, we can solve in each direction for the normal force.  
$$
\sum F_y = F_N\cos\theta - mg - F_{fr}\sin\theta = 0 \Longrightarrow F_N\cos\theta - \mu_sF_N\sin\theta = mg \\
F_N = \dfrac{mg}{\cos\theta - \mu_s\sin\theta} \\
\sum F_x = F_N\sin\theta + F_{fr}\cos\theta = \dfrac{mv^2}{r} \Longrightarrow F_N\sin\theta + \mu_sF_N\cos\theta = \dfrac{mv^2}{r} \\
F_N = \dfrac{mv^2}{r(\sin\theta + \mu_s \cos\theta)} \\
---------------------------------- \\
\dfrac{mg}{\cos\theta - \mu_s\sin\theta} = \dfrac{mv^2}{r(\sin\theta + \mu_s \cos\theta)} \\
\mu_s = \dfrac{\left(\dfrac{v^2\cos\theta}{r}\right) - g\sin\theta}{g\cos\theta + \left(\dfrac{v^2\sin\theta}{r}\right)} = 
\dfrac{\left(\dfrac{\left(95\cdot \dfrac{1.0}{3.6}\right)^2\cos(19.3^\circ)}{{0.095\cdot \dfrac{1000}{1}}}\right) - (9.8)\sin(19.3^\circ)}{(9.8)\cos(19.3^\circ) + \left(\dfrac{\left(95\cdot \dfrac{1.0}{3.6}\right)^2\sin(19.3^\circ)}{0.095\cdot \dfrac{1000}{1}}\right)} = 0.32
$$

### 27

> A particle revolves in a horizontal circle of radius 1.95 m. At a particular instant, its acceleration is 1.05 $\text{m/s}^2,$  in a direction that makes an angle of 25.0° to its direction of motion. Determine its speed (a) at this moment, and (b) 2.00 s later, assuming constant tangential acceleration.

##### Part A

$a_R = a\sin\theta = \dfrac{v^2}{r}\Longrightarrow v= \sqrt{ar\sin\theta} = \boxed{0.930\;\mathrm{m/s}}$

##### Part B

Since the acceleration comes from the tangential acceleration, we have $a_{\text{tan}} = a\cos\theta$. Therefore,
$$
v_{\text{tan}} = v_{0_{\text{tan}}} + a_{\text{tan}}t = 0.930 + 1.05\cos25^\circ \cdot 2.00 = \boxed{2.83\;\mathrm{m/s}}
$$
### 41

> Every few hundred years most of the planets line up on the same side of the Sun. Calculate the total force on the Earth due to Venus, Jupiter, and Saturn, assuming all four planets are in a line, Fig. 5–44. The masses are $m_V = 0.815 m_E,$ $m_J = 318 m_E ,$ $m_{Sat} = 95.1 m_ E$ , and the mean distances of the four planets from the Sun are 108, 150, 778, and 1430 million km. What fraction of the Sun’s force on the Earth is this?

$$
\sum F_G = G\sum_{i=\text{Venus}}^{\text{Saturn}} \left(\dfrac{m_E^2 m_{rel(i)}}{\Delta r^2}\right) = \boxed{9.6\times 10^{17}} \\
{F_{G}}_{sun} = \dfrac{Gm}{r^2} = 3.52\cdot10^{22} \\
\dfrac{{F_{G}}_{sun}}{\sum F_G} = \boxed{2.7\times10^{-5}}
$$

### 56

> (a) Show that if a satellite orbits very near the surface of a planet with period T, the density ( mass per unit volume) of the planet is (b) Estimate the density of the Earth, given that a satellite near the surface orbits with a period of 85 min. Approximate the Earth as a uniform sphere.

##### Part A

$$
\sqrt{\dfrac{GM}{R}} = v = \dfrac{2\pi R}{T} \Longrightarrow \dfrac{M}{R^3} = \dfrac{4\pi^2}{GT^2} \\
\rho = \dfrac{M}{Volume} = \dfrac{M}{\dfrac43 \pi R^3} \Longrightarrow \dfrac{3}{4\pi}\cdot \dfrac{4\pi^2}{GT^2} = \boxed{\dfrac{3\pi}{GT^2}}
$$

##### Part B

$$
\rho = \dfrac{3\pi}{GT^2} =  \dfrac{3\pi}{6.674\times10^{-11}\left(85\;\mathrm{min}\cdot\dfrac{60\;\mathrm{s}}{1\;\mathrm{min}}\right)^2} = \boxed{5430\;\mathrm{kg/m^3}}
$$



### 65

> Halley’s comet orbits the Sun roughly once every 76 years. It comes very close to the surface of the Sun on its closest approach (Fig. 5–45). Estimate the greatest distance of the comet from the Sun. Is it still “in” the solar system? What planet’s orbit is nearest when it is out there?

$$
r_E / r_C = (T_E / T_C)^{2/3}\Longrightarrow r_C = r_e\left(\dfrac{T_C}{T_E}\right)^{2/3} = 150\times 10^6 \times17.9422 = \underline{2.7\cdot 10^9 = a} \\

\textsf{Since the comet is very close to the Sun on its perihelion, we can assume it is 0.}\\\textsf{so we get that its distance is approximately }\boxed{5.4\times10^9\;\mathrm{km}} \textsf{ (around Pluto).}
$$

### 72

> While fishing, you get bored and start to swing a sinker weight around in a circle below you on a 0.25-m piece of fishing line. The weight makes a complete circle every 0.75 s. What is the angle that the fishing line makes with the vertical? 

Because $F_T = \dfrac{mg}{\cos\theta}$ and $F_T \sin\theta = \dfrac{mg\sin\theta}{\cos\theta} = \dfrac{mv^2}{r} = \dfrac{4\pi^2 mL\sin\theta}{T^2}$. Hence, we got
$$
\theta = \cos^{-1} \left(\dfrac{gT^2}{4\pi^2 L}\right) = \boxed{56^\circ} 
$$

### Footnotes

[^1]: See Chapter 5, Example 5-7

## Chapter 6: Work + Energy

### 4

> 

### 12 

> 

### 13

> 

### 29

> 

### 37

> 

### 43

> 

### 44

> 

### 56

> 

### 67

> 

### 71

> 

## Chapter 7: Linear Momentum

### 8

> 

### 12

> 

### 14

> 

### 17

> 

### 23

> 

### 42

> 

### 43

> 

### 4

> 

### 55

> 

### 66

> 

### 75

> 

### 77

> 

### 79

> 

### 81

> 

### 83

> 

## Chapter 8: Rotational Motion

### 8

> 

### 14

> 

### 22

> 

### 25

> 

### 29

> 

### 44

> 

### 46

> 

### 47

> 

### 48

> 

### 53

> 

### 58

> 

### 59

> 

### 62

> 

### 71

> 

### 72

> 

### 73

> 

