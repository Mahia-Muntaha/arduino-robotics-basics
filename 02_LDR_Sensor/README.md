# LDR Sensor

An Arduino project that uses an LDR (Light Dependent Resistor) to measure light intensity and control an LED based on a predefined threshold.

## Objective

To understand analog sensor input and use the sensor reading to control a digital output.

## Components

* Arduino
* LDR
* LED
* Resistor
* Breadboard
* Jumper wires

## Working Principle

The LDR produces an analog voltage that varies with the intensity of light. Arduino reads this value through an analog input pin.

When the sensor reading falls below the defined threshold, the LED is turned ON. Otherwise, the LED remains OFF.

## Threshold

The current threshold value is:

```text
400
```

This value may need to be adjusted depending on the LDR circuit, lighting conditions, and resistor configuration.

## Code

The complete implementation is available in [`LDR_Sensor.ino`](./LDR_Sensor.ino).

## Concepts

* Analog input
* `analogRead()`
* Digital output
* Sensor threshold
* LDR interfacing
