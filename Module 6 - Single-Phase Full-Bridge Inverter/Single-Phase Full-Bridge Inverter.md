# Controlled Rectifier
## Introduction
It is an electronic device that converts direct current (DC) into alternating current (AC). To perform this conversion, it uses a diode bridge circuit, generating greater efficiency than other types of inverters, which is why single-phase inverters are less complex than three-phase inverters [1]. 

## Principle of operation
This type of inverter consists of four choppers. When transistors Q1 and Q2 are turned on simultaneously, the input voltage Vs appears across the load. If transistors Q3 and Q4 are turned on at the same time, the voltage across the load is reversed and is -Vs.
Transistors Q1, Q4 act as the switching devices S1 and S4, respectively. If two switches: one upper and one lower conduct at the same time such that the output voltage is {Vs, the switch state is 1, where as if these switches are off at the same time, the switch state is 0. [2].
Table 1 shows the five switch states

![Switch states for a SPFBI](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/d24aba91fb4536529846236556988aba849b018b/Module%206%20-%20Single-Phase%20Full-Bridge%20Inverter/Images/Switch%20states%20for%20a%20SPFBI.png)

Table 1. Switch states for a SPFBI

### Configurations



* Common base configuration

![Base comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Base%20comun.png)


* Common collector configuration

![Colector comun](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/804306eaceb8bfa4e6ee32a0bd8154dd7eb4938d/Module%202%20-%20Power%20Transistors%20(BJT,%20MOSFET,%20and%20IGBT)/Images/Configurations/Colector%20comun.png)


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





## Configurations




## Bibliography
[1] Powerelectronicsnews.com. [En línea]. Disponible en: https://www.powerelectronicsnews.com/power-electronics-course-part-10-the-single-phase-full-bridge-inverter/. 

[2] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.

[3] M. Youssef, C. Boubahri, F. Aloui, y S. Fetni, “Simulation and design of A single phase inverter with digital PWM issued by an Arduino board”, International Journal of Engineering Research and, vol. 9, 2020.
