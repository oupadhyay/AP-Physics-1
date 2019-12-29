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

#### Part A<img src="/home/ou/Downloads/AP%20and%20SAT%20Subject/AP/physics/md/AP-Physics-1/images/Example%208-2.png" style="zoom:70%;float:left" />

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
\overline{\alpha} &= \dfrac{\Delta\theta}{\Delta t}\tag{average angular acceleration} \\
\alpha &= \lim_{\Delta t \rightarrow 0} \dfrac{\Delta \theta}{\Delta t}\tag{instantaneous angular acceleration}
\end{align}
$$

###  Relation to Linear Quantities

Now, each point of a rotating object also has a linear velocity $v$ and a linear acceleration $a$. ==We can now relate the linear quantities to the angular quantities.== Considering a point $P$ located $r$ from the axis of rotation, 
$$
v = \dfrac{\Delta \ell}{\Delta t} = r\dfrac{\Delta \theta}{\Delta t}\tag{instantaneous*}
$$

Since $\dfrac{\Delta \theta}{\Delta t} = \omega$, ==$\boxed{v = r\omega}$.==

$a_{\text{tan}} = \dfrac{\Delta v}{\Delta t} = r \dfrac{\Delta \omega}{\Delta t} = r\alpha$

$\textsf{Total linear acceleration: }\vec{\mathbf{a}} = \vec{\mathbf{a}_{\text{tan}}} + \vec{\mathbf{a}_{R}}$

| 8-1              | Linear and Rotational Quantities |            |                            |
| ---------------- | -------------------------------- | ---------- | -------------------------- |
| Linear           | Type                             | Rotational | Relation                   |
| $x$              | displacement                     | $\theta$   | $x = r\theta$              |
| $v$              | velocity                         | $\omega$   | $v = r\omega$              |
| $a_{\text{tan}}$ | acceleration                     | $\alpha$   | $a_{\text{tan}} = r\alpha$ |



## Constant Angular Acceleration



## Rolling Motion (Without Slipping)



## Torque



## Rotational Dynamics; Torque and Rotational Inertia



## Solving Problems in Rotational Dynamics



## Rotational Kinetic Energy



## Angular Momentum and Its Conservation



## Vector Nature of Angular Quantities