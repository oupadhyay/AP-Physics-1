# Derivations
$$
\textbf{Period of an Orbit} \\
\begin{align*}
F_g &= \dfrac{mv^2}{R} \\
\dfrac{GmM_E}{R^2} &= \dfrac{mv^2}{R} \\
\dfrac{GM_E}{R} &= v^2 \\
\dfrac{GM_E}{R} &= \left(\dfrac{2\pi R}{T}\right)^2 \\
\dfrac{GM_E}{R} &= \dfrac{4\pi^2 R^2}{T^2} \\
T^2 &= \dfrac{4\pi^2 R^3}{GM_E} \\
T &= \boxed{\sqrt{\dfrac{4\pi^2 R^3}{GM_E}}}
\end{align*} \\
$$

$$
\textbf{Speed of Satellite in Orbit} \\
\begin{align*}
\sum F_{\text{inwards}} &= F_g = m_{\text{satellite}} \cdot a_c \\
\dfrac{m_{\text{satellite}}\cdot v_t^2}{r} &= \dfrac{G\cdot m_E\cdot m_{\text{satellite}}}{r^2} \\
v_t &= \boxed{\sqrt{\dfrac{G\cdot m_E}{r}} = \sqrt{\dfrac{G\cdot m_E}{r_E + \text{altitude}}}}
\end{align*} \\
$$

$$
\textbf{Conical Pendulum}\\
\begin{align}
F_{{T}_{y}} &= F_T\cos\theta = mg \\  
F_{{T}_{in}} &= F_T\sin\theta = \dfrac{mv_t^2}{r} \\ \\
F_T &= \dfrac{mg}{\cos\theta} \Longrightarrow F_{{T}_{in}} = \left(\dfrac{mg}{\cos\theta}\right)\sin\theta  \\
m\left(\dfrac{\left(\dfrac{2\pi r}{T}\right)^2}{r}\right) &\Longrightarrow g\tan\theta = \dfrac{4\pi^2 r}{T^2} \\
\sin\theta = \dfrac{r}{L} &\Longrightarrow r = L\sin\theta \\
g\dfrac{\sin\theta}{\cos\theta} = \dfrac{4\pi^2L\sin\theta}{T^2} &\Longrightarrow T = \boxed{\sqrt{\dfrac{4\pi^2L\cos\theta}{g}}}
\end{align}
$$

$$
\textbf{Velocity to Go in a Circle}\\
\begin{align}
F_C = t - mg \Rightarrow F_C &= mg \tag{tension is zero} \\
mg &= \dfrac{mv^2}{r} \Longrightarrow v = \boxed{\sqrt{rg}}
\end{align}
$$

$$
\textbf{Max Velocity with a Breaking Tension }\\
\begin{align}
T_{\text{max}} - mg &= \dfrac{mv^2}{r} \\
v &= \boxed{\sqrt{\dfrac{r}{m}\left(T_{\text{max}} - mg\right)}}
\end{align}
$$

# Formula Sheet Ch. 6 - 8

$$
\begin{align}
d = \dfrac{v_1^2}{2g\mu_s} \tag{min. braking distance}\\
v_1 = \sqrt{2\mu_k gd} \tag{derived from above} \\ 
W_{\text{nonconservative}} = \Delta\text{KE} + \Delta\text{PE} \tag{friction}\\
W_{\text{net}} = \Delta\text{KE} = \dfrac12mv_2^2 - \dfrac12mv^2_1 \tag{work-energy principle}\\
PE_{G} = mgy \;\;\;\;\;\;\mathbf{|}\;\;\;\;\;\; PE_{el} = \dfrac12kx^2 \tag{potential energy}\\
v = \sqrt{2gh\left(1 - \dfrac{\mu_s}{\tan\theta}\right)} \tag{velocity of block with friction} \\
k = m\left(\dfrac{a_{\text{max}}}{v_0}\right)^2 \tag{spring constant $a_{\text{max}}$ horizontally} \\
F_{\text{tan}} = \dfrac{mg\sin\theta_{\text{ramp}} \cdot d_{\text{one rev}}}{2\pi r_{\text{pedal}}} \tag{cycling up a ramp}\\
\end{align}
$$

------


$$
\begin{align}
\text{A spring (mass }m\text{, constant }k&\text{, displacement }x_0\text{, initial velocity }v_0\text{) :} \\
v_{\text{max}} &= \sqrt{v_0^2 + \dfrac{k}{m} x_0^2 } \tag{maximum speed} \\
x_{\text{max}} &= \sqrt{x^2_0 + \dfrac{m}{k}v^2_0} \tag{maximum stretch} \\
\end{align}
$$

$$
\begin{align}
\tag{elastic}
v_A' &=\left(\dfrac{m_A - m_B}{m_A + m_B}\right) v_A \\
\tag{elastic}
v_B' &=\left(\dfrac{2m_A}{m_A + m_B}\right) v_A \\
\tag{height - level ground}
h_A &= \dfrac{v_A^2}{2g}\\
KE &= \dfrac{p^2}{2m} = \dfrac12 mv^2 \tag{KE formulas}\\
KE\;(J) &= F\Delta t = \int F\;dt =\Delta p \tag{interpretations}\\
x_{CM} &= \dfrac{m_A x_A + m_B x_B + \cdots}{m_A + m_B + \cdots} \tag{center of mass}\\
F_{\text{net}} &= Ma_{CM} \\
F &= ma_{net} = m(\sqrt{a_c^2 + a_{lin}^2}) \tag{rotational + linear} \\
\theta &= \tan^{-1} \dfrac{a_{\text{tan}}}{a_{c}} \tag{angle of rotational force} \\

\end{align}
$$

## Chapter 8 # 47, 48

### 47

>  An Atwood machine consists of two masses, $m_A = 65\;\mathrm{kg}$ and $m_B = 75\;\mathrm{kg}$, connected by a massless inelastic cord that passes over a pulley free to rotate. The pulley is a solid cylinder of radius R = 0.45 m and mass 6.0 kg. (a) Determine the acceleration of each mass. (b) What % error would be made if the moment of inertia of the pulley is ignored? <u>Hint:</u> The tensions $F_{TA}$ and $F_{TB}$ are not equal.

#### Part A

$$
a = \dfrac{g(m_B - m_A)}{m_A + m_B + I/R^2} = \dfrac{g(m_B - m_A)}{m_A + m_B + \frac12m_pR^2/R^2} = \boxed{0.685\;\mathrm{m/s^2}}
$$

#### Part B

$$
a = \dfrac{g(m_B - m_A)}{m_A + m_B} = 0.700\;\mathrm{m/s^2}\Longrightarrow \dfrac{0.0147}{0.6853} = \boxed{2.15\;\%}
$$

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

## Chapter 6: Pg. 164 # 8, 10, 11, 13, 14, 22, 23, 24, 25, 40, 42, 43, 44, 45, 56, 71

### Notes

| Problem | Notes                                                        |
| ------- | ------------------------------------------------------------ |
| 10      | Since the piano is not accelerating, the net force on the piano is 0, so the net work done on the piano is also 0. This can also be seen by adding the two work amounts calculated. |
| 11      | Since the force is halved, the distance to pull is doubled.  |
| 12      | $\sum F_x = F_P\cos(\phi + \theta) - mg \sin\theta =0 \rightarrow F_P = \dfrac{mg\sin\theta}{\cos(\phi + \theta)}$<br /> $W_{mg} = mgd\cos(102^\circ) = \boxed{-244.5\;\mathrm{J}}$<br />$F_N\text{ acts perpendicularly so }W_{normal} = \boxed{0}$<br />$W_P = F_P d \cos (29^\circ) = mgd\sin(12^\circ) = \boxed{244.5\;\mathrm{J}}$ |
| 13      | **a)** From $x \in [0,10]$, we get $W = \dfrac12 (400)(10+4) = \boxed{2.8\;\mathrm{kJ}}$<br />**b)** From $x\in [0,15]$, we get $W = -700+2800 = \boxed{2.1\;\mathrm{kJ}}$ |
| 14      | **a)** $W_{gas} = F_{gas}d_{gas} = F_{gas}d_{plane} = \boxed{1.1\times 10^7\;\mathrm{J}}$<br />**b)** $W = \text{area under the curve} = \boxed{5.0\times 10^7 \;\mathrm{J}}$ |
| 22      | $W = \Delta KE = F_{fr}d\cos (180) = \dfrac12 mv_2^2 - \dfrac12 mv_1^2 \Longrightarrow -\mu_s mgd = -\dfrac12 mv_1^2$<br />$d = \dfrac{v_1^2}{2g\mu_s} \Rightarrow 1.5^2 = \boxed{2.25}$ |
| 23      | Using the same equation, $v_1 = \sqrt{2\mu_k gd}$<br />The mass does not affect the problem, since both the change in kinetic energy and the work done by friction are proportional to the mass. The mass cancels out of the equation. |
| 24      | Use kinetic energy equation $KE = \dfrac12 mv^2$             |
| 25      | **a) ** $\sum F = F_T - mg = ma = 0.16 mg \Longrightarrow F_T = 1.16mg = \boxed{3010\;\mathrm{N}}$<br />**b)** $W_{net} = F_{net}d = 0.16mgd = \boxed{7480\;\mathrm{J}}$<br />**c)** $W_{\text{cable}} = F_T d = 1.16mgd = \boxed{5.42\times10^4\;\mathrm{J}}$<br />**d)** $W_G = mgd \cos 180 = -mgd = \boxed{-4.67\times 10^4\;\mathrm{J}}$<br />**e)** $W_{net} = KE_2 - KE_1 \Rightarrow \dfrac12 mv_2^2 - \dfrac12mv_1^2$ <br />$v_2 = \sqrt{\dfrac{2W_{net}}{m}+v_1^2} = \boxed{7.51\;\mathrm{m/s}}$ |
| 40      | $v_2 = \sqrt{2gy_1} = \boxed{25}$<br /> $v_3 = \sqrt{2g(y_1 - y_3)} = \boxed{11}$<br />$v_4 = \sqrt{2g(y_1 - y_4)} = \boxed{19}$ |
| 42      | $W_{\text{spring}} = \Delta KE \Longrightarrow -\dfrac12 k x^2 = -\dfrac12 mv_0^2 \Longrightarrow x_{\text{max}} = v_0 \sqrt{\dfrac{m}{k}}$<br />$ma_{max} = kx_{max} \Rightarrow k = m\left(\dfrac{a_{\text{max}}}{v_0}\right)^2 = \boxed{2648\;\mathrm{N/m}}$ |
| 43      | $Mg(x+h) = \dfrac12 kx^2$ <br />$F_{\text{spring}} = 6.0 Mg = kx \Longrightarrow Mg\left(\dfrac{6Mg}{k} + h\right) = \dfrac12 k\left(\dfrac{6Mg}{k}\right)^2 \Longrightarrow k = \boxed{\dfrac{12Mg}{k}}$ |
| 44      | $v_{\text{max}} = \sqrt{v_0^2 + \dfrac{k}{m} x_0^2 }$<br />$x_{\text{max}} = \sqrt{x^2_0 + \dfrac{m}{k}v^2_0}$ |
| 45      | $W = \Delta PE = mg\Delta y = \boxed{9.2\times 10 ^4\;\mathrm{J}}$<br /> Work by the force through one revolution is equal to the average tangential force times the circumference of the circular path of the pedals which is equal to the change in potential energy. <br />$W = F_{tan} \cdot 2\pi r = \Delta PE = mg \Delta y = mgd\sin\theta$<br />$F_{tan} = \dfrac{mg\sin\theta_{\text{ramp}} \cdot d_{\text{one rev}}}{2\pi r_{\text{pedal}}} = \boxed{433\;\mathrm{N}}$ |

