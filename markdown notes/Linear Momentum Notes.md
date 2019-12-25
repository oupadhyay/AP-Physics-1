# Linear Momentum Notes

## Momentum

- The **linear momentum** of an object is defined by ==$\boxed{\vec{\mathbf{p}} = m\vec{\mathbf{v}}}$==

- Newton originally formulated his second law in terms of momentum as the rate of change of the momentum is equal to the net force applied to it: ==$\boxed{\Sigma\vec{\mathbf{F}} = (\Delta\vec{\mathbf{p}})/(\Delta t)}$==

### Example 7-1

>  For a top player, a tennis ball may leave the racket on the serve with a speed of 55 m/s. If the ball has a mass of 0.060 kg and is in contact with the racket for about 4 ms estimate the average force on the ball. Would this force be large enough to lift a 60-kg person? 

$F = \dfrac{\Delta p}{\Delta t} = \boxed{825\;\mathrm{N}}$
$F_G = mg \approx 590\;\mathrm{N} < 825\;\mathrm{N}\Longrightarrow \boxed{\textsf{Yes}}$

## **The Conservation of Momentum (CofM)**

- The total momentum of an isolated system of objects remains constant:
  ==$\boxed{m_A v_A + m_B v_B = m_A v'_A + m_Bv'_B}\;\;\;\;\; \left[\Sigma F_{\text{ext}} = 0\right]$==

### Example 7-3

> If one car moves at 24.0 m/s and the other is at rest, what is the resultant velocity if they link up as a result of the collision.

$v' = \boxed{\dfrac12} (v_A + v_B)$

## Impulse

- ==$\boxed{\textsf{Impulse} = F\Delta t = \Delta p = m\Delta v}.$==

## Conservation of Energy and Momentum in Collisions

- **Elastic**: ==$\dfrac12 m_Av_A^2 + \dfrac12m_Bv_B^2 = \dfrac12 m_Av_A^{'2} + \dfrac12m_Bv_B^{'2}$==
- **Inelastic**: ==$\dfrac12 m_Av_A^2 + \dfrac12m_Bv_B^2 = \dfrac12 m_Av_A^{'2} + \dfrac12m_Bv_B^{'2} + \text{thermal and other energy}$==

## Elastic Collisions in 1-D

- **Derivation of  Head-On Elastic Collision Equation**
  Momentum and kinetic energy are conserved is because it is an elastic collision. Hence, 
  $$
  m_A(v_A - v_A') = m_b (v_b - v_B') \\
  
  \rule{17cm}{0.5pt}\\
  \dfrac12m_Av_A^2 + \dfrac12m_bv_B^2 = \dfrac12m_Av_A^{'2} + \dfrac12m_bv_B^{'2} \\
  \Rightarrow m_A(v_A^2 - v_A^{'2}) = m_B(v_B^2 - v_B^{'2})
  $$
  With the simplified forms of the equations, we divide the first from the second to get:
  ==$\boxed{(v_A + v_A') =(v_b + v_B')}$==

### Example 7-8

> A proton of mass 1.01 u traveling with a speed $3.60 \times 10^4$ m/s has an elastic head-on collision with a helium nucleus with mass 4.00 u initially at rest. What are the velocities of the proton and helium nucleus?

We start with the conservation of momentum:
$m_pv_p + 0 = m_pv'_p + m_{He}v'_{He}$

However, since the collision is elastic, we can use the equation we previously derived:
$v_p + v'_p = 0 + v'_{He}\Longrightarrow v'_p = v'_{He} - v_p$

Plugging back into the conservation of momentum equation, we get:
$m_pv_p = m_p\left(v'_{He} - v_p\right) + m_{He}v'_{He}\Longrightarrow v'_{He} = \dfrac{2m_pv_p}{m_p + m_{He}} = \boxed{1.45\times 10^4\;\mathrm{m/s}}$

Now, we can find the velocity of the proton by:
$v'_p = v'_{He} - v_p = (1.45 - 3.60)\times 10^4 = \boxed{-2.15\times 10^4\;\mathrm{m/s}}$

### Example 7-9

> The ballistic pendulum is a device used to measure the speed of a projectile, such as a bullet. The projectile, of mass m, is fired into a large block (of wood or other material) of mass M, which is suspended like a pendulum. (Usually, M is somewhat greater than m.) As a result of the collision, the pendulum and projectile together swing up to a maximum height h. Determine the relationship between the initial horizontal speed of the projectile, v, and the maximum height h.

<img src="/home/ou/Downloads/AP and SAT Subject/AP/physics/md/AP-Physics-1/images/Example 7-9.JPG" style="zoom:40%;float:left" /> For Part A, since gravity has no appreciable effect during the small time frame of the collision, momentum is conserved. Hence,
$mv + 0 = (m + M)v'$

For Part B, gravity is a conservative force, so mechanical energy is conserved. Hence,
$\dfrac12(m + M)v'^2 + 0 = 0 + (m+M)gh\Longrightarrow v' = \sqrt{2gh}$

Plugging this back into the CofM equation,
$v = \boxed{\dfrac{m + M}{m}\sqrt{2gh}}$



## Center of Mass (CM)

The **center of mass** of an extended object or group of objects is the point at which the net force can be considered to act on the object(s) as a whole. The x coordinate of the CM is: ==$x_{CM} = \boxed{\dfrac{m_Ax_A + m_Bx_B + \cdots}{m_A + m_B + \cdots}}$== and Newton's second law turns into ==$Ma_{CM} = F_{net}$==.

