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