# DC Motor Control

An Arduino project demonstrating basic speed and direction control of a DC motor using PWM signals.

## Objective

To understand the basic principles of DC motor direction and speed control using Arduino and a suitable motor driver.

## Components

* Arduino
* DC Motor
* Motor Driver / H-Bridge
* External motor power supply
* Breadboard
* Jumper wires

## Working Principle

The motor driver receives control signals from two Arduino output pins.

PWM is used to control the motor speed, while the combination of the two control signals determines the direction of rotation.

The program:

1. Rotates the motor in one direction.
2. Stops the motor.
3. Rotates the motor in the opposite direction.
4. Stops the motor.
5. Repeats the sequence.

## Speed Control

The current PWM value is:

```text
120 / 255
```

This value can be adjusted to change the motor speed.

## Important Note

The DC motor should **not be powered directly from an Arduino digital pin**. A suitable motor driver or H-bridge and an appropriate external power supply should be used.

## Code

The complete implementation is available in [`DC_Motor_Control.ino`](./DC_Motor_Control.ino).

## Concepts

* PWM
* DC motor control
* Direction control
* Motor drivers
* Digital output
