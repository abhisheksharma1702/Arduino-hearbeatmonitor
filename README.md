# ArduinoUno-hearbeatmonitor
A heart beat monitoring device with heart-beat sensor made by using Arduino Uno.

A)  Equipment:
An Arduino uno device, heart-beat sensor, Jumper wires, Bread-board, LCD Display 16 x 2, Laptop for uploading the code to Arduino.

B)	Circuit Description:
The full circuit has been constructed in three steps: The connection of the +5V and GND to the bread board, the connection of the LCD to the breadboard, the connection of the Pulse sensor to Arduino board and bread board

C)	Connections:
Using jumper wires connect the Arduino board +5V (positive) and GND (ground) port to two separate breadboard slots. The 1st pin (VSS) of the LCD is connected to GND slot of the breadboard. 2nd pin (VCC) of the LCD is connected to the +5V slot of the breadboard. 3rd pin (VEE) is ground or can be connected through a 10k ohm potentiometer to control the contrast of the LCD backlight. 4th pin (RS) of the LCD is connected to the digital pin D12 of the Arduino UNO board. 5th pin (RW) of the LCD is ground. 6th pin is connected to the digital pin D11 of the Arduino UNO board. 11th pin (DB4), 12th pin (DB5), 13th pin (DB6), 14th pin (DB7) are connected to Arduino digital pins D5, D4, D3, D2 respectively. The pulse “S” (Signal) is connected to the analog pin A0 of the Arduino UNO board. The “+” (VCC) is connected to +5V and the “-” (GND) is connected to ground on the breadboard.

![alt text](https://i.imgur.com/NVLrybF.png)
![alt text](https://i.imgur.com/86TSMKR.png)
