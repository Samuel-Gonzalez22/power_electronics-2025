# Power Transistors (BJT, MOSFET and IGBT)
## Introduction
A power transistor is a semiconductor device specifically designed to handle high levels of current and voltage while maintaining the ability to switch controlled at high speed. Unlike small-signal transistors, which are optimized to amplify low-level signals, power transistors are built and designed to support and control significant flows of electrical energy. The fundamental distinguishing feature of power transistors is their ability to operate as electronically controlled switches. This means they can quickly toggle between their on and off states, blocking the flow of current by presenting high impedance.

## Theoretical Framework
### BJT Power Transistors
A BJT power transistor is a bipolar junction semiconductor device designed to operate in applications where control and handling of high levels of current and voltage are required. Its principle of operation is based on the modulation of the collector current through a small current applied to the base, which allows for the amplification of electrical signals or acts as a power switch. In terms of applications, BJT power transistors are used in high-power audio amplifiers, linear and switched power supplies, output stages in motor controllers, lighting systems, and generally in any circuit where it is necessary to handle significant electrical loads.


### Configurations
In this section, the corresponding configurations for BJT power transistors were attached, along with their advantages and disadvantages.

Common sender configuration

![Emisor comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Emisor%20comun.png)

In this connection, the emitter is located as the reference terminal (usually grounded), while the input signal is applied to the base and the output is obtained at the collector. Its importance lies in that it allows for a high current gain and efficient operation in switching mode (saturation and cutoff), making it ideal for controlling high power loads such as transformers, motors, or DC-DC converters.
The common emitter configuration is the most used in BJT power transistors because it offers high current and power gain, in addition to allowing efficient control of switching between cutoff and saturation states. In applications such as switched-mode power supplies, inverters, and switching power amplifiers, the transistor is not used as a linear amplifier, but as a switch.




Common base configuration

![Base comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Base%20comun.png)


In the common base configuration, the base is connected as a reference for both the input and output signals. The input is applied between the emitter and the base, and the output is obtained between the collector and the base. In this configuration, the collector current is almost directly determined by the emitter current, and the current gain is low. However, the main advantage of this configuration is that it offers greater bandwidth and better performance at high frequencies, compared to the common emitter configuration.





Common collector configuration

![Colector comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Colector%20comun.png)


In this configuration, the collector is the common terminal for both the input and the output. The input signal is applied between the base and the collector, and the output is obtained between the emitter and the collector. Due to this arrangement, the output signal is in phase with the input and has a voltage gain close to one (≈1), but with a high current gain.


### MOSFET Power Transistors
The power MOSFET (Metal-Oxide-Semiconductor Field-Effect Transistor) is a voltage-controlled device widely used in power electronics due to its high efficiency and switching speed. Its structure allows large currents to be controlled by a small gate signal, thanks to its high input impedance. In terms of applications, Power supplies, motor controllers, renewable energy systems and electric vehicles [2].

### Configurations
* There are three main connection configurations for power MOSFETs:

* Common source configuration

* In this configuration, the gate is controlled by the input signal, and the drain and source are the output terminals. This configuration is the most common and offers high voltage gain.

* Common gate configuration

* The gate is connected to a current source or ground (in AC), and the input signal is applied to the source. The drain is the output. This configuration is suitable for high-frequency applications.

* Common drain configuration

* The gate receives the input signal, the drainer is used for loading, and the output is taken from the drainer. This configuration has unity voltage gain and high input impedance.

















## IGBT power transistors

The IGBT (Insulated Gate Bipolar Transistor) is a hybrid power semiconductor device that combines the characteristics of MOSFETs and BJTs. It has an insulated gate controlled by voltage, which means low control power consumption, and a bipolar conduction region, which allows it to handle high currents and voltages with low voltage drop in the on state. Due to these properties, the IGBT is widely used in inverters, frequency converters, electric traction systems, and renewable energy, being one of the most common power devices in medium and high voltage applications.

## Configurations





## Bibliography
[1] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.
[2] [4]	Redeweb.com. [En línea]. Disponible en: [https://www.redeweb.com/actualidad/mosfet/#:~:text=MOSFET%20de%20potencia&text=Esta%20categor%C3%ADa%20de%20transistores%20ha,energ%C3%ADa%20renovable%20y%20veh%C3%ADculos%20el%C3%A9ctricos.]
