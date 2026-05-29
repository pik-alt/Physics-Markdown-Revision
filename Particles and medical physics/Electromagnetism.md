## Magnetic fields

**A magnetic field is a field surrounding a magnet or field-carrying conductor in which magnetic objects experience a force
Magnetic field lines are a visual representation of this
The field lines point from the North pole to the South pole
**

![[bar magnet.png|415]]

North = red
South = Blue

way to remember: if you're feeling Blue, you're feeling down (or south)

The lines point in the way that a North pole magnet would point at that position


If magnetic field lines are parallel and equally spaced out then they're considered to be **uniform**. This is the case for an MRI machine.

**Magnetic fields are created by moving charge**. The field produced is called a B-field.


#### Right hand grip rule:
- Hold out your right hand in a thumb's up position
- The way which your thumb is pointing is the direction of conventional current
- The way your fingers curl is the direction of the B-field

you can also do the method for a Solenoid:
- The way in which your fingers curl is the direction of the current
- The way which your thumb is pointing is the North of the field


Unlike poles attract. The field lines connect.
Like poles repel. The field lines push away and don't connect.


## Force on a current carrying wire

A solenoid is a coil of wire carrying current that creates a magnetic field.

**The motor effect states that a wire which carries a current at a non-zero angle to magnetic field lines experiences a force**

**The force is proportional to the current $I$, the length of the wire in the field $l$ and the magnetic flux density $B$**

 $F = BIl\sin\theta$ (f.b.)

$\theta$ is the angle between the field and the current


**Magnetic flux density $B$, is the force per unit length per current on a current carrying wire. Units Tesla $T$**

**Fleming's left hand rule:
**

![[flemings left hand rule.png|376]]


The way I remember the fingers is that, starting from your thumb onward, they go FBI:
F - Force
B - Magnetic field
I - Current

## Charged particles in a magnetic field

In an [[Energy, Power and Resistance#Electron guns|Electron gun]], The work done by the anode is $QV=W = \frac{1}{2}mv^{2}$

Force in a perpendicular magnetic field: $F=BIl$
sub in:
- $I=\frac{Q}{t}$
- $l=vt$

and you get: $F=BQv$ (f.b.)

**The force on charges particles moving at right-angles to a magnetic field is proportional to its velocity, charge and the magnetic flux density**

You often get asked about particles moving in spirals due to magnetic fields, that's because the resultant force is changing the particles direction, which changes the direction of the current which, again, changes the resultant force.
Force is always perpendicular to the direction of travel, just like centripetal force.


$BQv = \frac{mv^{2}}{r}$

## Electromagnetic Induction

**Electromagnetic induction is the production of an emf by:
i) moving a conductor through a magnetic field
or
ii) moving a magnetic field through a conductor**

Conditions:
- The wire must cut across the magnetic field lines. If they're parallel, no current
- The induced emf is 0 the instant the relative motions is stopped

You can increase induced emf by:
- moving the wire or field faster
- having a stronger magnetic field
- having more coils to cut through the field lines

**Faraday's Law: induced emf in a circuit is equal to the rate of change of flux linkage through a circuit**

Remember that only the perpendicular component of the field produces the force that induces emf;

**Magnetic flux $\phi$ is the total magnetic field through an area perpendicular to the field direction. Units Weber (Wb)**

$\phi = BA$
$B = \text{ Magnetic flux density}$
$A = \text{ Area}$

The flux linkage is the product of magnetic flux and the number of turns crossing the field at right angles.

$E=\frac{\Delta(N\phi)}{\Delta t}$ (f.b.)

$N = \text{ Number of coil turns}$


If the coil is perpendicular to the field, then a current is induced. If it's parallel, then no current is induced, so, in general:

$\phi = BA\cos\theta$

$\theta$ is the angle between the normal line of the coil and the field:

![[Faraday coil theta.png]]



## Faraday's and Lenz's laws

**The energy transferred to the wire in the form of current is equal to the work done against the magnetic force**

**The rate of energy transfer = induced emf x current**


**Lenz's law states that the direction of the induced current is always such as to oppose the change that causes the current**

It's the "no you don't" law. If you want to move a conductor through a field in a direction, Lenz's law says "no you don't" and pushes it in the opposite direction, making you have to do work.


**The current will create a magnetic field that you're forced to do work against**


#### A.C. generator
Reverse of a motor, a generator is where coils are turning to induce a current. You need slip rings to do this to constantly shift the direction of current to keep it spinning in the same direction

Lenz's law is why the current reverses on every cycle in a generator, it always needs to oppose the direction of motion of the force that created it

Here's a long derivation that I don't really wanna write about so I'd just suggest looking at the powerpoint and remembering that e.m.f. is the rate of change of flux linkage, so even if there's very little magnetic flux, if it's changing quickly then the e.m.f. is large

$\varepsilon = BAN\omega \sin(\omega t)$ (not in f.b.)

## Transformers

#### Back EMF of motors
A spinning coil in a motor induces an emf since it's in a magnetic field which, due to Lenz's law, opposes the applied current.

This is called back-emf $\varepsilon_{back}$ and reduces the total pd and hence the current:

$IR = V_{applied} - \varepsilon_{back}$

![[Electric motor.png]]


#### Eddy currents

Eddy currents are currents induced in metals due to a changing magnetic field
Applications include:
- magnetic induction breaking
- Induction cookers


#### Transformers for real this time

Power stations produce an induced emf of ~ 25kV, but in our homes we thankfully only get 325V.

**Transformers change an alternating p.d. to a different peak value via electromagnetic induction**

![[Transformer circuit symbol.png]]

above: The circuit symbol for a transformer


![[Transformer.png|456]]

above: a complicated diagram of a transformer

There are two coils wrapped around the same iron core, to concentrate the magnetic flux.

The primary (or input) coil has turns $N_{p}$ and is connected to an alternating pd $V_{p}$

The secondary (or output) coil has turns $N_{s}$ and gives the output voltage $V_{s}$

If there are more turns in the secondary coil than in the primary, then the output voltage is greater and so it is a **Step-up transformer**
likewise, if there are less turns in the secondary coil, then the output voltage is lesser and so it's a **Step-down transformer**

The formula is:
$\frac{N_{s}}{N_{p}} = \frac{V_{s}}{V_{p}}$ (f.b.)

 Derivation:
P.d. in input coil = $V_{p} = \frac{N_{p}\Delta \phi}{\Delta t}$
p.d. in output coil = $V_{s} = \frac{N_{s}\Delta \phi}{\Delta t}$

combining the both equations we get the above formula for a transformer


A major source of energy loss is induced eddy currents in the core, which reduce flux in the secondary coil.

To reduce eddy currents, the core is laminated, consisting of thin sheets of iron separated by layers of insulating material

Assuming a high efficiency, $P_{in} = P_{out} \therefore I_{s}V_{s} = I_{p}V_{p}$



Using transformers is a more efficient way to transport electrical power as power lost is equal to $I^{2}R$, so we want very high voltage and very low current in order to minimise power lost.