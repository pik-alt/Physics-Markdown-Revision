## X-rays

X-Rays are [[Waves 1|transverse EM waves]] with a short wavelength of $10^{-13} < \lambda < 10^{-8}$m 
Since they're so high energy, they can easily kill living cells.

![[Xray gun.png|577]]

The above device shows how X-rays are generated.
- The hot filament boils off electrons through thermionic emission
- The target anode accelerated the electrons. The kinetic energy of the electrons is equal to the work done accelerating them which is equal to $QV$
- The electron hits the metal target and loses a tiny bit of it's kinetic energy, which gets emitted out as an X-ray photon. The rest of the energy gets converted to heat

This whole process has to be done in a vacuum to stop electrons from ionising the air

**Each decelerated electron emits one photon with energy equal to the change in kinetic energy**

The highest possible energy (highest frequency or smallest wavelength) of the generated photon is if all of the electrons kinetic energy goes to generating the photon

$EK_{\text{max}} = eV = hf_{\text{max}} = \frac{hc}{\lambda_{\text{min}}}$

Advantages:
- Cheap and easy

Disadvantages:
- 2D image so can't differentiate between overlapping tissue
- Can't give precise location of observed features


Different materials absorb x-rays to different extents

**Attenuation describes the decrease of strength / intensity of EM radiation as it passes through matter**

Bones attenuate x-rays more than soft tissue


**A collimator is a device which narrows a beam of particles and rays, used in x-rays to produce a parallel beam**
You can think of it as "focusing" the x-rays

We do this to improve contrast & sharpness as well as to limit the radiation dose to other tissues

#### The 4 attenuation methods:
The different methods depend on the photon energy which depends on the $E_{k}$ of the electron that created it

1.  **Simple scatter: The photon hits an electron in the atom, but it doesn't have enough energy to be absorbed, so it scatters away and doesn't lose any energy**
   
It doesn't lose energy, but the intensity decreases as the photons are redirected elsewhere
applicable for low energy photons

2. **[[Quantum physics#The photoelectric effect|Photoelectric effect]]: The photon hits an electron, being absorbed and giving all it's energy to knocking it out of the atom. The gap left is filled by a different electron that releases a photon, although with less energy than the initial x-ray one.**

This is the most important one for hospitals

3. **Compton scattering: The photon strikes an electron, knocks it out but it doesn't lose all of it's energy, instead scattering  in a different direction**

4. **[[Nuclear and particle physics#Mass-Energy equivalence|Pair production]]: The photon interacts with the nucleus, "annihilating" to become a electron-positron pair**

This is the highest energy one and not really significant for hospitals. Significant above $10\text{MeV}$

Attenuation formula:

$I=I_{0}e^{-\mu x}$ (f.b.)

$I = \text{ Intensity at a point}$
$I_{0} = \text{ initial intensity before any absorption}$
$\mu = \text{ attenuation coefficient / absorption coefficient, units: }m^{-1}$
$x = \text{ thickness of the substance}$


Typical values for $\mu$:
- Vacuum: 0
- Flesh: 100
- Bone: 300
- Lead: 600

If you need to image soft tissues, you can use a contrast medium to make them more obvious during x-ray scans.
The two most common ones are **Iodine and Barium** (you need to remember this)

Iodine is most commonly used in fluids, e.g. to observe blood flow

Barium is often used to image the digestive systems, given in the form of a liquid mixture that's digested

## CAT scans

**CAT scans stand for: Computerised Axial Tomography**

[Wonderful video on the history of CAT scans](https://www.youtube.com/watch?v=9SUHgtREWQc&t=510s)

Modern cat scans work thus:
- patient lies on their back and are slid into a large vertical ring (gantry)
- The gantry houses an x-ray tube on one side and, opposite, an array of x-ray detectors
- The gantry spins around
- A fan shaped beam of x-rays is produced
- The beam irradiates a "slice" of the patient
- The x-ray intensity is detected and recorded to a computer which does a lot of maths to produce a final image

You get one entire 2D slice of a patient per $360\degree$ rotation

![[CAT scan diagram.png]]


Advantages:
- They can better distinguish between tissues of similar attenuation coefficients
- They create 3D images of the patient to help assess shape and size of disorders
- This is all done in a single process

Disadvantages:
- X-rays are harmful and this fires a lot of them
- Prolonged scans means a very high radiation dose, much more than a single x-ray scan
- You must remain still during it

## Gamma camera

Radioactive isotopes can be used for both diagnosis and therapy

Therapy: you can target tumours with gamma radiation from the outside or a radioactive source inside the patient

Diagnosis: Radioisotopes injected into the patients, creates a non-invasive method to see inside the body by detecting the concentration of that isotope from the outside. Allows you to see tissue function rather than just anatomy


We use gamma emitters for diagnosis as they have a short [[Nuclear and particle physics#Half-life and activity|half-life]], which means they have a high activity and don't stay in the body for longer than necessary

Often in use is Technetium-99m for monitoring the function of organs such as the heart, liver, lungs and brain (You need to know about TC-99m)

You may also need to combine the radioisotope with a tracer in order to target a specific tissue

![[Gamma camera.png|304]]
We can detect the radiation emitted by the isotopes via a gamma camera


Components of a gamma camera:
- **Collimator: allows only gamma photons moving directly into the detector to pass through, to produce a well-defined image. Made of lead to absorb any photons not travelling in the correct direction**
- **Scintillator: converts the gamma photons to light photons**
- **Photomultiplier tubes: Converts the photons to electrons via the [[Quantum physics#The photoelectric effect|photoelectric effect]] and multiples the number of them for signal amplification**
- **Circuit & computer: converts the electron signal to a voltage and an image**

In essence:
$\text{ Gamma } \to \text{ Visible light} \to \text{ Electrons} \to \text{ Voltage}$

In photomultiplier tubes, each incident electron collision releases 4 secondary electrons

![[Photomultiplier tubes.png]]



## PET scans

**PET stands for: Positron Emission tomography**

It's a nuclear medical procedure that can measure the metabolic activity of the cells of body tissues.

A beta-plus emitting radioactive tracer is used to stimulate position-electron [[Nuclear and particle physics#Antiparticles, hadrons & leptons||annihilation]] to produce gamma photons, which are then detected

The radioisotope most commonly used for this is **Fluorine-18**
It decays via $\beta^{+}$ to Oxygen-18 which a short half-life

The disadvantage of the short half half-life is that it must be made on site.


Most PET scans use **Fluorine-18** in the form of a glucose (sugar) called **FDG (fluorodeoxyglucose)**, known as a **radiopharmaceutical**

You need to know about FDG.

FDG accumulates in tissues with a high rate of respiration, such as cancer cells because the body thinks it's just normal glucose


You can also use Carbon-11 as a radioisotope for PET scans, which is used in the medical tracer in the form of actual Carbon Monoxide (yeah that one)


![[PET scan.png]]

How it works:
- the positron source releases a positron (shocker)
- this meets with an electron after travelling around 1mm
- they annihilate and produce a pair of gamma photons
- These gamma photons travel in opposite directions (to conserve momentum\*) and are detected at opposite detectors
- The time difference between the detections can be used to determine where this occurred in the body
- This is then given to a computer to do a fuck ton of maths and make an image out of it

\* photons have momentum even though they don't have mass just go with it


![[alzheimers pet scan.png]]

The PET scan on the left shows a normal healthy brain, while the one on the right shows one of a person suffering from Alzheimer's, note the greatly reduced activity


Advantages:
- Non-invasive
- Shows anatomical and metabolic information

Disadvantages:
- Expensive, short half life means that the Fl-18 needs to be made on site


## Ultrasound

**Ultrasound are [[Waves 1#Progressive waves|sound waves]] with a frequency above the human hearing range of 20kHz**

They are generated through a process known as the **Piezoelectric effect**

**Piezoelectric effect: The ability for an applied potential difference to cause a piezo-crystal to contract or expand, and vice versa**


![[Piezoelectric crystal.png|407]]


Ultrasound waves are created through **Ultrasound Transducers**

![[Ultrasound Transducer.png]]


When you apply an alternating p.d., the piezoelectric crystal rapidly contracts and expands to the same frequency as the voltage.
The crystal is cut to a certain size in order to induce resonance.

The damping material is there to stop the crystal from vibrating too much, creating clear distinct and sharp pulses.


The crystal both receives and emits ultrasound:
- When emitting, it converts the alternating p.d. into sound waves
- When receiving, it converts the sound waves into an alternating p.d.


#### A-scans
(A stands for amplitude)
Uses a single transducer to emit a signal and then later receives it back. It is one dimensional and used to determine the depth of something, such as a tumour.

They work by measuring the time delay between generating and receiving the signal and calculating the distance by using that along with the speed of sound in the media.

This does **NOT** produce an image.

![[A-scan.png|369]]




#### B-scan
(B stands for baby cause this is the one you use to look at unborn babies)

A B-scan is an ultrasound scan that's used to build up a two or three-dimensional image of an internal structure using multiple sensors or one sensor in different positions.

You move the transducer around, measuring the different return times to form a series of A-scans that are then combined to form an image.

They're used to create an image of internal structures for the purpose of diagnosis.

To get a clear image, you use pulses of ultrasound to prevent any interference that would occur with a continuous wave and you use a small wavelength so it can more easily diffract around finer details.

![[B-Scan.png]]


Ultrasound tells you about how deep a boundary is and the nature of it, as different materials will reflect different amounts of the ultrasound wave.


Advantages:
- Non-ionising
- Non-invasive
- Quick

No disadvantages (in the spec)


## Ultrasound Impedance

**Impedance: The acoustic impedance Z of a substance is defined as the product of the density $\rho$ of the substance and the speed c of ultrasound in that substance**

$Z=\rho c$ (f.b.)

For sound waves, impedance is a measure of the force required to create the initial volume change to the wave medium.


At boundaries, ultrasound waves are reflected or refracted.

If you emit an ultrasound wave of intensity $I_{0}$ and $I_{R}$ is the intensity of the reflected wave, then the intensity of the transmitted wave is $I_{0}-I_{R}$

$\frac{I_{R}}{I_{0}} = \frac{(Z_{2} - Z_{1})^{2}}{(Z_{2} + Z_{1})^{2}}$(f.b.)

$\frac{I_{R}}{I_{0}}$ is the **intensity reflection coefficient**


If you want 0 reflection, then you want $I_{R}$ to be 0, so then you need for $Z_{2} = Z_{1}$

We don't want any reflection on the patients skin when performing an ultrasound, so we use a **coupling gel** which has an impedance similar to that of skin tissue (this is called **impedance / acoustic matching**).
We use a gel so that there's no pockets of air and this prevents there being one massive reflection from the boundary between air and skin.


If we want 0 transmission, we want $I_{R} = I_{0}$, so the ratio should equal $\pm 1$.
For this, we need either $Z_{2} \gg Z_{1}$ or $Z_{1} \gg Z_{2}$


## Doppler imaging

Required reading: [[Astrophysics and Cosmology 2#Doppler effect|The Doppler effect]]

**Doppler ultrasound: reflection from the ultrasound is Doppler shifted which allows you to determine the speed of the thing you're measuring**

This is often used to measure blood flow.

If the blood is flowing towards the transducer, the reflected frequency is **increased**.
If the blood if flowing away from the transducer, the reflected frequency is **decreased**.

The frequency shift is determined by the speed of the blood cells, the angle of the transducer relative to the blood, the speed of the ultrasound in the blood and the initial frequency of the sound waves.


![[Doppler imaging.png]]


Transducer C won't detect any frequency shift as the blood is neither flowing towards or away from the transducer.

Transducer D won't detect any frequency shift as most of the ultrasound waves are rebounded by the vessel wall.

Only transducers A and B will detect any frequency shift.

$\Delta f = \frac{2f\cos\theta}{c}$(f.b.)

the 2 comes from the fact that the ultrasound Doppler effect is twice as great as the normal one for reasons which I don't understand

This technique is used to analyse blood flow through arteries and veins and can reveal blood clots, vessel walls narrowing and see the rate of blood flow for organs such as the kidney or liver.

