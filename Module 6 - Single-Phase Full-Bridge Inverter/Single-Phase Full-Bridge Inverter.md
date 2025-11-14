# Single-Phase Full-Bridge Inverter
## Introduction
It is an electronic device that converts direct current (DC) into alternating current (AC). To perform this conversion, it uses a diode bridge circuit, generating greater efficiency than other types of inverters, which is why single-phase inverters are less complex than three-phase inverters [1]. 

## Principle of operation
This type of inverter consists of four choppers. When transistors Q1 and Q2 are turned on simultaneously, the input voltage Vs appears across the load. If transistors Q3 and Q4 are turned on at the same time, the voltage across the load is reversed and is -Vs.
Transistors Q1, Q4 act as the switching devices S1 and S4, respectively. If two switches: one upper and one lower conduct at the same time such that the output voltage is +Vs to -Vs, the switch state is 1, where as if these switches are off at the same time, the switch state is 0 [2].

Table 1 shows the five switch states

![Switch states for a SPFBI](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/d24aba91fb4536529846236556988aba849b018b/Module%206%20-%20Single-Phase%20Full-Bridge%20Inverter/Images/Switch%20states%20for%20a%20SPFBI.png)

Table 1. Switch states for a SPFBI [2]

The electronic switches operate in pairs: in one half-cycle, only S1 and S2 are closed, while in the other, S3 and S4 are closed. The inverter output is an alternating voltage with variable frequency, depending on the frequency of the control signals. 

## Modulation techniques
The most common modulation technique for inverters is pulse width modulation (PWM).
The main objective of these techniques is to improve the output of inverters by obtaining an output voltage or current that is very close to a sinusoidal waveform. But for this project, the pulse is square wave, generated from the Arduino to the entire circuit [3].

## Applications
- UPS Systems
- Photovoltaic Inverters
- AC Motor Control
- DC/AC Converters in Power Electronics
- Embedded Systems with Digital PWM (Arduino, DSP, FPGA)

## Architecture (components and diagram)


## Bibliography
[1] Powerelectronicsnews.com. [En línea]. Disponible en: https://www.powerelectronicsnews.com/power-electronics-course-part-10-the-single-phase-full-bridge-inverter/. 

[2] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.

[3] M. Youssef, C. Boubahri, F. Aloui, y S. Fetni, “Simulation and design of A single phase inverter with digital PWM issued by an Arduino board”, International Journal of Engineering Research and, vol. 9, 2020.
