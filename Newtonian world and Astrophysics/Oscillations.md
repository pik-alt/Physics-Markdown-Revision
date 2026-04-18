**An oscillation is the back-and-forth movement from an equilibrium position**

![[Pendulum.png|481]]

This diagram shows the information very well

**The minimum velocity the bob experiences is when it's at amplitude (farthest distance from the centre)
The maximum velocity is when the bob is at the equilibrium position, usually signified with $x_{0}$**

We can model oscillations using [[Circular Motion]], where the displacement is the horizontal component of the circular path and the amplitude is the radius.
(excuse the drawing)
![[circular oscillations.jpg|469]]

if you imagine moving forward in time as stepping through the curve of the circle, and then the displacement becomes the horizontal distance the point is from the centre

You can also draw this using a trig graph:
![[cos oscillations.png]]
$x$ = the displacement from $x_{0}$

$x = A\cos\theta$
(note: it could be either cos or sin depending on if the object starts in equilibrium or at amplitude)

$\theta = \omega t$

$\therefore x=A\cos\omega t$ (f.b.)

One derivation (which I don't fully understand except through calculus) later

$v_{x} = -v\sin\theta$
and something happens(???)
$v_{x} = -\omega A\sin\omega t$

where $v_{x} = \text{velocity of the oscillating body}$

**At equilibrium: $x=0, |v_{x}|=\text{max}$**
**At amplitude: $|x| = \text{max}, v_{x = 0}$**


next...

$a = \text{acceleration towards equillibrium}$

$a = \frac{F}{m}$
for an oscillating body is only the $x$ component, so

$a = -\frac{F}{m}\cos\theta$

$F=m\omega^{2}r = m\omega^{2}A$
$\theta=\omega t$

$\therefore a=-\omega^{2}A\cos\omega t$


$a_{max} \text{ is at amplitude}$
$a = 0 \text{ at equillibrium}$

still more shit to do

$x = A\cos\omega t \text{  and:  } a_{x} = -\omega^{2}A\cos\omega t$

$\therefore$
$a_{x}=-\omega^{2}x$ (f.b.)

so:
- Acceleration is directly proportional to the displacement
- Acceleration always acts in the opposite way to the displacement 

The two above are the requirements for SHM

#### Phase difference

The difference between two waves, measured in fraction of a cycle or in radians

$\phi = 2\pi \times \frac{\Delta t}{T}$

---
## SHM Displacement, Velocity & Acceleration

![[displacement time SHM.png]]


![[Velocity time SHM.png]]


![[acceleration time SHM.png]]


The above graphs showcase the relationship between displacement, velocity and acceleration for a system in SHM.

written down:
$\text{Velocity is } \frac{\pi}{2} \text{ radians out of phase with displacement}$ 

$\text{Acceleration is } \pi \text{ radians out of phase with displacement}$


**SHM oscillations are *isochronous*, meaning that the period doesn't depend on the amplitude of the motion**

basically no matter from where you start the pendulum swing, it will always take the same amount of time to complete a full swing

This is because as you increase the amplitude, you're allowing the pendulum to swing faster, making up for the lost time it needs to cover the distance

$v = \pm \omega \sqrt{ A^{2} -x^{2} }$ (f.b.)

---
## Energy with SHM


**Assuming no energy loss, the total energy $E_{T}$ in a SHM oscillation is fixed and is constantly transferred between potential $E_{p}$ and kinetic $E_{k}$ energy, so $E_{T} = E_{p} + E_{k}$**


graphically:
![[SHM energy.png]]

at amplitude, $E_{p}$ is max while $E_{k}$ is 0, and the inverse for equilibrium


---
## Damping and driving

**A damped oscillation is where a force (e.g. friction) acts in the opposite direction to velocity, dissipating energy as heat such that the amplitude decreases over time.**

Three types:
- Light damping: small dissipative force such as air, the amplitude changes by a small amount each cycle while leaving the period almost unchanged
  
- Heavy damping: stronger force such as water, the amplitude decreases significantly and the period increases slightly
  
- Very heavy damping: large force such as oil causes the amplitude to slowly move towards equilibrium with no oscillation


![[images pasted in/Damping.png]]

light damping (red), heavy damping (purple) and very heavy damping (green)
plotted graphically


**A forced oscillation is one that undergoes a periodic force at regular intervals**

to get maximum mileage out of this force, you should apply it when there is no acceleration from any other source, meaning when the velocity is at max

**The natural or resonant frequency is the frequency a system oscillates at with no periodic force**

**Resonance is where the maximum amplitude of a forced oscillation is achieved, with the periodic force $\frac{\pi}{2}$ radians out of phase with the displacement and its frequency equal to the resonant frequency of the system**

---
## Resonance

formula given for natural time period:

$T=2\pi \sqrt{ \frac{m}{k} }$

to get the natural frequency, take 1 over the result according to

$f=\frac{1}{T}$


**For no damping and light damping, the maximum amplitude occurs at the natural frequency**

**As the damping increases:
- The amplitude at every frequency decreases
- The maximum amplitude occurs at a lower frequency
- the peak becomes broader and flatter

