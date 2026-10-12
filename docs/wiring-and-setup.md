# Wiring and setup

## Planned hardware

- Arduino UNO R3
- ESP8266 / NodeMCU
- FC-28 soil-moisture sensor
- HC-SR04 ultrasonic sensor
- SG90 servo

## Before wiring

Confirm the exact ESP8266 board and sensor modules with the team. ESP8266 pins are 3.3 V logic and can be damaged by 5 V signals. Do not connect the HC-SR04 Echo pin directly to an ESP8266 input; use a suitable voltage divider or level shifter.

The pump, MOSFET driver, diode, external supply, and tubing are optional for the initial demonstration. The project brief says the current components do not include a pump.

## Wiring plan

Add the final pin-by-pin wiring here after the team agrees on which board reads each sensor and drives the servo. Record any required level shifting and separate power supplies.

## Software setup

Add the selected Arduino IDE version, required board packages, libraries, MQTT broker, and dashboard instructions here.
