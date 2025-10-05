# Thyristor (Phase Control Circuit)
## Introduction
The thyristor is one of the most important power semiconductor devices in modern electronics. Since its invention in the 1950s, it has been widely used in power control and conversion systems due to its ability to handle high levels of voltage and current. Its internal structure, consisting of four layers of semiconductor material arranged in PNPN sequence, allows it to act as an electronically controlled switch that combines simplicity, robustness, and efficiency. Unlike a mechanical switch, the thyristor can be activated by a small signal at the gate and, once turned on, remains in conduction until the circulating current drops below a minimum value. This latching property makes it an essential component in applications such as controlled rectifiers, motor control systems, high-voltage direct current (HVDC) power transmission, and high-power industrial processes. In a context where energy efficiency and precise control of electrical energy are increasingly important, thyristors remain the devices of choice, especially in large-scale applications where other semiconductors cannot match their robustness and power handling capabilities [1].

![Thyristor symbol](https://github.com/Samuel-Gonzalez22/power_electronics-2025/blob/20534bac3b55afd2fb6d141468a6188bb384c86f/Module%204%20-%20Thyristor%20(Phase%20Control%20Circuit)/Images/Thyristor%20symbol.png)

Figure 1. Thyristor symbol

## Operating principle
The thyristor functions as a controlled electronic switch. Under normal conditions, when a positive voltage is applied between the anode and cathode, the device remains in a blocking state because one of its internal junctions is reverse biased. In this state, only a very small leakage current flows. The transition from the blocking state to the conducting state is achieved by applying a current pulse to the gate. This pulse activates the device internally and causes all its junctions to conduct, allowing a high current to flow from the anode to the cathode. Once turned on, the thyristor remains in conduction even if the gate signal is removed. It will only return to the blocking state when the current flowing through it decreases below a value called the holding current or when the anode-cathode voltage changes polarity (as occurs naturally in alternating current). Thanks to this latching behavior, the thyristor is used in systems where control over switching on is required, but not necessarily over switching off, which is produced by the conditions of the circuit [1].

## Thyristors types
Depending on the physical construction, and turn-on	and	turn-off behavior, thyristors	can	be broadly classified into 13 categories:
1. Phase-controlled	thyristors (or SCRs)
2. Bidirectional phase-controlled thyristors (BCTs)
3. Fast	switching	asymmetrical thyristors (or	ASCRs)
4. Light-activated silicon-controlled rectifiers (LASCRs)
5. Bidirectional triode thyristors (TRIACs)
6. Reverse-conducting thyristors (RCTs)
7. Gate turn-off thyristors (GTOs)
8. FET-controlled	thyristors (FET-CTHs)
9. MOS turn-off thyristors (MTOs)
10. Emitter	turn-off (control) thyristors (ETOs)
11. Integrated gate-commutated thyristors (IGCTs)
12. MOS-controlled thyristors (MCTs)
13. Static induction thyristors (SITHs) [1]

## Applications
Thyristors are widely used in electrical and industrial systems due to their ability to handle high currents and voltages with great efficiency. One of their most common applications is in controlled rectifiers, where they convert alternating current into direct current by regulating the output voltage level. They are also essential in the control of electric motors, as they facilitate smooth starts and speed variation in industrial processes. In the field of power transmission, thyristors play a key role in high-voltage direct current (HVDC) systems, which are used to transport large amounts of energy over long distances with fewer losses. They are also used in industrial furnaces such as induction and electric arc furnaces, where they control the power supplied for smelting and heating processes. In more everyday applications, they are used to regulate lighting through dimmers, as well as in electric heating systems. They have also been very important in the transportation sector, particularly in trains, trams, and subways, to control the power of traction motors. Even in the field of renewable energy, thyristors are used in power conversion and control equipment in solar and wind systems, demonstrating their versatility and relevance in the world of power electronics [1] [2].

## Bibliography
[1] M. H. Rashid, Power electronics: Devices, circuits, and applications, international edition, 4/E. Pearson, 2014.

[2] N. Mohan, W. P. Robbins, y T. M. Undeland, Power electronics: Converters, applications and design, media enhanced, 3a ed. Brisbane, QLD, Australia: John Wiley and Sons (WIE), 2002.
