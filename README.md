Arduino I2C LCD Welcome Display

A simple Arduino project that displays a welcome message on a 16x2 I2C LCD. The display first welcomes viewers to Experiment Verse and then asks them to subscribe to the channel.

Features

* Displays “Welcome to”
* Displays “Experiment Verse”
* Changes to “Please Subscribe”
* Easy to build with only an Arduino and an I2C LCD
* Beginner-friendly project

Components Required

* Arduino Uno, Nano, or Mega
* 16x2 I2C LCD Display
* USB Cable
* Jumper Wires

Wiring

I2C LCD Pin	Arduino Uno/Nano
VCC	5V
GND	GND
SDA	A4
SCL	A5

For Arduino Mega:

* SDA → Pin 20
* SCL → Pin 21

Library Required

Install the following library using the Arduino IDE Library Manager:

* LiquidCrystal_I2C

How It Works

1. Initializes the I2C LCD.
2. Turns on the LCD backlight.
3. Displays “Welcome to”.
4. Shows “Experiment Verse”.
5. Waits for a few seconds.
6. Displays “Please Subscribe”.

Upload Instructions

1. Connect the Arduino to your computer.
2. Open the Arduino sketch.
3. Select the correct Board and COM Port in the Arduino IDE.
4. Click Upload.
5. Enjoy the welcome animation on your LCD.

Troubleshooting

* If nothing appears on the LCD, try changing the I2C address from 0x27 to 0x3F.
* Verify the SDA and SCL connections.
* Ensure the LiquidCrystal_I2C library is installed.
* Adjust the LCD contrast using the potentiometer on the I2C module if the display is blank.

Project Structure

Arduino-I2C-LCD-Welcome/
├── Arduino_I2C_LCD_Welcome.ino
├── README.md
└── LICENSE (optional)

Demo

The LCD displays:

Welcome to
Experiment Verse

Then changes to:

Please
Subscribe

License

This project is free to use for educational and personal purposes.

Author

Experiment Verse

If you found this project helpful, consider subscribing to the Experiment Verse YouTube channel for more Arduino, electronics, robotics, and DIY projects.
