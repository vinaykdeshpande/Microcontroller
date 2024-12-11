# Microcontroller
Arduino Uno to Mega UART Communication - LED Control
This project demonstrates how to establish UART communication between an Arduino Uno and an Arduino Mega. The Uno acts as the sender, transmitting ON and OFF commands via UART, while the Mega acts as the receiver, controlling an LED based on the received commands.
Features

UART Communication: Demonstrates basic UART communication between two Arduino boards.
LED Control: The Arduino Mega turns an LED on or off based on commands (ON/OFF) received from the Arduino Uno.
Debugging: Debug messages are sent to the Serial Monitor for easy troubleshooting.

Requirements:
1.  Arduino Uno
2.  Arduino Mega
3.  Two LEDs (one for each board)
4.  Jumper wires
5.  Breadboard (optional)

Wiring
1.  Connect the Uno's TX pin (Pin 1) to the Mega's RX1 pin (Pin 19).
2.  Connect the Uno's GND to the Mega's GND.
3.  Connect an LED to Pin 13 on each board with an appropriate resistor.

Usage
Upload the Sender code to the Arduino Uno.
Upload the Receiver code to the Arduino Mega.
Open the Serial Monitor for the Arduino Mega (set to 9600 baud) to observe debug messages.
Observe the LED on the Mega toggling on and off every 3 seconds based on commands received from the Uno.
