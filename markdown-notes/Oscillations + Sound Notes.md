# Oscillations and Waves Notes

## Equations

- $F = -kx$
- $f = \dfrac{1}{T}$
- $T = 2\pi\sqrt{\dfrac{m}k}$
- $E = \dfrac12 mv^2 + \dfrac12 kx^2$
- $T = 2\pi\sqrt{\dfrac{l}g}$
- $v_{max} = A\sqrt{k}{m}$
- $v = v_{max}\sqrt{1-\left(\dfrac{x}{A}\right)^2}$
- $v = \lambda f$
- $I \propto A^2 \;\;\;//\;\;\; I\propto f^2 \;\;\;//\;\;\; I\propto \dfrac{1}{r^2}$
- $I = \dfrac{P}{4\pi r^2}$
- $A = \sqrt{\dfrac{P}{4\pi r^2}}$
- $E = \dfrac12 kA^2 =  2\pi^2 m f^2 A^2$
- $y = A\sin\left(\left(\dfrac{2\pi}{\lambda}\right)\left(x\pm vt\right)\right)$
- Diffraction: $\theta = \lambda / \ell$

# Sound Notes

## Notes

### Sound

- **Sound level** in decimals: $\beta = 10 \log\left(\dfrac{I}{I_0}\right)$
- an **octave** = doubling of frequency
- The pitch is normally determined by the lowest resonant frequency, the **fundamental**, which corresponds to nodes occurring only at the ends
  - $f_n = nf_1 = n\dfrac{v}{\lambda} = n \dfrac{v}{2\ell}$
- The strings on an instrument sound different because they have different densities.
  - $\mu \textsf{ (density)} = m/\ell$
  - $v = \sqrt{F_T / \mu}$
- <img src="../images/OpenTubeHarmonics.png" style="zoom:70%;" />
- <img src="../images/OneEndClosedTubeHarmonics.png" style="zoom:70%;" />
- **Ultrasound** 
  - used in many applications include sonar and medical imaging
  - higher than 20,000 Hz

### Doppler Effect

- The modulation of the pitch as an object moves away from you or comes towards you. 
- **Derivation**
  - $T = \dfrac{1}{f} = \dfrac{\lambda}{v_{\text{sound}}}$
  - In a time T, $d = v_{sound}T = \lambda$ and $d_{\text{source}} = v_{\text{source}}T$
  - $\lambda' = d - d_{\text{source}} = \lambda\left(1 - \dfrac{v_{\text{source}}}{v_{\text{sound}}}\right)$
  - $f’ = \dfrac{v_{\text{sound}}}{\lambda’} = \dfrac{v_{\text{sound}}}{\lambda\left(1 - \dfrac{v_{\text{source}}}{v_{\text{sound}}}\right)}$

#### Summary of Equations

$$
\begin{align*}
f' &= \dfrac{f}{1 - \dfrac{v_{\text{source}}}{v_{\text{sound}}}} 
\tag*{$\mathbf{\textsf{[source moving toward stationary observer]}}$} \\
f' &= \dfrac{f}{1 - \dfrac{v_{\text{source}}}{v_{\text{sound}}}} 
\tag*{$\mathbf{\textsf{[source moving away from stationary observer]}}$} \\
f' &= f\left(1 + \dfrac{v_{\text{observed}}}{v_{\text{sound}}}\right) \tag*{$\textsf{[observer moving toward stationary source]}$} \\
f' &= f\left(1 - \dfrac{v_{\text{observed}}}{v_{\text{sound}}}\right) \tag*{$\textsf{[observer moving away from stationary source]}$} \\
f' &=  f\left(\dfrac{v+v_0}{v - v_0}\right) \tag*{$\textsf{[source moving towards the stationary observer]}$} \\
f' &=  f\left(\dfrac{v-v_0}{v + v_0}\right) \tag*{$\textsf{[source moving away the stationary observer]}$} \\
\end{align*}
$$

