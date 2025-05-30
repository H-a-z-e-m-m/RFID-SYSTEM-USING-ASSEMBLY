# RFID Attendance System using PIC16F877A

This project is a simple but efficient RFID-based attendance system built using the **PIC16F877A microcontroller**, an **RDM6300 RFID reader**, and a **16x2 LCD display**. Written entirely in **Assembly**, the system reads RFID tags via UART, verifies the input, checks the checksum, and displays the user’s unique ID on the LCD.

---

-- Features

-  Displays UID on **16x2 LCD**
-  Communicates with **RDM6300 RFID Reader via UART**
-  **Checksum verification** for secure data integrity
-  Detects valid/invalid tags
-  Built for educational and real-world use cases
-  Fully written in **Assembly language**

---

-- Hardware Used

-  PIC16F877A Microcontroller
-  RDM6300 RFID Reader (125kHz)
-  LCD 16x2 Display
-  Breadboard + Jumper Wires
-  5V Power Supply

---

-- How It Works

1. System waits for RFID input from RDM6300 via UART.
2. Incoming data is stored and **checksum is calculated**.
3. If checksum is valid, the UID is extracted and shown on the **LCD**.
4. Invalid data is discarded or flagged.
5. Optional: You can expand this to include EEPROM logging or time-based attendance.

---

-- Development Info

-  Written in **Assembly Language**
-  Developed using **MPLAB X IDE**
-  Simulated using **Proteus** (optional)
-  Implemented on PIC16F877A and RDM6300 RFID Sensor.
-  UART configured at 9600 baud rate (RDM6300 default)


