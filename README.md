# HOME-AUTOMATION-WITH-BLUETOOTH

COMPANY: CODTECH IT SOLUTIONS

"NAME: SRIHARI A

"INTERN ID: CT04DY35

"DOMAIN: FRONT END DEVELOPMENT"

DURATION: 4 WEEEKS

"MENTOR: VAISHALI"

Project Description:

This project allows users to remotely control home appliances using an Android smartphone. The system uses an Arduino Uno board, a 16x2 LCD display, and six relays or output devices connected to digital pins. Communication between the Android device and Arduino is done using Serial Communication, likely through a Bluetooth module (HC-05/HC-06) or via USB-OTG.

The project demonstrates:

Turning appliances ON/OFF via simple character commands sent from a smartphone.

Real-time feedback on a 16x2 LCD screen indicating which appliance is active.

A welcome and credit display sequence on the LCD upon system startup.

📡 Working Principle:

When the system starts:

The LCD displays a sequence of welcome and contributor messages.

It clears the screen and waits for user input via serial.

When a user sends a character from an Android app (like a serial Bluetooth terminal), the Arduino interprets the character and:

Activates/deactivates the corresponding appliance.

Displays the current status on the LCD.

Control Commands:

'A' to 'F' turn ON Appliance 1 to 6 respectively.

'a' to 'f' turn OFF Appliance 1 to 6 respectively.

🔌 Hardware Components:

Arduino Uno or compatible board

Bluetooth module (HC-05/HC-06)

16x2 LCD Display

Relays or LEDs (6 outputs representing appliances)

Connecting wires and resistors

Android smartphone with Bluetooth terminal app

🧠 Software Components:

Arduino IDE

Serial Bluetooth Terminal App on Android (or any serial app)

Code written in C++ for Arduino

📺 LCD Display Usage:

Startup: Displays project name, institution, and contributors.

Control Mode: Displays appliance indicators like 1|2|3|4|5|6|GRP, with letters under each indicating their current state (A-F ON, a-f OFF).

🎓 Contributors Mentioned (LCD Display):

Project guided by: Dhirendra Sir & Rajendra Sir

Designed by: Pawan K. Maurya

Team Members: Aman Verma, Arvind Vishwakarma, Pradeep Kumar, Somil Kumar

✅ Applications:

Home appliance control (lights, fans, etc.)

Smart home systems

Elderly and disabled assistance

Energy management

🔄 Possible Improvements:

Add voice control using Google Assistant integration.

Use Wi-Fi (ESP8266/ESP32) for IoT-based remote control.

Add sensors (temperature, motion, etc.) for automation.

Use a more advanced user interface (Android app or webpage).

Output:
https://github.com/Srihari9215/HOME-AUTOMATION-WITH-BLUETOOTH/issues/1#issue-3325172713
