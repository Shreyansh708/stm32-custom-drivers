# Alternating LED Blink – STM32F446RE

This example demonstrates register-level GPIO control on the STM32F446RE
using two external LEDs connected via a breadboard.

The LEDs blink alternately using direct register manipulation without HAL.

## Hardware Used
- STM32 Nucleo-F446RE
- Breadboard
- 2 LEDs
- 220–330 Ω resistors
- Jumper wires

## Connections
PA5 (D13) → Resistor → LED1 → GND  
PA6 (D12) → Resistor → LED2 → GND  

## Behavior
LED1 and LED2 blink alternately with a software delay loop.

## Concepts Practiced
- Enabling GPIO clocks
- Register-level GPIO configuration
- Output pin control
- Breadboard interfacing
- Hardware debugging

## Future Improvements
- Timer-based delay instead of software loops
- Interrupt-based button control
- PWM LED brightness control

---
Author: Shreyansh Saxena
