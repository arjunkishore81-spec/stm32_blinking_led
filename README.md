# Automatic Sensor-Based LED Control System Using STM32

## Aim

To interface a digital sensor with an STM32 microcontroller and automatically control an LED according to the sensor output.

## Apparatus Required

| S. No. | Component | Quantity |
|---:|---|---:|
| 1 | STM32 development board | 1 |
| 2 | Digital sensor or push button | 1 |
| 3 | LED | 1 |
| 4 | 220–330 Ω resistor | 1 |
| 5 | Breadboard | 1 |
| 6 | Jumper wires | As required |
| 7 | USB cable | 1 |

## Algorithm
Start the program.
Initialize the STM32 HAL library.
Configure the system clock.
Configure PA0 as a digital input.
Configure PA5 as a digital output.
Read the digital signal from PA0.
Check whether the sensor output is HIGH or LOW.
If the sensor output is HIGH, set PA5 HIGH and turn ON the LED.
If the sensor output is LOW, set PA5 LOW and turn OFF the LED.
Repeat the process continuously.
Stop.



## Program

## Result

The digital sensor was successfully interfaced with the STM32 microcontroller. The LED connected to `PA5` turned ON when the sensor input at `PA0` was HIGH and turned OFF when the sensor input was LOW.
