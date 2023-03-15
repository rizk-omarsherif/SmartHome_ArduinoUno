# Smart-Home_ArduinoUno

Smart Home Project Using LabVIEW LINX with Arduino Uno.

Components used: TCR5000 IR Sensor, SG90 Servo Motor, Sound Sensor Module, LDR, LED, LM35 Temperature Sensor, 2N2222A Transistor and 7805 Voltage Regulator.

Project Description: TCRT5000 IR sensor (digital input) is connected to the door using SG90 micro servo motor (PWM). Sound Sensor Module (digital input) controls the power of a circuit of 2 LEDs (PWM) connected to an LDR (analog input) to control house light intensity based on light intensity out of the house. Temperature sensor LM35 (analog input) is connected to 3 LEDs (digital output) and a 5V DC Fan (digital output) that are turned on according to outside temperature as follows: T ≤ 20C only Blue LED is ON, 20C<T<30C only Yellow LED is ON, T ≥ 30C only both Red LED and 5V DC Fan are ON.
