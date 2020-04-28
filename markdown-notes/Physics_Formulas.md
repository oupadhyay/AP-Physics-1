# Formula Sheet

## Derivations

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
\textbf{Ballistic Pendulum} \\
h= L(1-\cos\theta) \\
v_{sys} = \dfrac{mv_b}{m_b + m_p}\\\\
\dfrac12(m_b + m_p)v^2_{sys} = (m_p + m_b)gh\\
\dfrac{1}{2}(m_b+m_p)\dfrac{m_b^2v_1^2}{(m_b + m_p)^2}=(m_b+m_p)gh \\
v_{b} = \sqrt{2gh}\left(1+\dfrac{m_p}{m_b}\right) \\
v_{b} = \boxed{\sqrt{2gL(1-\cos\theta)}\left(1+\dfrac{m_p}{m_b}\right)}
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

$$
\textbf{Falling to Earth Time}\\
T_E = \text{period of revolution}\\
a = \text{semimajor axis}\\
2t = \text{period with no orbital velocity}\\
a/2 = \text{major axis with no orbital velocity}\\ \\
\begin{align}
\dfrac{(2t)^2}{T_E^2} &= \dfrac{\left(\dfrac{a}{2}\right)^3}{a^3} \\
t^2 &= \dfrac{1}{2}\dfrac{T_E^2}{16} \\
t &= \boxed{\dfrac{T_E}{4\sqrt2}} \\\\
\text{for Earth: }t &= \dfrac{365.26}{4\sqrt2} = 64.57\;\mathrm{days}
\end{align}
$$

## Formula Sheet Ch. 6 - 8

$$
\textbf{One Object} \\
\begin{align}
d &= \dfrac{v_0^2}{2g\mu_s} \tag{min. braking distance}\\
v_0 &= \sqrt{2\mu_k gd} \tag{derived from above} \\ \\
\end{align} \\
$$

$$
\textbf{Two Objects Colliding} \\
\begin{align}
d = \dfrac{v_0^2m^2}{2g\mu_k(m+M)^2} \tag{min. braking distance}\\\\
v_0 = \dfrac{M+m}{m}\sqrt{2\mu_k gd} \tag{derived from above}
\end{align}
$$

$$
\textbf{Energy}\\
\begin{align}
W_{\text{nonconservative}} = \Delta\text{KE} + \Delta\text{PE} \tag{friction}\\
W_{\text{net}} = \Delta\text{KE} = \dfrac12mv_2^2 - \dfrac12mv^2_1 \tag{work-energy principle}\\
PE_{G} = mgy \;\;\;\;\;\;\mathbf{|}\;\;\;\;\;\; PE_{el} = \dfrac12kx^2 \tag{potential energy}\\\\
v = \sqrt{2gh\left(1 - \dfrac{\mu_s}{\tan\theta}\right)} \tag{velocity of block with friction from ramp} \\
k = m\left(\dfrac{a_{\text{max}}}{v_0}\right)^2 \tag{spring constant with $a_{\text{max}}$ horizontally} \\
F_{\text{tan}} = \dfrac{mg\sin\theta_{\text{ramp}} \cdot d_{\text{one rev}}}{2\pi r_{\text{pedal}}} \tag{cycling up a ramp}\\
\end{align}
$$

------


$$
\begin{align}
\textbf{A spring }\textbf{(mass }m\textbf{, constant }k&\textbf{, displacement }x_0\textbf{, initial velocity }v_0\textbf{) :} \\
v_{\text{max}} &= \sqrt{v_0^2 + \dfrac{k}{m} x_0^2 } \tag{maximum speed} \\
x_{\text{max}} &= \sqrt{x^2_0 + \dfrac{m}{k}v^2_0} \tag{maximum stretch} \\
\end{align}
$$

------

$$
\textbf{Momentum and SHO} \\
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

$$
\begin{align}
\textbf{Angular Equations for}& \textbf{ Constant Angular Acceleration} \\
\omega &= \omega_0 + \alpha t \tag{constant $\alpha$, 1} \\
\theta &= \omega_0t + \dfrac12\alpha t^2 \tag{constant $\alpha$, 2}\\
\omega^2 &= \omega_0^2 + 2\alpha \theta \tag{constant $\alpha$, 3}\\
\overline{\omega} &= \dfrac{\omega + \omega_0}{2} \tag{constant $\alpha$, 4} \\\\
\textbf{}& \textbf{Torques} \\
|\tau| &= rF\sin\theta \\
\tau = mr^2 \alpha &\Rightarrow \text{Inertia} = \sum mr^2 \\
\text{rotational KE} &= \dfrac12 I\omega^2 \\
KE &= \dfrac12Mv^2_{CM} + \dfrac12 I_{CM}\omega^2 \\
L &= I\omega \\

\end{align}
$$

```json
"}& \text{"
for aligningText(align_environment) {
    state: "very useful"
} else {
    state: "do not use"
}
```

