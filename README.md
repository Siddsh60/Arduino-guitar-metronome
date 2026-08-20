# Arduino-guitar-metronome
An Arduino-based adaptive metronome that starts at half of a user defined target tempo and listens to guitar strumming through a piezo sensor. The Arduino measures the time between strums and compares it with the expected beat interval at the current tempo using a fixed millisecond tolerance, keeping the definition of "close enough" consistent in real time. After 8 consecutive accurate strums, the tempo automatically increases; an inaccurate strum resets the streak. This process repeats until the player reaches the target tempo.

Hardware -
Arduino Uno
Breadboard
Jumper wires
LCD 1602A Screen
Makerhawk Piezo Sensor
Passive Buzzer
Potentiometer
1MΩ Resistor

Wirings

Lcd -
VSS :	GND
VDD :	5V
V0 : Potentiometer Middle pin
RS : Arduino D7
RW : GND
E	: Arduino D8
D4 :	Arduino D9
D5 :	Arduino D10
D6 :	Arduino D11
D7 : Arduino D12
LED A :	5V
LED K :	GND

Potentiometer - 
positive : 5V
negative : GND
Middle Pin/wiper : V0

Piezo Sensor -
postitive	: A0
negative	: GND
1 MΩ resistor : between A0 and GND (parallel with piezo)

Buzzer -
positive	: Arduino D6
negative	: GND


See [Hardware](https://github.com/Siddsh60/Arduino-guitar-metronome/blob/main/hardware) for the exact wiring and [Firmware](https://github.com/Siddsh60/Arduino-guitar-metronome/blob/main/firmware) for the code.
