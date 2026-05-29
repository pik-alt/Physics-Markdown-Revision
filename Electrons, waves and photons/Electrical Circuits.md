## Kirchoff's Laws

1st law: **For any point in an electrical circuit, the sum of currents into that point is equal to the sum of currents out of that point**

see: [[Charge and current#Kirchoff's 1'st law|Kirchoff's 1st Law]]

2nd law: **In any circuit, the sum of the electromotive forces is equal to the sum of p.d. around a closed loop**

written fancy: $\Sigma \varepsilon = \Sigma V$

A "closed loop" is one possible path for current, you can think of it as a single series circuit within a parallel circuit

![[K2L loops.png]]

series circuits only have one loop and the current is the same in every position, therefore the emf is equal to the total p.d.

Each loop has the same potential difference which is the same as the EMF of the whole thing

![[crude emf thing k2l.png]]

here's a (admittedly crude) sketch of this

the sum of the p.d.s on the bottom branch is 2, which is the same as the top branch which is also the same as the whole emf.

The p.d. across resistors in parallel is always the same.


![[k2l series loop.png]]

Here's another example:
$\epsilon = V_{\text{branch}} + V_{\text{series}}$

$2 = V_{\text{branch}} + 1$

$V_{\text{branch}} = 1$

## Combining Resistors

In series: $R_{T} = R_{1} + R_{2} \dots$ (f.b.)

In parallel: $\frac{1}{R_{T}} = \frac{1}{R_{1}} + \frac{1}{R_{2}} \dots$ (f.b.)

## Analysing circuits 

There's nothing really "taught" this lesson.

Pro tip though I guess: If you have two resistors (or whatever) in parallel when it'd be more convenient to have them in series, find the total resistance of them both and treat them both as one resistor in series.

![[complex resistor.png]]

$\frac{1}{100} + \frac{1}{100} = \frac{2}{100}$

$R_{T} = \frac{100}{2} = 50\Omega$

Therefore it's equivalent to this:

![[Simple resistor.png]]

Much better!

## Internal resistance

**Power sources have an internal resistance r which causes a loss of energy and volts**

**The terminal p.d. V is the potential difference across a power supply**
basically the p.d. that actually reaches the components

$\epsilon = V + Ir$ (f.b.)

where $Ir$ is the "lost volts"

$\epsilon = IR + Ir$

$\therefore \epsilon = I(R + r)$ (f.b.)


![[Internal resistance.png]]

It is commonly represented with a resistor "within" the cell or battery

$I_{\text{max}} = \frac{\epsilon}{r}$
(I've never seen this mentioned again but its on the powerpoint ¯\\_(ツ)_/¯)


If there's no current flowing through the circuit, the terminal p.d. is equal to the emf, meaning that there's no internal resistance


## Potential divider

**A potential divider is two or more resistors in series connected to a source of potential difference which is divided between the resistors**

![[Meet potential divider!.png]]


Derivation if you're curious:

$I = \frac{\varepsilon}{R_{T}}$

$I= \frac{\varepsilon}{R_{1} + R_{2}}$

(1) $V_{1}=IR_{1} = \frac{\varepsilon R_{1}}{R_{1} + R_{2}}$

(2) $V_{2} = IR_{2} = \frac{\varepsilon R_{2}}{R_{1} + R_{2}}$

Dividing (1) by (2):

$\frac{V_{1}}{V_{2}} = \frac{R_{1}}{R_{2}}$ (f.b.)


You can also think of this as the resistors sharing the p.d. proportional to the ratio of their resistances.

if $R_{1} = 2R_{2}$, $V_{1} = 2V_{2}$, so $V_{1} = \frac{2}{3}\varepsilon$

So the Output is the proportion of the total resistance the output resistor takes up:

$V_{\text{out}} = \frac{R_{1}}{R_{1}+R_{2}}V_{\text{in}}$ (f.b.)

## Sensing circuits

Potential dividers are used for sensing circuits, where physics changes cause the resistance of one of the components to change and therefore the p.d. across it such as temperature sensors or light sensors










