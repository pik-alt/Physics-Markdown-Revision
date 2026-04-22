# Part 1: Stars

**Stars are created in nebula, vast clouds of interstellar dust and gas, mainly hydrogen, brought together over millions of years by the tiny force of gravity**

**A protostar is a hot dense sphere of gas that will become a star**

We use units of light years to measure distance, which is the distance that light in a vacuum travels in a year, equal to $9.5\times {10}^{15}m$ (f.b.)


These are the steps for a star to form:

1. The nebula needs to become large enough to contract under it's own gravity
   
2. Clumps compact under gravity to form a spinning ball of Hydrogen, called a protostar
   
3. The number density of particles increases, increasing the pressure
   
4. The increased pressure causes more collisions, raising the temperature and $E_{k}$
   
5. at ~3000K, Hydrogen ionises, leaving positively charged Hydrogen nuclei plasma
   
6. at ~10MK Hydrogen overcomes its electromagnetic repulsion, allowing it to fuse and becoming a main sequence star

[[Nuclear Fusion]] occurs within the star, fusing hydrogen into helium which produces a radiation pressure from the emitted photons and a gas pressure from the nuclei themselves, both of which prevent the star from collapsing in on itself from it's own gravity

The star is at equilibrium once the outward pressure is equal to the gravitational pressure.


The more massive the star is, the greater the force of gravity trying to collapse it, so they need more pressure which means more fusion which means that they are brighter, reducing the star's lifespan as all the hydrogen runs out faster

The definition of a planet is:
- a body that orbits a star that
- has a large enough mass so that gravity forms it into a round shape and
- doesn't rely on nuclear fusion and
- has cleared its orbit (this is what knocked Pluto out)

There are other objects that you need to know, such as satellites which are things that orbit planets. The moon is Earths natural satellite.

## Star life cycle

Once all of a star's hydrogen in the core is depleted, it moves on from the main sequence and the next stage is dependent on it's mass.

To measure mass of stars, we use Solar mass $M_{\odot}$, which is $1.99\times {10}^{30}Kg$ (not given in f.b. but often times is stated in questions where it's needed)

### $\leq 10M_{\odot}$ 

Once the hydrogen in the core runs out, the radiation pressure reduces and the core contracts due to gravity and as a result heats up (see: [[Gas laws]]).
However, it's still not hot enough to fuse helium, meaning that it's innate.

There is still some hydrogen left in the "shell" of the star, however, which begins to fuse (shell hydrogen burning) which increases the outward pressure, causing the shell to expand and cool, forming a red giant.

The shell gradually leaves, leaving behind a white dwarf which are extremely dense.
**However this only happens below the critical mass, known as the Chandrasekhar limit of $1.44M_{\odot}$**

Red giants, although cooler, have more surface area and so are more luminous, moving up-right on a HR-diagram ([[Astrophysics and Cosmology 1#HR-diagram]]).

### $> 10M_{\odot}$

Stars with mass above 10 solar masses have much hotter cores, meaning that when the hydrogen runs out, they can start fusing helium in the core into carbon.
This cycle continues for a while until you get to iron, where fusion no longer produces energy.

At that point, the star is a red supergiant and is unstable, each of the fusion layers collapse and bounce off the core, leading to a supernova.
What remains is the remnant core.

Depending on the mass of the core, different things happen:

core $< 1.44M_{\odot}$ -  white dwarf

core $> 1.44M_{\odot}$ - neutron star

core $> 3M_{\odot}$ -  black hole


Black holes have a gravitational field so great that beyond a certain point, the Schwarzchild Radius, not even light can escape it

## HR-diagrams


![[hr diagram.png|422]]

You need to know this.

Temperature goes right to left (for some reason) and is on the x axis while luminosity is on the y axis.

The black line is the typical life cycle for a small star like our sun.

## Energy levels in atoms

Electrons bound to atoms can only have discrete energy levels (quantum behaviour)

![[hydrogen energy levels.png]]

Electrons cannot exist between energy levels.

Potential energy increases as you get further away from the nucleus, like on Earth when you go higher and higher up.

Electrons don't like to be excited (killjoys), so they de-excite (move down an energy level)
and release a photon corresponding to the energy difference between the levels.

## Emission Spectra

**Emission spectra is the range of wavelengths produced by a light source**

we can look at any particular star's emission spectra and determine what it's made of.

There are two types:
- Continuous spectrum: contains all the wavelengths or colours emitted with no gaps
  
- Line spectra: contains discrete wavelengths or colours with gaps

also two types of line spectra!

- Emission lines, produced by the de-excitation of electrons to lower energy levels
  ![[Emission lines.png]]
  
- Absorption lines, produced as a continuous spectra, where ambient photons get absorbed by electrons to higher energy levels, then as they de-excite they move in a random direction, showing up as a black line
  ![[Absorption lines.png]]

In stars, we see absorption spectra, as the core releases a continuous spectrum and certain frequencies of light are "caught" in the outer layer, that they get de-excited and those photons get scattered.

## Analysing starlight

Required reading [[Young's double slits]]

**Diffraction gratings contain many evenly spaced slits that produce bright and dark fringes which are *sharper* than from double slits**

The central bright fringe has order 0
then the bright fringes either side have order 1 and so on

The formula to find the maxima or bright fringes, you use:
$d\sin\theta=n\lambda$

$d = \text{distance between slits}$
$\lambda = \text{wavelength}$
$n = \text{order peak}$
$\theta = \text{angle between bright fringe and central beam}$

diffraction gratings are usually given by their "lines per millimetre"

So if a grating has 300 lines per mm, that means that the distance between lines is $\frac{1}{300}$mm, which you then convert to metres to find $d$

We can send starlight through a diffraction grating and the different components get split up according to $d\sin\theta = n\lambda$, which reveals the spectras.

## Blackbody radiation

**A black-body is an idealised object that absorbs all the electromagnetic radiation incident on it and at a specific temperature in thermal equilibrium emits a characteristic distribution of wavelengths**

in essence, it absorbs all em-radiation and emits all wavelengths of em-radiation.

![[blackbody chart.png]]

This chart shows how, at different temperature, the intensity of each wavelength of light varies. As you get hotter, the peak moves more to the left, or shorter wavelength as well as higher up.

**Wien's displacement law states that the wavelength $\lambda_{\text{max}}$ at which the intensity of a black-body is maximum is inversely proportional to the temperature (in kelvin)**
remember its always kelvin

written out:
$\lambda_{\text{max}} \propto \frac{1}{T}$ (f.b.)

The true relationship is: $\lambda_{\text{max}}T = 2.9\times {10}^{-3}mK$ (that's metres kelvin)

**Stefan's law states that the total power radiated per unit surface area of a black body (luminosity) is directly proportional to the fourth power of its absolute temperature**

$L=4\pi r^{2}\sigma T^{4}$ (f.b.)

$L = \text{Luminosity (W)}$
$\sigma = \text{Stefan's constant = }5.67\times {10}^{-8}Wm^{-2}K^{-4}$ (f.b.)
$r = \text{star radius (m)}$
$T = \text{surface temperature (K)}$


continued in [[Astrophysics and Cosmology 2]] cause this is a long ass topic