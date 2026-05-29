# Part 1: Particle physics

## Alpha scattering experiment

1904 - plum pudding model: electrons are evenly distributed in a positive mass - J.J. Thompson

1911 - Rutherford discovers the nucleus

Experimental conditions for alpha scattering experiment:
- Vacuum, to avoid $\alpha$ particles being absorbed by air
- Thin foil: to prevent all the $\alpha$ particles being absorbed by the metal
- Same speed: As slower $\alpha$ particles will be deflected more
- Narrow beam: So only back scattered when colliding head on with metal

$\alpha$ particles are fired at a at a thin sheet of gold leaf, most of the particles went through, but some deflected off, suggesting a massive nucleus that's positively charged.

The closer the $\alpha$ particles get to the nucleus, the more they're deflected via the repulsive [[Electric fields#Coulomb's law|Coulomb force]].

Key findings: 
- **The majority of the atom is empty space with most of the mass in the nucleus**
- **The nucleus has a positive charge**


If an $\alpha$ particle is fired head on to a nucleus, then the nucleus does work transferring the particles kinetic energy into potential energy, bringing it to rest at the minimum closest approach radius $r_{min}$

You can use this to find the radius of an atom:
$\text{ work done on the } \alpha \text{ particles is } QV \text{ where V = } \frac{1}{4\pi\varepsilon_{0}} \times \frac{Q}{r}$ (see: [[Electric fields#Electric potential|Electric potential]])

## The nucleus

**An element is defined the the number of protons in the nucleus (Z)**

**Isotopes are atoms with the same number of protons but different numbers of neutrons**

$X^{A}_{Z}$ <- isotope notation

A = Nucleon number (protons + neutrons) (aka atomic mass)
Z = Proton number

Number of neutrons = $A-Z$


**Unified atomic mass unit = 1u = $1.661\times {10}^{-27}Kg$** (f.b.)

**Mass of atom or nucleus (Kg) = Atomic Mass A x u**

#### Strong Nuclear Force

This keeps nucleus' from exploding outwards due to their electromagnetic repulsion

- Acts between all nucleons
- Can be repulsive or attractive
- A very strong force within a short range (~3fm)
![[Strong force.png]]

Depending on the distance, it can be either attractive or repulsive

Repulsive below 0.5fm to stop protons collapsing into each other

Attractive between 0.5 and 3fm to beat out the electrostatic force of repulsion


Number of nucleons in the nucleus can be approximated by:

$A = \frac{\text{ Volume of the nucleus}}{\text{ Volume of a nucleon}}$

$A = \frac{\frac{4}{3}\pi R^{3}}{\frac{4}{3}\pi R_{0}^{3}}$

therefore:

$\text{ Radius of nucleus = }R = r_{0}A^{1/3}$ (f.b.)
$r_{0} = \text{ radius of a nucleon}$

You can find $r_{0}$ by either:
- plotting a graph of R against $A^{1/3}$ and getting the gradient

or
- Plotting $\ln(R)$ against $\ln(A)$ and looking at the y intercept

derivation for the second option

$\frac{R}{R_{0}} = A^{1/3}$

$\ln\left( \frac{R}{R_{0}} \right) = \frac{1}{3}\ln(A)$

$\ln(R) - \ln(R_{0}) = \frac{1}{3} \ln(A)$

$\ln(R) = \frac{1}{3}\ln(A) + \ln(R_{0})$


## Antiparticles, hadrons & leptons



| Fundamental force | effect                                    | relative strength | range        |
| ----------------- | ----------------------------------------- | ----------------- | ------------ |
| Strong nuclear    | Experienced by nucleons                   | 1                 | ~$10^{-15}m$ |
| EM                | Static and moving<br> charged parcticles  | $10^{-3}$         | $\infty$     |
| Weak nuclear      | Responsible for beta decay                | $10^{-6}$         | ~$10^{-18}m$ |
| Gravitational     | Experienced by all particles<br>with mass | $10^{-40}$        | $\infty$     |


**Antimatter is matter composed of anti-particles that have the same mass as ordinary particles but the opposite charge.**


| Name       | Symbol    | Charge (C)              | Mass (Kg)               |
| ---------- | --------- | ----------------------- | ----------------------- |
| proton     | $p$       | $1.6\times {10}^{-19}$  | $1.67\times {10}^{-27}$ |
| antiproton | $\bar{p}$ | $-1.6\times {10}^{-19}$ | $1.67\times {10}^{-27}$ |


**Annihilation is where a particle and its corresponding antiparticle meet, and all their mass is converted into a pair of photons**

it's a pair to conserve momentum


![[Matter zoo.png]]

Here is how we categorise all particles

**Hadrons: Made of quarks & anti-quarks, defined by being affected by the strong force**
**Leptons: Fundamental particles not affected by the strong force** (e.g. electron)

**Baryons: Made of 3 quarks or 3 anti-quarks** (e.g. proton)
**Mesons:  Made of a quark anti-quark pair** (e.g. pion)


## Quarks

You only need to know about 3 for OCR physics, even though there are actually 6


| Flavour | Symbol | Charge          |
| ------- | ------ | --------------- |
| Up      | u      | $+\frac{2}{3}e$ |
| Down    | d      | $-\frac{1}{3}e$ |
| Strange | s      | $-\frac{1}{3}e$ |
Anti-quarks, same as normal. Same mass, opposite charge


You need to know what quarks the baryons are made of

| Baryon    | Charge | Quark<br>composition    |
| --------- | ------ | ----------------------- |
| $p$       | $+e$   | $uud$                   |
| $\bar{p}$ | $-e$   | $\bar{u}\bar{u}\bar{d}$ |
| $n$       | 0      | $udd$                   |
| $\bar{n}$ | 0      | $\bar{u}\bar{d}\bar{d}$ |

## Beta decay

Nuclei become unstable when the strong force can no longer hold the nucleus together

![[Line of stability.png|400]]


Heavy Particles decay to get back into the line of stability


**Neutrinos:
	fundamental particles with 0 charge**
	**Have very low mass and very low interaction with matter**

The two you need to know:
**Electron neutrino $\nu_{e}$ and Electron antineutrino $\bar{\nu}_{e}$**

Both have charge and mass* of 0
\* not actually but just go with it

#### Alpha decay
**Where an unstable nucleus emits an alpha $\alpha$ particle (two protons and two neutrons)**

Parent nucleus --> Daughter nucleus + Alpha particle

$X^{A}_{Z} \to Y^{A-4}_{Z-2} + \alpha^{4}_{2}$


#### Beta minus decay
**Where an unstable nucleus has too many neutrons, so a neutron decays into a proton via the weak force and emits a $\beta^{-}$ particle and electron antineutrino**


$n^{1}_{0} \to p^{1}_{1} + \beta^{0}_{-1} + \bar{\nu_{e}}^{0}_{0}$

$\beta^{-}$ particles are just electrons

**Beta plus decay is where an unstable nucleus has too many protons, so a proton decays into a neutron via the weak force and emits a $\beta^{+}$ particle and electron neutrino**


$p^{1}_{1} \to n^{1}_{0} + \beta^{0}_{+1} + (\nu_{e})^{0}_{0}$

(the brackets around the neutrino are just so I can actually write it down, it's not there in the textbook)

way to remember which one does what: since in one of them you're creating positive charge (turning a neutron into a proton), in that same one you must also create negative charge (release an electron)
#### Gamma decay

The emission of gamma rays doesn't change the number of protons or neutrons, it just moves the nucleus from a higher to a lower energy state


In beta minus decay, an up quark turns into a down quark due to W- boson

In beta plus decay, a down quark turns into an up quark due to W+ boson


**For all these decay interactions and equations, Charge, Nucleon Number and Atomic Number are all conserved**



# Part 2: Radioactivity

## Radioactivity

**$\alpha, \beta \text{ and } \gamma$ radiation are known as ionising radiation as they can ionise atoms by removing their electrons, leaving positive ions**


![[geiger tube.png|505]]

We can detect radioactivity via a **Geiger-Muller tube (GM-tube)**

This works by having the incoming radiation ionise the air, which allows it to now carry current to the negative cathode which completes the circuit.
A signal is recorded as a count rate $s^{-1}$

the MICA window prevents dust

You can measure the penetration strength of different types of radiation by putting different materials between the radioactive source and the GM-tube. Make sure to measure a control of the background count and subtract that value from the measurements recorded.



Alpha decay:
 > Highly ionising
 > Mass ~ 4u
 > Short range in air (1-3cm)
 > Blocked by paper
 
Beta decay:
> Less ionising than $\alpha$
> Mass = $M_{e} = 9.11\times {10}^{-31}$Kg
> Longer range in air (~1m)
> Blocked by 1-3mm aluminium

Gamma decay:
> Least ionising
> 0 Mass as it's a photon\*
> Obeys the inverse square law
> Requires a few cm of lead to stop it

\* ignoring special relativity


Large doses of radiation can destroy cell membranes.
This leads to death.

Smaller doses can cause DNA damage.
This can lead to mutations, cancer, damage to sex cells and death.

Alpha is the most harmful when digested or absorbed through cuts as it's the most ionising, but from the outside it gets blocked by skin.
Gamma is the most harmful from the outside, as it can pass through skin though it's the least ionising.

## Nuclear decay equations

**When the nucleus of a radioactive isotope decays by $\alpha$ or $\beta$ emission, it changes (transmutes) into the nucleus of a different element**

The nucleus before is known as the parent nucleus, and the nucleus after is known as the daughter nucleus.

In all nuclear reactions: Nucleon number; Proton number and total energy must be conserved

Example:
$Ra^{226}_{88} \to Rn^{222}_{86} + He^{4}_{2}$

Radium is the parent nucleus and Radon is the daughter nucleus.

For Beta minus:

$X^{A}_{Z} \to Y^{A}_{Z+1} + \beta^{0}_{-1} + \bar{\nu_{e}}$

For Beta plus:

$X^{A}_{Z} \to Y^{A}_{Z-1} + \beta^{0}_{+1} + \nu_{e}$

No transmutation happens in gamma decay


## Half-life and activity

**The decay of an individual unstable nuclei is a random event which can't be predicted precisely**

**The number of decays per second is proportional to the number of unstable nuclei N**
**The number of unstable nuclei N decreases exponentially with time**

An example is like popping popcorn, lots of pops at the beginning that gradually slow down as they pop

If we start with $N_{0}$ nuclei and in time period $\Delta t$ seconds $\Delta N$ decay, that leaves
$N=N_{0}-\Delta N$

**$\lambda$ is the decay constant, for the specific isotope, the fraction that decays per unit time, units $s^{-1}$**

$\frac{\Delta N}{\Delta t} = -\lambda N$ (f.b.)

**The half-life $t_{\frac{1}{2}}$ of an isotope is the average time it takes for half the number of active nuclei in the sample to decay**

The number $N$ of un-decayed nuclei halves every $t_{\frac{1}{2}}$



**The activity A of a radioactive isotope is the number of nuclei that decay per second. Units becquerel (Bq)**

Equivalent to the number of alpha and beta particles emitted per second 

$A=\lambda N$ (f.b.)


## Modelling Radioactive decay

There's an equation to plot the exponential decay:

$N=N_{0}e^{-\lambda t}$ (f.b.)

$t$ is the time that you're looking at


## Radioactive dating

**Carbon dating is a method to determine the age of organic material based on the ratio of unstable carbon-14 to stable carbon-12**


How $C^{14}$ gets into organic matter:
1. High speed protons from cosmic rays collide with atoms and produce neutrons
2. Nitrogen-14 nuclei capture these neutrons and decay into Carbon-14, which get captured in plants via photosynthesis
3. $C^{14}$ decays into $N^{14}$ via $\beta^{-1}$ emission, with a half-life of 5700 years

When the organic matter is alive, it keeps taking in C-14 at a constant rate, keeping the ratio of it to C-12 constant, at around $1.3\times {10}^{-12}$
Once it dies, it stops taking in C-14 and then it starts to decay to C-12

Limitations:
- Small samples can have count rates close to background, increasing the percentage uncertainty
- The method assumes constant atmospheric C-14 levels. Events such as volcano eruptions and burning fossil fuels can change C-14 levels.
- It's limited to around ten half-lived (~60,000 years)


Alright I weren't here for a lot of the radiation lessons and the powerpoints don't mention them but here's the rest of the radioactivity formulas:

$\lambda t_{\frac{1}{2}} = \ln(2)$ (f.b.)

$A=A_{0}e^{-\lambda t}$ (f.b.)

# Part 3: Nuclear Physics

## Mass-Energy equivalence

**Einstein showed that mass and energy are equivalent, meaning mass can be converted to energy, and vice versa, according to Einstein's equation $E=mc^{2}$** (in the f.b. but I don't think you'll need to check it for this equation)


When a positron meets an electron, they annihilate each other. All of the mass is converted to energy according to $E=mc^{2}$

**Pair production is where a high energy photon vanishes and produces a particle-antiparticle pair.**

![[Pair Production.png|357]]


They move in opposite directions to preserve momentum

**Mass increases with kinetic energy**
This also means a change in energy has a change in mass


$\Delta m = \frac{\Delta E}{c^{2}}$

**Mass changes are usually insignificant, except for nuclear reactions**

$\Delta m = \Sigma \text{ mass after} - \Sigma \text{ mass before}$

$\alpha$ decay:
$U^{238} M= 238.051u \to \alpha, M=4.002u + Th^{234}, M=234.044u$

$\Delta m = [238.051 - 234.044 - 4.002]u$
$\Delta m = 0.005u = 8.305\times {10}^{-30}Kg$


The change in mass is converted into the $E_{K}$ of the $\alpha$ particle = $4.67MeV$


## Binding Energy

**The binding energy of a nucleus is the minimum energy required to completely separate a nucleus into its constituent nucleons**

consider the work done to remove a nucleon.

Strong force must at least be equal to the repulsive [[Electric fields#Coulomb's law|Coulomb force]].

For two protons 1fm away, $F=230N$

we need to move 3fm away to break free of the strong force

$W  \approx 230 \times 2\times {10}^{-15} = 2.9MeV$

![[Separating nucleus.png]]

Work is done on the nucleus against the strong force to separate the nucleons

To combine the nucleons back, work is done by the strong force

The separated nucleons weigh more than the nucleons bound together (just go with it)
The mass defect between them $\Delta m$ is where the binding energy comes from


$\text{ Binding Energy} = \Delta mc^{2} = [\text{Total mass of nucleons - mass of the nucleons}]c^{2}$


Most of the time, we need to use the **Binding energy per nucleon**

$\frac{[\Delta mc^{2}]}{A}$
$A$ is the number of nucleons


**The stability of a nucleus increases with the binding energy per nucleon**

## Fission

**Nuclear fission is the process where a large nucleus splits into two smaller nuclei**
**Energy is released when the total binding energy increases** (just go with it)

Most of the energy released from fission (around 200MeV) is absorbed by the daughter nuclei as Kinetic Energy
**Induced fission is where a nucleus is bombarded with neutrons, causing it to split into two approximately equally massed nuclei and the release of energy (and also sometimes some neutrons)**

In a nuclear chain reaction, the emitted neutrons go on to induce further fission events

If each fission event releases N neutrons, after $n$ generations, there will be a total of $N^{n}$ neutrons released

![[Binding energy per nucleon diagram.png|592]]

The above shows a graph of the binding energy per nucleon against the atomic number.
Anything to the left of $Fe^{56}$ undergoes [[Nuclear and particle physics#Fusion|Fusion]] and anything to the right of it undergoes fission
#### Inside a nuclear reactor

**Fuel rods: Rods made of 2-3% $U^{235}$, produces heat end emits neutrons for induced fission chain reaction**

**Critical Mass: minimum amount of fissile material ($U^{235}$) required for a chain reaction**

**Moderator: slows down the neutrons through collisions so they can be re-absorbed by other nuclei. This also prevents the high energy neutrons from damaging the reactor**

**Control rods: Can be lowered to keep neutron abundance to one per fission by absorbing neutrons. They are dropped fully to stop fission and prevent everyone dying and exploding to death**

**Heat exchange: uses pressurised coolant (usually water) to remove heat from fission and produce steam that drives turbine generators to make electricity**

Safety Features:
- Thick steel reactor core: absorbs $\beta \text{ and } \nu$ and neutrons
- Thick concrete walls: on outer building to absorb rest of $\nu$ and neutrons
- Control rods for emergency shut-down
- Sealed fuel rods inserted and removed by remote handling to avoid radiation
- (before use) there's only $U^{235}$ & $U^{238}$ which only emit $\alpha$

Nuclear Waster:
- High level fresh waste is spent fuel cans, initially stored underwater to cool it off and provide shielding from the radiation
- After around a year, they're stored in deep underground containers



## Fusion

**Nuclear fusion is where two nuclei fuse together to form a single nucleus**

This requires a high speed collision to overcome the electrostatic repulsion of two nuclei.
They need to get to around 3 fm


**The energy released in fusion is equal to the total increase in the binding energy**

#### Proton cycle in stars:
1. $p^{1}_{1} + p^{1}_{1} \to H^{2}_{1} + \beta^{0}_{+1} + \nu$
   B.E. before = 0, After = $2 \times 1.1\text{MeV}$ (gotten from the diagram in the Fission section)
   Energy released = $2.2\text{MeV}$
   
2. $H^{2}_{1} + p^{1}_{1} \to \text{He}^{3}_{2}$
   Before = $2.2\text{MeV}$, after = $3 \times 2.6\text{ MeV} = 7.7\text{MeV}$
   Released = $+5.5\text{MeV}$
   
3. $\text{He}^{3}_{2} + \text{He}^{3}_{2} \to \text{He}^{4}_{2} + 2p^{1}_{1}$
   $\Delta \text{Binding energy} = 4 \times 7.0 - 2\times 7.7 = +12.9\text{MeV}$






