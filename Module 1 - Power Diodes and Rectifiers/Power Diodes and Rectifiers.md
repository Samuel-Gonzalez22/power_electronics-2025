# Characteristics of Power Diodes

Power diodes are semiconductors conditioned for high electrical demand condition application. If they can be compared to normal diodes, they have unique characteristics that make them suitable for switching and rectifying applications:

* High direct current: Ability to conduct currents from 10A to hundreds of amperes.

* High repetitive reverse voltage: Have reverse voltages in the range of 100V to over 1000V.

* Switching speed: A crucial aspect in high frequency application as inverters and switched sources.

* Good thermal robustness and good power dissipation: Some are placed on heatsinks or have special encapsulations to facilitate thermal management.

These characteristics make power diodes essential in environments where reliability, high efficiency and heat resistance are needed. [1]

# Types of Power Diodes: 

Power diodes are basically divided according to their recovery time and internal structure:

* General Purpose Diodes: Low cost, used in low-frequency applications such as power supplies. They have long recovery times (~25µs).

* Fast Recovery Diodes: Designed for fast switching applications (1–5µs). Used in dc-dc and ad-ac converter circuits.

* Schottky diodes: Use a metal-semiconductor junction; have very fast switching times and low forward voltage drops, ideal for switched-mode power supplies. [1]

# Freewheeling

In circuits with inductive loads, a freewheeling diode is used to:
* Provide an alternate path for current when the main switch is turned off.
* Prevent dangerous voltage spikes generated by inductance.
* Protect the switch and allow current to continue flowing for a controlled period of time.
The freewheeling diode is connected in parallel with the inductive load. [1]

# Diode rectifiers: single-phase (full wave) and three-phase

Rectifiers are basic circuits that convert alternating current into direct current through power diodes. Depending on the number of input phases, they are classified as follows.

* Single Phase Full Wave
Uses a center tap transformer (2 diodes) or a 4 diode bridge. Converts both half cycles of the AC wave into positive DC pulses. Used in domestic or laboratory power supplies.

* Three-phase: Uses 6 diodes (three positive and three negative) in a bridge config. Produces a more stable output with less ripple. Used extensively in industrial systems requiring large amounts of power. [1]

# Performance parameters: 

In order to evaluate the performance of a rectifier, the following technical parameters are taken into account:
* The average value of the output (load) voltage and current
* The output DC power
* The root-mean-square (RMS) value of the output voltage and current
* The output AC power
* The efficiency
* The effective (RMS) value of the AC component
* The form factor
* The ripple factor
* The transformer utilization factor (TUF)
* The power factor (PF)
* The crest factor (CF) [1]

# Design of a rectifier circuit

The design of a rectifier requires determining the diode ratings and the ratings of filter components at the input and output side. Average current, RMS current, peak current and peak inverse voltage. There are no standard procedures for the design, but it is required to determine the shapes of the diode currents and voltages. [1]

# References

[1] M. H. Rashid, Power electronics: Circuits, devices & applications, 4th ed. Upper Saddle River, NJ: Pearson, 2013.
