# MCC Melody for PIC16 - CLC Demo

Demonstrate how to use the CLC (Configurable Logic Cell) peripheral with PIC16, configured via MCC Melody.

## 📹 Video Tutorial
<!-- Add your video link here -->

## 🛠️ Tools & Hardware
- MPLAB X IDE
- MCC Melody
- PIC16F13145 Curiosity Nano (EV06M52A)

## 📋 What it does
- Demonstrates how to use CLC (Configurable Logic Cell) to drive an RGB LED via PWM
- PIC16F13145 has only 2 PWM channels, so this demo uses 2 CLC modules, one for each PWM output
- Each CLC performs an AND operation between the PWM signal and the switch input
- Pressing the button gates the PWM signal through to the LED channel
- Since only 2 of 3 RGB channels are driven, the demo shows 2 individual colors plus 1 mixed color when both channels are active
