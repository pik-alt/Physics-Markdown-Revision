## Circuit symbols

 
Here are all the circuit symbols that you need to know (as well as a capacitor which isn't included in this diagram)

You also need to know how to place them in a circuit:
Ammeters go in series and should ideally have 0 resistance
Voltmeters go in parallel and should ideally have $\infty$ resistance
Diodes and LEDs only allow current to flow through them in one direction

![[Circuit sumbols.png]]


## Potential difference and electromotive force

**Potential difference V is the work done W per unit charge by moving charge Q passing between two points, which is transferred to other forms**

$V=\frac{W}{Q} \therefore W=VQ$ (f.b.)

**Electromotive force (EMF) $\epsilon$ is the work done per unit charge *on* the charge carriers by a cell, battery or power supply**

Potential difference is work done **by** the charge carriers
EMF is work done **on** the charge carriers

$W=\epsilon Q$ (f.b.)

## Electron guns

![[Electron gun.png]]

An electron gun produces a narrow beam of electrons which can be used to ionise particles or for certain scientific instruments like electron microscopes.
It's also the same technology that CRT TVs used.

The hot filament releases electrons via **thermionic emission**

The electrons are accelerated by the p.d. shown.

This whole thing has to take place in a vacuum to ensure the electrons don't bump into anything.

The kinetic energy of the electrons is equal to the work done by the p.d.

$W=VQ = \frac{1}{2}mv^{2}$

## Resistance

**Resistance R is a measure of how difficult it is for current to flow through a component in a circuit**

caused in wires by the collisions of free electrons with positive ions and defects

**Ohm's law states that for a wire with a constant temperature, the current in the wire is directly proportional to the p.d. across it**

$V=IR$ (not in f.b. surprisingly)


![[IV ideal.png|436]]

This is however for an ideal ohmic conductor.

![[bulb IV.png]]

The IV graph for a bulb looks like this. It's not proportional because, as current flows through, the bulb heats up, which increases the resistance which decreases the current. This eventually reaches an equilibrium which is why the curve goes flat.

N.B. because we use IV graphs, where the equation is $I=\frac{1}{R}V$, the gradient is the reciprocal of the resistance, not the resistance itself

## I-V Characteristics

**Ohmic conductors have a straight line through the origin, $I \propto V$ so resistance is constant**

You need to know how to set up a test to measure this

![[IV practical.png]]

the setup looks something like this

## Diodes

Diodes only allow current to flow through them in one direction

LEDs are efficient light sources as they transfer electrical energy directly into light rather than indirectly through heat.
They also don't get hot.

LEDs emit light photons with a specific energy and therefore wavelength, given by $E=\frac{hc}{\lambda}$ (see quantum physics)

**Current flows \[through a diode] when a potential difference above the threshold voltage is applied across the diode in the forward direction**

The threshold voltage is usually something like 5V

![[Diode IV.png]]

As you can see, below the threshold voltage, no current flows through and current will never flow through with a negative voltage.


## Resistivity

Resistivity is the property of a material that determines the resistance of a sample with any given size and shape

 $R = \frac{\rho L}{A}$ (f.b.) $\therefore$  $\rho$ = $\frac{R A}{L}$ 

$\rho \text{ units are: } \Omega m$

Resistivity is an inherent property of the material


## Thermistors

A thermistor is made from a semi conductor, which has a lower number density (see [[Charge and current#Mean drift Velocity|Mean drift velocity]]) than metals but higher than insulators.

In semi conductors, number density increases with temperature, so the hotter a thermistor gets, the better a conductor and thus worse resistor it is.


**The resistivity of a semi conductor and therefore thermistors decreases with temperature. This is known as a negative temperature coefficient (NTC)**

Increasing current through a thermistor increases the temperature and therefore decreases the resistance
therefore it is **non ohmic**

![[Thermistor IV.png]]


## LDR

A light dependent resistor (LDR) is made from a special semi-conductor where the electron density increases with exposure to light.

**The resistivity of a LDR semiconductor decreases with exposure to light**

use cases include street lights and sports light meters

You need to know how to set up an experiment to find the change in resistance using a light.

![[LDR practical.png]]

changing the resistance on the variable resistor changes the power input to the bulb, which is plotted against the log of resistance (due to how quickly the values change)

## Electrical energy and power

**Electrical power is the rate of energy transfer by each electrical component**

$P=\frac{W}{t}, W=VQ$
$\therefore P=V \frac{Q}{t}$

$\frac{Q}{t} = I$

$\therefore P=IV$ (f.b.)

you can combine this with $V=IR$ to get:

$P=I^{2}R$ (f.b.)

and

$P=\frac{V^{2}}{R}$ (f.b.)

## Paying for electricity

1 Joule is a tiny amount of energy compared to regular everyday energy usage.
Therefore we use kilowatt-hours (kWh) which is the amount of energy used by an appliance with a power input of 1kW for 1 hour which is stupid and dumb and I hate it just uses MJ its like measuring distance in "miles per hour minutes".

$P \times t = E$
$1,000 \times 60 \times 60 = 3.6 \text{MJ}$

