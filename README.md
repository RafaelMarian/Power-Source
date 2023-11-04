# Power Source Project

## Overview

The Power Source Project entails the design and development of various components and systems related to power generation, regulation, and management. The project integrates multiple elements, such as voltage regulators, stabilizers, and converters, to achieve stable and efficient power supply solutions.

## Stabilizer

The stabilizer focuses on maintaining a constant output voltage despite variations in input voltage, load current, or temperature fluctuations. The design involves a series transistor without an error amplifier, utilizing specific parameters to achieve the desired output voltage.

### Design Specifications:
- Voltage Input: 18V (17.5V)
- Voltage Output: 12V
- Current Output: 0.5A
- Suimin: 150
- Romax: 0.4 ohms

### Calculations & Component Selection:
The calculations involved determining diode and transistor parameters such as forward voltage and current, as well as resistance values. Specific diodes (UDZS13B) and transistors (QBD135, 2N4401) were selected based on datasheet specifications and electrical characteristics.

## Voltage Regulator

The voltage regulator aims to maintain a stable output voltage and operates as a linear regulator. The designed circuit enables consistent output voltage despite fluctuations in input conditions.

### Design Criteria:
- Output Current: Up to 0.8A
- Output Voltage: 5V

### Calculations & Component Selection:
The circuit calculations involved determining resistance values and selecting a specific linear regulator with IC LM7805, meeting the required output voltage and current specifications.

## DC-DC Converter

The DC-DC converter project focuses on producing a lower output voltage than the input. It operates in either continuous or discontinuous conduction mode, depending on the load and current conditions.

### Design Requirements:
- Output Voltage: 3.3V
- Maximum Output Current: 4A
- Minimum Output Current: 100mA
- Switching Frequency: 100kHz
- Output Ripple Voltage: 20mV

### Calculations & Component Selection:
Design calculations involved determining duty cycle, selecting diodes, transistors, and other necessary components based on datasheet specifications and electrical characteristics.

## Conclusion

The Power Source Project incorporates various aspects of power generation, regulation, and conversion, ensuring stable and efficient power supply solutions. Each section of the project highlights calculations, component selections, and design criteria tailored to specific output and current requirements.

This README serves as an overview of the Power Source Project, summarizing the different components and their roles in achieving reliable power supply solutions.
