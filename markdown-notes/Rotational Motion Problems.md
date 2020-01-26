# Rotational Motion Problems

## Homework 1: Pg. 222 # 3, 6, 17, 20, 21, 23, 25, 27, 28, 29, 30, 32

### 3

>A laser beam is directed at the Moon, 380,000 km from Earth. The beam diverges at an angle $\theta $ of $1.4\times 10^{-5}\;\mathrm{rad.}$ What diameter spot will it make on the Moon?

$\theta = \dfrac{\ell}{r} = 380000 / r = 1.4\times 10^{-5} \Longrightarrow \boxed{2.71 \times 10^{10}}$

### 6

> A child rolls a ball on a level floor 3.5 m to another child. If the ball makes 12.0 revolutions, what is its diameter?

$C = \pi d$
$12C = 3.5 \Longrightarrow C = 3.5/12 \Longrightarrow d = \dfrac{3.5}{12\cdot\pi} = \boxed{0.093}$

### 17

>An automobile engine slows down from 3500 rpm to 1200 rpm in 2.5 s. Calculate (a) its angular acceleration, assumed constant, and (b) the total number of revolutions the engine makes in this time.

#### Part A

$\omega = \omega_0 + \alpha t$
$1200 = 3500 + \alpha (2.5) \Longrightarrow \dfrac{-2300\;\mathrm{rev/min}}{2.5 s} (\dfrac{2\pi rad}{1 rev})(\dfrac{1 min}{60 sec}) = \boxed{-96.34\;\mathrm{rad/s^2}}$

#### Part B

$\theta = \overline{\omega}t = (\dfrac{3500+1200}{2})(2.5)(\dfrac{1 min}{60 sec}) = \boxed{97.9\;\mathrm{rev}}$

### 20

>A cooling fan is turned off when it is running at 850 rev/min. It turns 1250 revolutions before it comes to a stop. (a) What was the fan’s angular acceleration, assumed constant? (b) How long did it take the fan to come to a complete stop?

#### Part A

$\alpha = \dfrac{\omega^2 - \omega_0^2}{2\theta} = \dfrac{-850^2\;\mathrm{rev^2/min^2}}{2(1250\;\mathrm{rev})} \left(\dfrac{1\;\mathrm{min}}{60\;\mathrm{s}}\right)^2 \left(\dfrac{2\pi\;\mathrm{rad}}{1\;\mathrm{rev}}\right) = \boxed{-0.50\;\mathrm{\dfrac{rad}{s^2}}}$

#### Part B

$\omega = \omega_0 + \alpha t \Longrightarrow t = \dfrac{\Delta \omega}{\alpha} = \dfrac{-850\;\mathrm{rev\cdot s^2}}{-0.5\;\mathrm{rad\cdot min}} \left(\dfrac{1\;\mathrm{min}}{60\;\mathrm{s}}\right)\left(\dfrac{2\pi \;\mathrm{rad}}{1\;\mathrm{rev}}\right) = \boxed{178h\;\mathrm{s}}$

### 21

>A wheel 31 cm in diameter accelerates uniformly from 240 rpm to 360 rpm in 6.8 s. How far will a point on the edge of the wheel have traveled in this time?

$\alpha = \dfrac{\Delta \omega}{\Delta t} = \dfrac{120\;\mathrm{rev/min}}{6.8\;\mathrm{s}} \left(\dfrac{1\;\mathrm{min}}{60\;\mathrm{sec}}\right) = 0.294\;\mathrm{rev/s^2}$

$\theta = \omega_0t + \dfrac12 \alpha t^2 = \left(240\;\mathrm{\dfrac{rev}{min}}\right)(6.8\;\mathrm{sec})\left(\dfrac{1\;\mathrm{min}}{60\;\mathrm{sec}}\right) +\dfrac12 \left(0.294\;\mathrm{\dfrac{rev}{s^2}}\right) \left(6.8\;\mathrm{s}\right)^2 = 34\;\mathrm{rev} $
$34\cdot C = 34\pi(31) = \boxed{33.1\;\mathrm{m}}$

### 23

>A small rubber wheel is used to drive a large pottery wheel. The two wheels are mounted so that their circular edges touch. The small wheel has a radius of 2.0 cm and accelerates at the rate of 7.2 rad/s$^2$ and it is in contact with the pottery wheel (radius 27.0 cm) without slipping. Calculate (a) the angular acceleration of the pottery wheel, and (b) the time it takes the pottery wheel to reach its required speed of 65 rpm.

#### Part A

$a_{\text{tan}}$ is equivalent for each of the wheels because there is no slipping. Therefore, $\alpha_{r} r_r = \alpha_p r_p\Longrightarrow \alpha_p = \dfrac{\alpha_r r_r}{r_p} = \boxed{0.533\;\mathrm{rad/s^2}}$

#### Part B

$\omega = \omega_0 + \alpha t \Longrightarrow \dfrac{65\;\mathrm{rev/min}}{0.533\;\mathrm{rad/s^2}}\left(\dfrac{1\;\mathrm{min}}{60\;\mathrm{sec}}\right)\left(\dfrac{2\pi\;\mathrm{rad}}{1\;\mathrm{rev}}\right) = \boxed{t = 12.76\;\mathrm{s}}$

### 25

> <img src="../images/Problem%208-25.png" style="zoom:50%;float:right;overflow:auto;" /> Calculate the net torque about the axle of the wheel shown in the figure. Assume that a friction torque of $0.60\;\mathrm{m\cdot N}$ opposes the motion. 

$\tau_{\text{net}} = \tau_1 + \tau_2 + \tau_3 + \tau_f$
$\tau_{\text{net}} = (35\cdot 0.12) - (28\cdot 0.24) + (18\cdot 0.24) - (0.60) =\boxed{1.2\;\mathrm{m\cdot N}}$

### 27

> <img src="../images/Problem%208-27.png" style="zoom:60%;float:right" /> Two blocks, each of mass $m$, are attached to the ends of a massless rod which pivots as shown. Initially the rod is held in the horizontal position and then released. Calculate the magnitude and direction of the net torque on this system when first released. 

$\tau_{\text{net}} = mg(\ell_2 - \ell_1)\textsf{ towards the mass that is further away from the fulcrum.}$

### 28

> <img src="../images/Problem%208-28.png" style="zoom:75%;float:right;overflow:auto;" /> The bolts on the cylinder head of the engine require tightening to a torque of $95 \;\mathrm{m\cdot N}$. If a wrench is 28 cm long, what force perpendicular to the wrench must the mechanic exert at its end? If the six-sided bolt head is 15 mm across, estimate the force applied by each of the six points of the wrench against the bolt.

#### Part A

$F = \dfrac{95\;\mathrm{m\cdot N}}{0.28\;\mathrm{m}} = \boxed{339.3\;\mathrm{N}}$

#### Part B

The radius of the bolt to each of its corner is $\dfrac{2\sqrt3}{3}\cdot \dfrac{0.015}{2}.$
Thus, when finding the force on all six, we take the torque of the wrench and divide by six times the radius:
$F = \dfrac{95}{6r} = \dfrac{95}{0.03\sqrt3} = \boxed{1830\;\mathrm{N}}$

### 29

> <img src="../images/Problem%208-29.png" style="zoom:50%;float:right;rotate:90;" /> Determine the net torque on the 2.0-m-long uniform beam shown. All forces are shown. 
>
> Calculate about 
> (a) point C, the CM, and 
> (b) point P at one end.

#### Part A

$\tau = -(1.0\;\mathrm{m})(56\;\mathrm{N})\sin 32 + (1.0\;\mathrm{m})(52\;\mathrm{N})\sin 58 = \boxed{14.42\;\mathrm{m\cdot N}}$

#### Part B

The force at C has a lever arm of 1.0 m, and the force at the top has a lever arm of 2.0 m. 

$\tau = − (2.0\;\mathrm{m})(56\;\mathrm{N}) \sin 32 +(1.0\;\mathrm{m})(65\;\mathrm{N}) \sin 45 = \boxed{-13.39\;\mathrm{m\cdot N}}$

### 30

> Determine the moment of inertia of a 10.8-kg sphere of radius 0.648 m when the axis of rotation is through its center.

$I = \dfrac25 MR^2 = \boxed{1.81\;\mathrm{kg\cdot m^2}}$

### 32

> A merry-go-round accelerates from rest to 0.68 rad/s in 34 s. Assuming the merry-go-round is a uniform disk of radius 7.0 m and mass 31,000 kg, calculate the net torque required to accelerate it.

$\alpha = \omega / t$
$\tau = I\alpha = \left(\dfrac12MR_0^2\right)\left(\dfrac{\omega}{t}\right) = \dfrac{31000\cdot (7.0^2)\cdot 0.68}{2(34)} \approx \boxed{15,200\;\mathrm{m\cdot N}}$















## Homework 2: Pg. 223 # 34, 37, 38, 39, 41, 43, 46 ,48, 50, 52, 54, 56

### 34

>  A grinding wheel is a uniform cylinder with a radius of 8.50 cm and a mass of 0.380 kg. Calculate (a) its moment of inertia about its center, and (b) the applied torque needed to accelerate it from rest to 1750 rpm in 5.00 s. Take into account a frictional torque that has been measured to slow down the wheel from 1500 rpm to rest in 55.0 s.

#### Part A

$I = \dfrac12 MR^2 = \dfrac12 (0.380)(0.0850)^2 = \boxed{0.00137\;\mathrm{kg\cdot m^2}}$

#### Part B

$\tau = I\alpha + I\alpha_f = \dfrac{(0.001373\;\mathrm{kg\cdot m^2})(1750\;\mathrm{rev})(1\;\mathrm{min})(2\pi\;\mathrm{rad})}{(1\;\mathrm{rev})(1\;\mathrm{min})(60\;\mathrm{s})(5.00\;\mathrm{s})} + \dfrac{(0.001373\;\mathrm{kg\cdot m^2})(1500\;\mathrm{rev})(1\;\mathrm{min})(2\pi\;\mathrm{rad})}{(1\;\mathrm{rev})(1\;\mathrm{min})(60\;\mathrm{s})(55.00\;\mathrm{s})} = \boxed{0.0542\;\mathrm{m\cdot N}}$

### 37

> A softball player swings a bat, accelerating it from rest to 2.6 rev/s in a time of 0.20 s. Approximate the bat as a 0.90-kg uniform rod of length 0.95 m, and compute the torque the player applies to one end of it.

$\tau = I\alpha = \dfrac13M\ell^2 \dfrac{\Delta \omega}{\Delta t} = \dfrac13 (0.90\;\mathrm{kg})(0.95\;\mathrm{m})^2\left(\dfrac{(2.6\;\mathrm{rev/s})(2\pi\;\mathrm{rad})}{(1\;\mathrm{rev})(0.20\;\mathrm{s})}\right) = \boxed{22.1\;\mathrm{N\cdot m}}$

### 38

> A small 350-gram ball on the end of a thin, light rod is rotated in a horizontal circle of radius 1.2 m. Calculate (a) the moment of inertia of the ball about the center of the circle, and (b) the torque needed to keep the ball rotating at constant angular velocity if air resistance exerts a force of 0.020 N on the ball. Ignore air resistance on the rod and its moment of inertia.

#### Part A

$I= MR^2 = (0.350\;\mathrm{kg})(1.2\;\mathrm{m})^2 = \boxed{0.504\;\mathrm{kg\cdot m^2}}$

#### Part B

$\tau = r_{\perp}F = 1.2\;\mathrm{m}\cdot 0.020\;\mathrm{N} = \boxed{2.4\times 10^{-2}\;\mathrm{m\cdot N}}$

### 39

> <img src="../images/Problem%208-39.png" style="zoom:55%;float:right;" />Calculate the moment of inertia of the array of point objects shown in the figure about (a) the y axis, and (b) the x axis. Assume $m = 2.2\;\mathrm{kg},$ $M= 3.4\;\mathrm{kg}$, and the objects are wired together by very light, rigid pieces of wire. The array is rectangular and is split through the middle by the x axis. (c) About which axis would it be harder to accelerate this array?
>

#### Part A

$$
\begin{align*} \textsf{The Y Axis:}\;\;I = \sum M_i R_{ix}^2 = (m+M)\left[(0.50)^2 + (1.00)^2\right] = \boxed{7.0\;\mathrm{kg\cdot m^2}} \end{align*}
$$

#### Part B

$$
\begin{align*} \textsf{The X Axis:}\;\; I = \sum M_iR_{iy}^2 = 2(m+M)(0.25)^2 = \boxed{0.7\;\mathrm{kg\cdot m^2}}\end{align*}
$$

#### Part C

$$
\begin{align*}\textsf{It is harder to rotate about the y-axis as its moment of inertia is 10 times larger than the moment of inertia of the x-axis.}\end{align*}
$$

### 41

> A dad pushes tangentially on a small hand-driven merry-go-round and is able to accelerate it from rest to a frequency of 15 rpm in 10.0 s. Assume the merry-go-round is a uniform disk of radius 2.5 m and has a mass of 560 kg, and two children (each with a mass of 25 kg) sit opposite each other on the edge. Calculate the torque required to produce the acceleration, neglecting frictional torque. What force is required at the edge?

$\tau = I\alpha = (I_{\text{mgr}} + I_{\text{kids}})\dfrac{\Delta \omega}{\Delta t} = \left(\dfrac12 MR^2 + 2mR^2\right)\dfrac{(\omega\;\mathrm{rev/min})(2\pi\;\mathrm{rad/rev})}{(60\;\mathrm{s/min})t} = \boxed{320\;\mathrm{m\cdot N}}$

$F_\perp = \tau/R \approx \boxed{129.6\;\mathrm{N}}$

### 43

> <img src="../images/Problem%208-43.png" style="zoom:60%;float:right;overflow:auto;" />Let us treat a helicopter rotor blade as a long thin rod, as shown in Fig. 8–49. (a) If each of the three rotor helicopter blades is 3.75 m long and has a mass of 135 kg, calculate the moment of inertia of the three rotor blades about the axis of rotation. (b) How much torque must the motor apply to bring the blades from rest up to a speed of 6.0 rev/s in 8.0 s?

#### Part A

$I = 3\left(\dfrac13 M\ell^2\right) = (135\;\mathrm{kg})(3.75\;\mathrm{m})^2 = \boxed{1898\;\mathrm{kg\cdot m^2}}$

#### Part B

$\tau = I\alpha = (1898\;\mathrm{kg\cdot m^2})\left(\dfrac{(6.0\;\mathrm{rev/s})(2\pi\;\mathrm{rad/rev})}{8.0\;\mathrm{s}}\right) \approx \boxed{8900\;\mathrm{m\cdot N}}$

### 46

> <img src="../images/Problem%208-46.png" style="zoom:60%;float:right;overflow:auto;" />Two blocks are connected by a light string passing over a pulley of radius  0.15 m and moment of inertia I. The blocks move (towards the right) with an acceleration of $1.00\;\mathrm{m/s^2}$ along their frictionless inclines (see figure. (a) Draw free-body diagrams for each of the two blocks and the pulley. (b) Determine $F_{TA}$ and $F_{TB}$, the tensions in the two parts of the string. (c) Find the net torque acting on the pulley, and determine its moment of inertia, $I$.

#### Part A

See diagrams to the right.

<img src="../images/Problem%208-46a.png" style="zoom:35%;float:right;" /><img src="../images/Problem%208-46a2.png" style="zoom:35%;float:right;" />

#### Part B

Since the force vectors perpendicular to the surface cancel out, we only care for the forces acting parallel to the surface:

$F_{TA} = m(a + g\sin\theta_\alpha)= (8.0\;\mathrm{kg})(1.00\;\mathrm{m/s^2} + 9.8\sin(32^\circ)) = \boxed{49.55\;\mathrm{N}}$
$F_{TB} = m(-a+g\sin\theta_\beta) = (10.0\;\mathrm{kg})(-1.00 + 9.8\sin(61^\circ)) = \boxed{75.71\;\mathrm{N}}$

#### Part C

$\sum\tau = (F_{TB} - F_{TA})R = \boxed{3.92\;\mathrm{m\cdot N}}$
$\sum\tau =I\alpha \Longrightarrow I = \dfrac{(\sum \tau)R}{a} = \boxed{0.588\;\mathrm{m^2\cdot kg}}$

### 48

> A hammer thrower accelerates the hammer (mass = 7.30 kg) from rest within four full turns (revolutions) and releases it at a speed of 26.5 m/s. Assuming a uniform rate of increase in angular velocity and a horizontal circular path of radius 1.20 m, calculate (a) the angular acceleration, (b) the (linear) tangential acceleration, (c) the centripetal acceleration just before release, (d) the net force being exerted on the hammer by the athlete just before release, and (e) the angle of this force with respect to the radius of the circular motion. Ignore gravity.

#### Part A

$\alpha = \dfrac{\omega^2 - \omega_0^2}{2\Delta \theta} = \dfrac{\left[\frac{26.5\;\mathrm{m/s}}{1.20\;\mathrm{m}}\right]^2}{2(4(2\pi))} = \boxed{9.70\;\mathrm{rad/s^2}}$

#### Part B

$a = \dfrac{\alpha}{R} = (9.702\;\mathrm{rad/s^2})(1.20\;\mathrm{m}) = \boxed{11.64\;\mathrm{m/s^2}}$

#### Part C

$a_c = \dfrac{v^2}{R} = \dfrac{(26.5\;\mathrm{m/s})^2}{1.20\;\mathrm{m}} = \boxed{585.2\;\mathrm{m/s^2}}$

#### Part D

$F = ma_{\text{net}} = (7.30\;\mathrm{kg})\left(\sqrt{(11.64)^2 + (585.2)^2}\right) =  \boxed{4272\;\mathrm{N}}$

#### Part E

$\theta = \tan^{-1} \dfrac{a_{\text{tan}}}{a_{c}} = \boxed{1.14^\circ}$

### 50

> A centrifuge rotor has a moment of inertia of $3.25 \times 10^{-2}\;\mathrm{kg\cdot m^2}$. How much energy is required to bring it from rest to 8750 rpm?

$KE = \dfrac12 I\omega^2 = \dfrac12 (3.25\times 10^{-2}\;\mathrm{kg\cdot m^2}) (8750\;\mathrm{rev/min})^2 \left(\dfrac{1\;\mathrm{min}\cdot 2\pi\;\mathrm{rad}}{60\;\mathrm{s}\cdot 1\;\mathrm{rev}}\right)^2 = \boxed{13,640\;\mathrm{N\cdot m}}$

### 52

> A bowling ball of mass 7.25 kg and radius 10.8 cm rolls without slipping down a lane at 3.10 m/s. Calculate its total kinetic energy.

$KE = \dfrac12\left(Mv^2 + I\omega^2\right) = \dfrac12\left((7.25\cdot (3.10\cdot0.108)^2) + \dfrac25(7.25)(3.10)^2\right) = \boxed{14.34\;\mathrm{J}}$

### 54 ==confused==

> A rotating uniform cylindrical platform of mass 220 kg and radius 5.5 m slows down from 3.8 rev/s to rest in 16 s when the driving motor is disconnected. Estimate the power output of the motor (hp) required to maintain a steady speed of 3.8 rev/s.

$P=Wt=\Delta KE\cdot t = \dfrac12 MR\omega^2t = \dfrac12(220\cdot 5.5\cdot 3.8^2\cdot 16) = \boxed{190\;\mathrm{W}}$

### 56

> A sphere of radius $r = 34.5\;\mathrm{cm}$ and mass $m = 1.80\;\mathrm{kg}$ starts from rest and rolls without slipping down a 30.0° incline that is 10.0 m long. (a) Calculate its translational and rotational speeds when it reaches the bottom. (b) What is the ratio of translational to rotational kinetic energy at the bottom? Solve generally so you can answer: (c) do your answers in (a) and (b) depend on the radius of the sphere or its mass?

#### Part A

$mgh = \dfrac12 \cdot \dfrac25mr^2\omega^2 + \dfrac12m(r\omega)^2\Longrightarrow \omega = \sqrt{\dfrac{10gh}{7r^2}} = \boxed{24.25\;\mathrm{rad/s}}$

$v = r\omega = \boxed{8.37\;\mathrm{m/s}}$

#### Part B

$\dfrac{TKE}{RKE} = \dfrac{\dfrac12 m(r\omega)^2}{\dfrac12 I\omega^2} = \dfrac{mr^2\omega^2}{\dfrac25mr^2\omega^2} = \boxed{\dfrac{5}{2}}$

#### Part C

Since $v = r\omega$, only $\omega$ depends on the radius of the sphere as the greater the radius the smaller the rotational kinetic energy as fewer rotations take place. Also, in both cases, the masses cancel so therefore the mass has no effect on the ratio of kinetic energies and the end velocities of the sphere.



## Homework 3: Pg. 222 # 19, 24, 26, 31, 35, 36, 39, 47, 49, 55, 59, 62, 67, 73, 87, 93

### 19

> Pilots can be tested for the stresses flying high-speed jets in a whirling “human centrifuge,” which takes 1.0 min to turn through 23 complete revolutions before reaching its final speed. (a) What was its angular acceleration, and (b) what was its final angular speed in rpm?

#### Part A

$\theta = \omega_0 t + \dfrac12 \alpha t^2\Longrightarrow 23\;\mathrm{rev}\cdot 360\;\mathrm{deg/rev} = \dfrac12\alpha\left(60\;\mathrm{s}\right)^2\Longrightarrow\alpha = \boxed{4.6\;\mathrm{deg/s^2}}$

#### Part B

$\omega = \omega_0t + \dfrac12 \alpha t^2 = \dfrac12 (4.6)(60\;\mathrm{s}) = \boxed{138\;\mathrm{deg/s}}$

### 24

> A 52-kg person riding a bike puts all her weight on each pedal when climbing a hill. The pedals rotate in a circle of radius 17 cm. (a) What is the maximum torque she exerts? (b) How could she exert more torque?

#### Part A

$\tau = F\cdot d = 52g\;\mathrm{N}\cdot0.17\;\mathrm{m} = 86.632\;\mathrm{N\cdot m}$

#### Part B

She could get bigger pedals that rotate in a larger circle, therefore increasing the torque on the pedal.

### 26

> A person exerts a horizontal force of 42 N on the end of a door 96 cm wide. What is the magnitude of the torque if the force is exerted (a) perpendicular to the door and (b) at a 60.0° angle to the face of the door?

#### Part A

$\tau = F_\perp \cdot d = 42\;\mathrm{N} \cdot 0.96\;\mathrm{m} = \boxed{40.32\;\mathrm{N\cdot m}}$

#### Part B

$\tau = F_\perp \cdot d = 42\sin(60^\circ)\;\mathrm{N}\cdot 0.96\;\mathrm{m} \approx \boxed{34.92\;\mathrm{N\cdot m}}$

### 31

> Estimate the moment of inertia of a bicycle wheel 67 cm in diameter. The rim and tire have a combined mass of 1.1 kg. The mass of the hub (at the center) can be ignored (R = 0).

$I = MR^2 = 1.1\;\mathrm{kg}\cdot (0.67\;\mathrm{m})^2 = \boxed{0.49\underline{4}\;\mathrm{kg\cdot m^2}}$

### 35

> The forearm accelerates a 3.6-kg ball at $7.0\;\mathrm{m/s^2}$ by means of the triceps muscle, as shown. Calculate (a) the torque needed, and (b) the force that must be exerted by the triceps muscle. Ignore the mass of the arm.

$$
F = ma = 3.6\cdot 7.0 = 25.2\;\mathrm{N}\\
\tau = F\cdot d = 25.2\cdot 0.31 = 
$$



### 36

>  



### 39

>  



### 47

>  



### 49

>  



### 55

>  



### 59

>  



### 62

>  



### 67

>  



### 73

>  



### 87

>  



### 93

>  


