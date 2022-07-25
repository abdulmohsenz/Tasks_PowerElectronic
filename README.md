servo motor:
First we need to connect the servo motor to the Arduino by connecting it to V5, GND and one of the DigitalPin, and to control it we need to add a code and the code used to move the servo motor to the degree that is specified from 0 to 180 degrees, which is the highest degree that the servo can motor access to it.

Stepper motor:
The Stepper motor cannot be connected to the Arduino directly, because the Stepper motor needs 4 DigitalPin, and when connected to the Arduino directly, it may cause damage to the Arduino, so it is necessary to add a Driver Board, there are 2048 degrees in the stepper motor, to control the stepper motor we need to add a code And the code used in it to determine the speed of rotation and the number of steps it rotates.

Brushless/DC motor:
To connect the Brushless/DC motor, we need a Driver Board, a power source, and a Potentiometer to control the rotational speed of the Brushless/DC motor and the Breadboard for connection. The Breadboard is connected to an external power source, and also connected to GND and V5 on the Arduino, and the Potentiometer is connected to the ANALOG IN and GND and also the V5 on the Arduino, and connect the Brushless / DC motor to the Driver Board and from the Driver Board to two of the DigitalPin on the Arduino, and to move it, we need to write a code that we can control the Brushless / DC motor through the Potentiometer.

PushButton:
The PushButton is a tool for connecting or disconnecting an electronic circuit, to use it we need an Arduino, a Breadboard and a resistor to provide the voltage and also the output. The LED has been used in this circuit. To turn it on, we need to write a code in which the LED will turn on when PushButton is pressed and turn off automatically when not Press it with resistance.
