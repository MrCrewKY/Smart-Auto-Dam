# Smart-Auto-Dam
My Last Internship Project at Kidocode

This project uses Ultrasonic Sensor, I2CLCD, 4x4 Keypad, Arduino Uno R3, Buzzer, 3 LEDs, 1 SG90 Servo.

Concept:
The LCD display prompts the user to enter a password.
User enters password through 4x4 keypad.
If password is correct, smart detection system is activated.
The ultrasonic sensor measures the distance between water surface(object) and the sensor in the smart dam. 
Based on the distance measured, different color LEDs light up accordingly, with green as safe, yellow as medium and red as danger.
When the water level reaches danger zone, red LED is light up followed by the buzzer alarm. Then, the servo rotates to 180 degrees to lift open the water dam gate.
When a logout key is pressed, the smart detection system is turned off.
If password is wrong, the smart detection system will not be activated
