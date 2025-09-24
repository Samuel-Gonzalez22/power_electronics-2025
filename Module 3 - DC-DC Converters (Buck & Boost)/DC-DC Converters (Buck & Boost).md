# DC-DC Converters (Buck & Boost)
## Introduction
A DC-DC converter is an electronic device characterized by its ability to alter the voltage of direct current (DC) between different values. This is valuable in many situations, as often different elements within a single electronic device require various voltage levels to operate correctly. Thus, converters have the ability to increase, reduce, or reverse the voltage as required. Unlike an AC-DC converter, which transforms alternating current (AC) from the electrical grid into direct current (DC), the DC-DC converter works exclusively with direct current, modifying its voltage as necessary. DC-DC converters are composed of inductors, capacitors, diodes, and transistors, along with pulse width modulation techniques to achieve efficient energy conversion. In this way, they operate as follows: the duty cycle of the input signal is modulated, and the converter regulates the ratio between the time it is activated and deactivated, allowing the desired output to be controlled [1]. 

## Operation and applications
DC-DC converters are composed of inductors, capacitors, diodes, and transistors, along with pulse width modulation techniques to achieve efficient energy conversion. In this way, they operate as follows: the duty cycle of the input signal is modulated, and the converter regulates the ratio between the time it is activated and deactivated, allowing the desired output to be controlled. It is widely used in power electronics, the renewable energy sector, communication systems, and the automotive industry [1] & [2].


## Configurations

### Buck Converter (Reducers)

They allow a lower voltage than the input voltage to be obtained at the output. They are ideal when it is necessary to reduce a voltage to power circuits that require a lower voltage. In continuous mode, it is a converter whose voltage output depends exclusively on the duty cycle and the input voltage. The relationship is given by (1) 

$V_{out} = D \cdot V_{in}$ (1)

In a buck converter, the duty cycle is modified so that the output voltage remains at the intended level. However, when connecting a load that powers a system, the output voltage is influenced by the effect of that load. One way to regulate the output voltage in response to load variation is to dynamically adjust the duty cycle. The duty cycle is the ratio D whose domain is between 0 and 1, and whose output voltage will never exceed the input voltage. To adjust the duty cycle, a pulse width modulator can be incorporated into the circuit at the switch connected in series to the source. The duty cycle is adjusted with the switching frequency of the PWM [3].

![Buck Converter](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/cd9f92f7bea412332b0a0a7750deeebb6759a890/Module%203%20-%20DC-DC%20Converters%20(Buck%20%26%20Boost)/Images-Simulations/Buck_operating.svg.png)

Figure 1. Buck converter operation

### Boost Converter (Elevators)

They allow a higher voltage than the input voltage signal to be obtained at the output. They are useful for raising a voltage, for example, to recharge batteries or to supply devices that require a higher voltage. The basic principle consists of two different states, depending on the switch:
* When the switch is closed, the coil stores energy from the source, while the load is powered by the capacitor.
* When the switch is open, the current only passes through the diode and flows through the capacitor and the load.

![Boost Converter](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/cd9f92f7bea412332b0a0a7750deeebb6759a890/Module%203%20-%20DC-DC%20Converters%20(Buck%20%26%20Boost)/Images-Simulations/Boost_operating.svg.png)

Figure 2. Boost converter operation


## Bibliography
[1] Distron, “Convertidor DC-DC: qué es y cómo se aplica”, Distron, 08-jun-2023. [En línea]. Disponible en: https://distron.es/convertidor-dc-dc-funcionamiento-aplicaciones/.

[2] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.

[3] R. D. B. Isaza, “Control difuso aplicado a un convertidor DC-DC buck para una carga no lineal”, Tecnura, vol. 20, núm. 48, pp. 117–148, 2016.
