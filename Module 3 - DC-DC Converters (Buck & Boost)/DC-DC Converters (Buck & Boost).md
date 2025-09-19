# Power Transistors (BJT, MOSFET and IGBT)
## Introduction
A power transistor is a semiconductor device specifically designed to handle high levels of current and voltage while maintaining the ability to switch controlled at high speed. Unlike small-signal transistors, which are optimized to amplify low-level signals, power transistors are built and designed to support and control significant flows of electrical energy. The fundamental distinguishing feature of power transistors is their ability to operate as electronically controlled switches. This means they can quickly toggle between their on and off states, blocking the flow of current by presenting high impedance.

## Theoretical Framework
## BJT Power Transistors
A BJT power transistor is a bipolar junction semiconductor device designed to operate in applications where control and handling of high levels of current and voltage are required. Its principle of operation is based on the modulation of the collector current through a small current applied to the base, which allows for the amplification of electrical signals or acts as a power switch. In terms of applications, BJT power transistors are used in high-power audio amplifiers, linear and switched power supplies, output stages in motor controllers, lighting systems, and generally in any circuit where it is necessary to handle significant electrical loads [1].


### Configurations
In this section, the corresponding configurations for BJT power transistors were attached, along with their advantages and disadvantages.

* Common emitter configuration

![Emisor comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Emisor%20comun.png)

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
[1] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.

[2] Redeweb.com. [En línea]. Disponible en:[https://www.redeweb.com/actualidad/mosfet/#:~:text=MOSFET%20de%20potencia&text=Esta%20categor%C3%ADa%20de%20transistores%20ha,energ%C3%ADa%20renovable%20y%20veh%C3%ADculos%20el%C3%A9ctricos.]

[3] – MOSFET AMPLIFIER CONFIGURATIONS y I. Impedance, “Department of electrical and computer engineering”, Charlotte.edu. [En línea]. Disponible en: https://ece.charlotte.edu/wp-content/uploads/sites/301/2023/05/ECGR3155-EXPERIMENT-8-MOSFET-AMPLIFIERS-CONFIGURATIONS-AND-INPUT-OUTPUT-IMPEDANCES.pdf.
