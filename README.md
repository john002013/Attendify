# Project Overview
Seamless real-time attendance tracking powered by cloud automation

A real-time RFID-based attendance system that automatically logs each scan to Google Sheets, supports dual operating modes (Attendance and Registration), prevents duplicate entries within the same day, and provides instant feedback to users. Designed for schools, labs, organizations, and events that need a simple but powerful attendance automation solution.
Attendify is an IoT-enabled attendance solution built to eliminate manual record-keeping and ensure accurate, real-time tracking. This system reads RFID cards and instantly synchronizes attendance data—including Name, UID, Time-In, and Time-Out—to a Google Sheet using cloud APIs.

It features two fully functional operating modes:

1. Attendance Mode: Reads RFID cards, logs attendance to Google Sheets, and prevents duplicate marking by notifying the user if they have already completed attendance for the day.
2. Registration Mode: Allows administrators to register new RFID cards, capturing user details and storing card information automatically.

Operators can switch between both modes using a physical switch, making the system highly flexible and easy to manage.

# Key Features

1. Real-Time Cloud Storage: Automatic synchronization of attendance to Google Sheets.
2. RFID-Based Identification: Fast and contactless card scanning.
3. Dual Operation Modes:

Attendance Mode — logs scans and prevents duplicates

Registration Mode — registers new users into the system

4. User Feedback System: Display prompts confirm successful registration or attendance.

5. Duplicate Detection: Prevents users from marking attendance more than twice in a single day.

6. Plug-and-Play Operation: Simple switching between modes using a hardware toggle.

7. Clean Data Logging: Stores Name, UID, Time-In, Time-Out, and attendance status.

# Tech Stack

1. RFID RC522 / MFRC522

2. ESP32

3. Switch button

3. LCD

4. Buzzer or LED indicators
