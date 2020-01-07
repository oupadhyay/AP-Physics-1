# Rotational Motion Notes

Until now, we have talked about **translational motion.** Now, we will deal with **rotational motion.** Mainly, we will be considering the rotation of **rigid motion,** which is an object with a definite shape that doesn’t change (the particles of the object stay in fixed positions relative to each other) and is an approximation of real life. 

## Angular Quantities

By purely rotational motion we mean that all points in the object move in *circles.* The center of these circles are called the **axis of rotation.** ==To indicate **angular position,** we specify the angle $\theta$ with respect to a reference line.== The mathematics of rotational motion is simplified with the use of *radians,*which is defined as the angle subtended by an arc whose length is equal to the radius. Any angle $\theta$ is given by the radius $r$ and arc length $\ell$:
$$ {==}
\begin{align}
\theta = \dfrac{\ell}{r}\tag{$\theta$ in radians; arc length $\ell$; radius $r$} \\
\Delta \ell = r \Delta \theta \tag{$\theta$ in radians; arc length $\ell$; radius $r$}
\end{align}
$$
Radians can be related to degrees as $\theta = \ell/r = 2\pi r/r = \boxed{2\pi = 360^\circ}$.

### Example 8-2

> A bird’s eye can distinguish objects that subtend an angle no smaller than about $3\times10^{-4}\;\mathrm{rad}$. 
> (a) How many degrees is this? 
> (b) How small an object can the bird just distinguish when flying at a height of 100 m?

#### Part A<img src="../images/Example%208-2.png" style="zoom:70%;float:left" />

$(3\times 10^{-4})\left(\dfrac{360^\circ}{2\pi}\right) = \boxed{0.017^\circ}$

#### Part B

Using $\ell = r\theta$ works as the arc length is a good approximate for the chord length for small angles such as in this example. Since r = 100\;\mathrm{m} and \theta = 3\times 10^{-4} (making sure that we use the radian measure instead of the degree measure), we find

$\ell = r\theta = \left(100\;\mathrm{m}\right)\left(3\times 10^{-4}\right) = \boxed{0.03\;\mathrm{m}}$

------

### Angular Displacement, Velocity, and Acceleration

Like translational motion, ==there is also **angular displacement,**  **angular velocity,** and **angular acceleration.**==
Here are the basic motion equations for rotational motion:
$$
\begin{equation}
\Delta \theta = \theta_2 - \theta_1 \tag{angular displacement} \\
\end{equation}
$$

$$
\begin{align}
\overline{\omega} &= \dfrac{\Delta \theta}{\Delta t} \tag{instantaneous angular velocity} \\
\omega &= \lim_{\Delta t \rightarrow 0} \dfrac{\Delta \theta}{\Delta t}\tag{instantaneous angular velocity}
\end{align}
$$

$$
\begin{align}
\overline{\alpha} &= \dfrac{\Delta v}{\Delta t}\tag{average angular acceleration} \\
\alpha &= \lim_{\Delta t \rightarrow 0} \dfrac{\Delta v}{\Delta t}\tag{instantaneous angular acceleration}
\end{align}
$$

###  Relation to Linear Quantities

Now, each point of a rotating object also has a linear velocity $v$ and a linear acceleration $a$. ==We can now relate the linear quantities to the angular quantities.== Considering a point $P$ located $r$ from the axis of rotation, 
$$
v = \dfrac{\Delta \ell}{\Delta t} = r\dfrac{\Delta \theta}{\Delta t}\tag{instantaneous*}
$$

Since $\dfrac{\Delta \theta}{\Delta t} = \omega$, ==$\boxed{v = r\omega}$.== 

Also, we can use this to see that the angular acceleration is related to the tangential linear acceleration of a point by: $a_{\text{tan}} = \dfrac{\Delta v}{\Delta t} = r \dfrac{\Delta \omega}{\Delta t}\Longrightarrow$ ==$\boxed{a_{\text{tan}} = r \alpha}.$==

Total linear acceleration: ==$\vec{\mathbf{a}} = \vec{\mathbf{a}_{\text{tan}}} + \vec{\mathbf{a}_{R}}$==where $a_{\text{tan}} = r\alpha$ and $a_R = \dfrac{(r\omega)^2}{r} = \omega^2 r.$ 

| 8-1              | Linear and Rotational Quantities |            |               |
| ---------------- | -------------------------------- | ---------- | ------------- |
| Linear           | Type                             | Rotational | Relation      |
| $x$              | displacement                     | $\theta$   | $x = r\theta$ |
| $v$              | velocity                         | $\omega$   | $v = r\omega$ |
| $a_{\text{tan}}$ | acceleration                     |            |               |

### Frequency and Period

$$
\begin{align*}
f &= \dfrac{\omega}{2\pi} \Longrightarrow \omega = 2\pi f \\
T &= \dfrac{1}{f}
\end{align*}
$$

## Constant Angular Acceleration

The angular equations for **constant angular acceleration** will be analogous to the linear acceleration equations. They are:
$$
\textbf{Angular Equations for Constant Angular Acceleration} \\
\begin{align}
\omega &= \omega_0 + \alpha t \tag{constant $\alpha$, 1} \\
\theta &= \omega_0t + \dfrac12\alpha t^2 \tag{constant $\alpha$, 2}\\
\omega^2 &= \omega_0^2 + 2\alpha \theta \tag{constant $\alpha$, 3}\\
\overline{\omega} &= \dfrac{\omega + \omega_0}{2} \tag{constant $\alpha$, 4}
\end{align}
$$


## Rolling Motion (Without Slipping)

When something is rolling without slipping, then there is a simple relation between the translation and angular velocities:
==$v = r\omega$==.

## Torque



## Rotational Dynamics; Torque and Rotational Inertia



## Solving Problems in Rotational Dynamics



## Rotational Kinetic Energy



## Angular Momentum and Its Conservation



## Vector Nature of Angular Quantities