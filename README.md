# Duosecure

The DuoSecure Smart Locker System combines embedded systems and IoT technology to create a versatile and secure locker access solution. It integrates hardware components such as a keypad, LCD display, and ESP32 microcontroller, along with cloud-based mobile interaction using the Blynk IoT platform.

The system works in two modes:

Local Mode: Users can unlock the locker by entering a valid 4-digit PIN through the keypad. If the PIN matches the stored credentials, the ESP32 triggers the locking mechanism to open.
Remote Mode: Authorized users can unlock or lock the locker from anywhere via the Blynk mobile application, which communicates with the ESP32 through Wi-Fi, offering real-time control and monitoring.
An LCD display is included to show access status, system messages (like “Access Granted” or “Wrong PIN”), and to assist in user interaction.

Please check out Architecture :
https://drive.google.com/file/d/1inAd1YSvbMsr_4u6w2hbXuwnbocuQSX9/view?usp=sharing
and Code : From Github code file

Key Features:

Dual Authentication: Access via keypad or mobile app.
Secure PIN Verification: Validates user identity locally before unlocking.
Cloud Connectivity: Control and monitor locker status remotely using the Blynk app.
User Feedback: LCD provides clear instructions and status updates.
ESP32-based Control Unit: Acts as the central hub, managing all hardware and communication.

Technologies and Components Used:

Microcontroller: ESP32 (with built-in Wi-Fi)
User Interface: 4x4 Keypad for PIN entry
Display: 16x2 LCD for real-time feedback
IoT Platform: Blynk IoT App for mobile control
Programming Language: Embedded C/C++
Development Tools: Arduino IDE, Blynk Console

Hope you all like it, Thank you :)
