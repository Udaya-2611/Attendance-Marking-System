Attendance Marking System

Description

The RFID Attendance Marking System is an automated solution that records attendance using RFID cards. Each card has a unique ID, which is read by the system and logged when scanned, improving accuracy and reducing manual effort.

Features

* RFID-based attendance
* Fast and contactless system
* Reduces manual errors
* Unique ID verification
* Real-time attendance display

Components Used

* Arduino UNO
* MFRC522 RFID Module
* RFID Cards/Tags
* LCD 16*2 Display
* Jumper Wires

How It Works

1. RFID reader scans the card
2. Arduino reads the UID
3. System verifies the card
4. Attendance is marked and displayed

How to Run

1. Connect RFID module to Arduino
2. Upload the code
3. Open Serial Monitor
4. Scan RFID card

Connections

* SDA → Pin 10
* SCK → Pin 13
* MOSI → Pin 11
* MISO → Pin 12
* RST → Pin 9
* VCC → 3.3V
* GND → GND

Project Structure

* `attendance.ino` → Arduino code
* `README.md` → Documentation

Future Improvements

* Store attendance in database
* Add LCD display
* Integrate IoT (cloud storage)
* Mobile app integration
