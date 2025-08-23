# Power Transistors (BJT, MOSFET and IGBT)
## Introduction
A power transistor is a semiconductor device specifically designed to handle high levels of current and voltage while maintaining the ability to switch controlled at high speed. Unlike small-signal transistors, which are optimized to amplify low-level signals, power transistors are built and designed to support and control significant flows of electrical energy. The fundamental distinguishing feature of power transistors is their ability to operate as electronically controlled switches. This means they can quickly toggle between their on and off states, blocking the flow of current by presenting high impedance.

## Theoretical Framework
### BJT Power Transistors
A BJT power transistor is a bipolar junction semiconductor device designed to operate in applications where control and handling of high levels of current and voltage are required. Its principle of operation is based on the modulation of the collector current through a small current applied to the base, which allows for the amplification of electrical signals or acts as a power switch. In terms of applications, BJT power transistors are used in high-power audio amplifiers, linear and switched power supplies, output stages in motor controllers, lighting systems, and generally in any circuit where it is necessary to handle significant electrical loads.


In these transistors, their saturation state refers to the condition in which both the base-emitter junction and the base-collector junction are forward-biased. This implies that the transistor conducts the maximum possible current from the collector to the emitter for a given base current, effectively functioning as a closed switch. In this state, the collector-emitter voltage (VCE) drops to a very low value, resulting in minimal power losses due to dissipation. However, saturation also brings certain disadvantages: the charge storage time in the base can slow down switching, which is undesirable in high-frequency applications. For this reason, in switch-mode power supplies and power systems, it is sought that the transistor operates efficiently in cutoff (as an open switch) and in saturation (as a closed switch), thus optimizing performance and reducing losses.


The configurations applied to BJT power transistors are the same as those applied in BJT transistors typically used in low-power circuits, but there is a key difference: although they are the same configurations, there are practical differences, for example:
- In BJT transistors ordinary, the focus is primarily on amplifying small signals, high gain, and speed.
- In BJT power transistors, the priority is the ability to handle high currents and voltages, which is why they require higher base currents to enter conduction.

### Configurations
In this section, the corresponding configurations for BJT power transistors were attached, along with their advantages and disadvantages.

Common sender configuration

![Emisor comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Emisor%20comun.png)

In this connection, the emitter is located as the reference terminal (usually grounded), while the input signal is applied to the base and the output is obtained at the collector. Its importance lies in that it allows for a high current gain and efficient operation in switching mode (saturation and cutoff), making it ideal for controlling high power loads such as transformers, motors, or DC-DC converters.
The common emitter configuration is the most used in BJT power transistors because it offers high current and power gain, in addition to allowing efficient control of switching between cutoff and saturation states. In applications such as switched-mode power supplies, inverters, and switching power amplifiers, the transistor is not used as a linear amplifier, but as a switch.

Advantages 
- It works very well as a switch: in power electronics, it is efficient in cutoff and saturation modes, which allows it to be used as a controlled switch.
- Significant voltage gain: in addition to current, it can provide voltage amplification, making it versatile.
- Wide application in power: it is the standard configuration in switched-mode power supplies, inverters, motor controls, and regulators.

Disadvantages 

- Longer switching times than other devices: especially compared to MOSFETs or IGBTs, the deep saturation of the BJT introduces a charge storage time that delays the turn-off.
- It requires a greater excitation current at the base: unlike MOSFETs, the BJT needs a continuous current at the base to remain in conduction.
- Lower efficiency at very high power: although it is widely used, at very high power levels it tends to be replaced by MOSFETs or IGBTs due to switching losses.



Common base configuration

![Base comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Base%20comun.png)


In the common base configuration, the base is connected as a reference for both the input and output signals. The input is applied between the emitter and the base, and the output is obtained between the collector and the base. In this configuration, the collector current is almost directly determined by the emitter current, and the current gain is low. However, the main advantage of this configuration is that it offers greater bandwidth and better performance at high frequencies, compared to the common emitter configuration.

Advantages 

- High voltage gain: although it does not increase the current, it can significantly amplify voltage signals.
- Stability: it has lower unwanted internal feedback than the common emitter configuration, making it more stable in certain high-frequency designs.

Disadvantages

- Low input impedance: it makes it difficult to connect to signal sources that cannot supply high currents.
- More complex polarization: it requires a more robust emitter excitation design, which increases the cost and difficulty of the circuit.




Common collector configuration

![Colector comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Colector%20comun.png)


In this configuration, the collector is the common terminal for both the input and the output. The input signal is applied between the base and the collector, and the output is obtained between the emitter and the collector. Due to this arrangement, the output signal is in phase with the input and has a voltage gain close to one (≈1), but with a high current gain.

Advantages

- High input impedance and low output impedance: ideal for coupling a weak signal source with a low resistance load.
- Signal stability: the output voltage follows the input, providing a very useful voltage follower in power control.
- Simplicity in polarization: easier to polarize than common base.


Disadvantages

- Lower efficiency as a switch: it is not the most suitable configuration for cutoff and saturation, where the common emitter performs better.
- Limitations at high power: although it offers good impedance matching, it is not the most efficient option for handling large power loads.
- Specialized use: it is used more as a buffer or adapter than as the main switching device in power supplies.
