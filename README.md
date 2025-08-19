🔗 Arduino + HC-05 Bluetooth Communication

This project demonstrates how to establish serial communication between an Arduino Uno and an HC-05 Bluetooth module.
It allows you to send and receive data wirelessly between your Arduino and a smartphone/PC Bluetooth terminal app.

📌 Features

Two-way serial communication via Bluetooth.

Send data from Arduino Serial Monitor → smartphone via Bluetooth.

Receive data from smartphone → Arduino Serial Monitor.

Works with any Bluetooth terminal app (e.g., Serial Bluetooth Terminal).

🛠️ Hardware Required

Arduino Uno (or compatible board)

HC-05 Bluetooth Module

Jumper wires

Breadboard (optional)

⚡ Circuit Connections
HC-05 Pin	Arduino Pin
VCC	5V
GND	GND
TX	Pin 2 (RX of SoftwareSerial)
RX	Pin 3 (TX of SoftwareSerial)
EN/KEY	(Not used, leave unconnected)

⚠️ Note: Use a voltage divider (e.g., 1kΩ + 2kΩ resistors) on HC-05 RX pin if connecting directly from Arduino TX (to avoid 5V logic damage).

📦 Library Dependencies

SoftwareSerial
 (built-in with Arduino IDE)