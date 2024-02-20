# Digital-keypad-security-door-using-Arduino
Objective:
Often times, we need to secure a room at our home or
office (perhaps a secret dexter ’s laboratory) so that no one can access the room without our permission and ensure protection against theft or loss of our important accessories and assets. There are so many types of security systems present today but behind the scene, for authentication they all relay on fingerprint, retina scanner, iris scanner, face id, tongue scanner, RFID reader, password, pin, patterns, etc. Off all the solutions the low-cost one is to use a password or pin-based system. So, in this project, We have built an Arduino Keypad Door Lock which can be mounted to any of your existing doors to secure them with a digital

password. 
List of components: 

1. Arduino Uno/Pro/Mini or Custom board using Atmega   328p Microcontroller 
2. 16 x 2 LCD (Liquid Crystal Display)
3. 4 x 3 or 4 x 4 matrix keypad for Arduino
4. Servo motor
5. 3D printed door locker/customised door locker
6. Additional components for power supply of 1 Amp 5 Volt mobile charger
7. 4’’ / 6’’plastics boxes, jumper wires, nuts bolts, plastic casing, etc.

Theory:

First of all, we start from the brain of this project which is the Arduino UNO board. The Arduino board is connected to an LCD and a servo motor. The servo motor is used to push (lock) or pull (unlock) the latch on the door. A 16 x 2 LCD is required to display the message by Arduino, 16 x 2 means it has 16 number of columns and 2 number of rows. 

We are using a 5v Towerpro SG90 servo motor for making our customized door locker. It is a basic level servo motor and works fine with Arduino without any driving circuit or external module. Also, the cost of this servo motor is very less so you can easily afford to buy it. Connect the servo motor with Arduino Digital pin D9 and with a 5volt power supply. This servo motor has a total of 3 input lines (GND, +5V & SIGNAL LINE).

In this project, I have used a 4 x 4 matrix keypad (but the 4 x 4 keypad part is not available in fritzing for making this graphical representation), but don’t worry as 4 x 3 Matrix keypad also works fine with my coding. We need a keypad for password input and manually lock our customised door locker. It consists of 16 keys (soft switch) 4 keys in Rows (R1, R2, R3, R4) and 4 keys in Columns (C1, C2, C3, C4) when a key pressed, it establishes a connection in between the corresponding rows and columns. The below table shows how to connect your Arduino with Keypad. 

"
Keypad"	"
Arduino "
"
Pin 1 (row 1)"	"
Digital Pin1"
"
Pin 2 (row 2)"	"
Digital Pin 2"
"
Pin 3 (row 3)"	"
Digital pin 3"
"
Pin 4 (row 4)"	"
Digital pin 4"
"
Pin 5 (columns 5)"	"
Digital pin 5"
"
Pin 6 (columns 6)"	"
Digital pin 6"
"
Pin 7 (columns 7)"	"
Digital pin 7"
<img width="284" alt="image" src="https://github.com/danushtom/Digital-keypad-security-door-using-Arduino/assets/89013357/9bd53e37-666c-44cf-801c-9cb4553e6079">

Advantages: 
Automatic Door Lock Allows Keyless Entry : With a keyless automatic door lock, you would not have to bother about losing or forgetting your keys. You probably have experienced how frustrating it is to get locked out of your own home.

Automatic Door Lock Allows Personalised Entry :
An automatic door lock is also ideal for anyone who wants a personalised entry. You could change your code in any way or any time you want. 

Automatic Door Lock Gives You More Control : The automatic door lock is known to strengthen home security. Aside from this, it also allows you to have more control over your own home. 

Automatic Door Lock Is Convenient for the Elderly and Disabled : The automatic door lock also has a positive eﬀect on society. This device allows the elderly and disabled to easily unlock door locks.
