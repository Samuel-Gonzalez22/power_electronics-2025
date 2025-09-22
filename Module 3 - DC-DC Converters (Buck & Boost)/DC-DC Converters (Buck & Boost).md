# DC-DC Converters (Buck & Boost)
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











## Bibliography
[1] Distron, “Convertidor DC-DC: qué es y cómo se aplica”, Distron, 08-jun-2023. [En línea]. Disponible en: https://distron.es/convertidor-dc-dc-funcionamiento-aplicaciones/.

[2] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.

[3] – MOSFET AMPLIFIER CONFIGURATIONS y I. Impedance, “Department of electrical and computer engineering”, Charlotte.edu. [En línea]. Disponible en: https://ece.charlotte.edu/wp-content/upl
