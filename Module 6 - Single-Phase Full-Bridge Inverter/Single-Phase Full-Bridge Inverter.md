# Controlled Rectifier
## Introduction
A DC-DC converter is an electronic device characterized by its ability to alter the voltage of direct current (DC) between different values. This is valuable in many situations, as often different elements within a single electronic device require various voltage levels to operate correctly. Thus, converters have the ability to increase, reduce, or reverse the voltage as required. Unlike an AC-DC converter, which transforms alternating current (AC) from the electrical grid into direct current (DC), the DC-DC converter works exclusively with direct current, modifying its voltage as necessary. DC-DC converters are composed of inductors, capacitors, diodes, and transistors, along with pulse width modulation techniques to achieve efficient energy conversion. In this way, they operate as follows: the duty cycle of the input signal is modulated, and the converter regulates the ratio between the time it is activated and deactivated, allowing the desired output to be controlled [1]. 

## Operation and applications
DC-DC converters are composed of inductors, capacitors, diodes, and transistors, along with pulse width modulation techniques to achieve efficient energy conversion. In this way, they operate as follows: the duty cycle of the input signal is modulated, and the converter regulates the ratio between the time it is activated and deactivated, allowing the desired output to be controlled. It is widely used in power electronics, the renewable energy sector, communication systems, and the automotive industry. [1].


### Configurations
There are several DC-DC configurations, which we will present below.

### Boost with a pure resistive load (R)

* Circuit: DC source + inductor in series → switch and diode → resistive load with capacitor.

* Operation:

ON: The inductor charges from the source, while the load is powered by the capacitor.

OFF: The inductor discharges its energy into the load, adding it to the source, increasing the output voltage.

* Result: The voltage across the load resistor is higher than that of the source.

* Specific feature: Since there is only R, the output current has greater ripple, smoothed by the capacitor.

IMAGENNNN DE ESTO 

Figure 1. Common emitter configuration

In this connection, the emitter is located as the reference terminal (usually grounded), while the input signal is applied to the base and the output is obtained at the collector. Its importance lies in that it allows for a high current gain and efficient operation in switching mode (saturation and cutoff), making it ideal for controlling high power loads such as transformers, motors, or DC-DC converters.
The common emitter configuration is the most used in BJT power transistors because it offers high current and power gain, in addition to allowing efficient control of switching between cutoff and saturation states. In applications such as switched-mode power supplies, inverters, and switching power amplifiers, the transistor is not used as a linear amplifier, but as a switch.




* Common base configuration

![Base comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Base%20comun.png)

Figure 2. Common base configuration

In the common base configuration, the base is connected as a reference for both the input and output signals. The input is applied between the emitter and the base, and the output is obtained between the collector and the base. In this configuration, the collector current is almost directly determined by the emitter current, and the current gain is low. However, the main advantage of this configuration is that it offers greater bandwidth and better performance at high frequencies, compared to the common emitter configuration.





* Common collector configuration

![Colector comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Colector%20comun.png)

Figure 3. Common collector configuration

In this configuration, the collector is the common terminal for both the input and the output. The input signal is applied between the base and the collector, and the output is obtained between the emitter and the collector. Due to this arrangement, the output signal is in phase with the input and has a voltage gain close to one (≈1), but with a high current gain.


## MOSFET Power Transistors
The power MOSFET (Metal-Oxide-Semiconductor Field-Effect Transistor) is a voltage-controlled device widely used in power electronics due to its high efficiency and switching speed. Its structure allows large currents to be controlled by a small gate signal, thanks to its high input impedance. One of its main advantages over BJT transistors is that it has high input impedance, allowing the MOSFET to be activated with low-power control circuits, significantly reducing the losses associated with actuation. In terms of applications, are used in power supplies, motor controllers, renewable energy systems and electric vehicles [2].

### Configurations
There are three main connection configurations for power MOSFETs:

* Common source configuration

![Fuente comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/f1cb55f43e9815c0adcb6338a8c188f68d6ed38b/Module%202%20-%20Power%20Transistors%20(BJT%2C%20MOSFET%2C%20and%20IGBT)/Images/Configurations/Fuente%20comun.png)

Figure 4. Common source configuration

The common source configuration in a MOSFET is an amplifier circuit where the input signal is applied to the gate, the output is obtained from the drain, and the source is connected to ground (for an N-channel MOSFET) or to a positive voltage (for a P-channel MOSFET). This configuration is the most common because offers high voltage and current gain.

* Common gate configuration

![Puerta comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/f1cb55f43e9815c0adcb6338a8c188f68d6ed38b/Module%202%20-%20Power%20Transistors%20(BJT%2C%20MOSFET%2C%20and%20IGBT)/Images/Configurations/Puerta%20comun.png)

Figure 5. Common gate configuration

In this configuration the input signal is applied to the source terminal and the output is taken from the drain terminal, while the gate is maintained at a constant bias voltage. This configuration is characterized by low input impedance, high output impedance, and moderate voltage gain where the input and output are in phase.

* Common drain configuration

![Drenador comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/f1cb55f43e9815c0adcb6338a8c188f68d6ed38b/Module%202%20-%20Power%20Transistors%20(BJT%2C%20MOSFET%2C%20and%20IGBT)/Images/Configurations/Drenador%20comun.png)

Figure 6. Common drain configuration

This configuration is characterized by having the drain terminal connected to AC ground and the input signal applied to the gate, while the output is taken from the source terminal. This configuration is ideal for buffer applications due to its high input impedance, low output impedance, and a voltage gain close to one, with the input and output signals in phase.




![Summary MOSFETs](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/9741f9f0d73775b83719362ce6b21a376ee51530/Module%202%20-%20Power%20Transistors%20(BJT%2C%20MOSFET%2C%20and%20IGBT)/Images/Configurations/Summary%20MOSFETs.png)

Table 1.  Summary of MOSFET Amplifier Characteristics [3]










## IGBT power transistors.

The IGBT (Insulated Gate Bipolar Transistor) is a hybrid power semiconductor device that combines the characteristics of MOSFETs and BJTs. It has an insulated gate controlled by voltage, which means low control power consumption, and a bipolar conduction region, which allows it to handle high currents and voltages with low voltage drop in the on state. Due to these properties, the IGBT is widely used in inverters, frequency converters, electric traction systems, and renewable energy, being one of the most common power devices in medium and high voltage applications.

### Key features

* Voltage controlled: does not require significant DC current in the gate, only pulses for charging and discharging capacitances.

* High current capacity: can handle from tens to hundreds of amps.

* Low voltage drop in conduction: similar to a BJT (typically 1.5 to 3 V).

* Average switching speed: faster than a BJT, but slower than a MOSFET due to the “tail current” phenomenon (tail current when turning off).

* Use in medium and high voltage (600 V – 6.5 kV): much more efficient than MOSFET in this range.



## Configurations

Depending on their structure and technology, IGBTs are classified as follows:

### First-generation IGBTs (NPT - Non Punch Through)

* Symmetrical construction.

* They withstand voltage in both directions (forward and reverse blocking).

* More thermally robust.

* Used in traction and very high power applications.

### Second-generation IGBTs (PT - Punch Through)

* Add a “buffer” layer that reduces voltage drop and improves speed.

* Only block voltage in one direction.

* Have lower conduction losses.

* More common than NPTs in industrial applications.

### Trench IGBT (Trench Gate IGBT)

* More modern technology.

* Uses trench gates to increase current density and reduce losses.

* Much more efficient at medium frequencies (inverters, drives).

* Very common in industry today.

### Field Stop IGBT (FS-IGBT)

* Improved version of the PT, incorporates a field stop layer.

* Further reduces switching and conduction losses.

* Currently the most widely used in modern converters.




## Bibliography
[1] Distron, “Convertidor DC-DC: qué es y cómo se aplica”, Distron, 08-jun-2023. [En línea]. Disponible en: https://distron.es/convertidor-dc-dc-funcionamiento-aplicaciones/.

[2] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.

[3] – MOSFET AMPLIFIER CONFIGURATIONS y I. Impedance, “Department of electrical and computer engineering”, Charlotte.edu. [En línea]. Disponible en: https://ece.charlotte.edu/wp-content/upl
