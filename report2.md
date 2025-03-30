# **IoT-Based Morse Code Transmission System Using Raspberry Pi 4**

## **Morse Code Messaging**

**Name:** Siddharth Karmokar  
**Roll No:** 123CS0061  

---

## **1. Introduction**
This project implements a **Morse code messaging system** using a **touch sensor**, **Blynk**, and **Twilio** on a **Raspberry Pi 4**. The system allows a user to input Morse code using a **touch sensor**, which is then translated into readable text and sent via **Blynk** and **Twilio SMS**. Challenges included accurately detecting touch durations, ensuring proper Morse code decoding, and handling transmission delays. The implementation also required careful GPIO handling for real-time input capture.

---

## **2. Components Used**
- **Raspberry Pi 4**
- **Touch Sensor (Capacitive or Mechanical)**
- **Internet Connectivity (WiFi)**
- **Twilio Account for SMS transmission**
- **Blynk IoT Platform**
- **Power Supply (5V, 2.5A)**

---

## **3. System Architecture**
- The **user inputs Morse code** via a **touch sensor**.
- The Raspberry Pi **decodes** the Morse code into **readable text**.
- The **decoded text is sent** to the **Blynk app** for display.
- The same message is also **forwarded via Twilio** as an SMS to a designated phone number.
- The system ensures **real-time input detection** and **accurate Morse code translation**.

---

## **4. Software and Tools Required**
- **Raspberry Pi OS (Debian-based)**
- **Python 3.9**
- **Blynk Python Library**
- **Twilio API**
- **RPi.GPIO for GPIO Handling**

---

## **5. Morse Code Reference Table**

| Morse Code | Character |
|------------|-----------|
| .-         | A         |
| -...       | B         |
| -.-.       | C         |
| -..        | D         |
| .          | E         |
| ..-.       | F         |
| --.        | G         |
| ....       | H         |
| ..         | I         |
| .---       | J         |
| -.-        | K         |
| .-..       | L         |
| --         | M         |
| -.         | N         |
| ---        | O         |
| .--.       | P         |
| --.-       | Q         |
| .-.        | R         |
| ...        | S         |
| -          | T         |
| ..-        | U         |
| ...-       | V         |
| .--        | W         |
| -..-       | X         |
| -.--       | Y         |
| --..       | Z         |
| -----      | 0         |
| .----      | 1         |
| ..---      | 2         |
| ...--      | 3         |
| ....-      | 4         |
| .....      | 5         |
| -....      | 6         |
| --...      | 7         |
| ---..      | 8         |
| ----.      | 9         |

---

