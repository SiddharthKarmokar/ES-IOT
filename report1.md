# **Smart Alarming IoT-Based System Using Raspberry Pi 4**

## **Message Transmission**

**Name:** Siddharth Karmokar  
**Roll No:** 123CS0061  

---

## **1. Introduction**
This project focuses on **message transmission** using **Blynk**, **Twilio**, and an **SPI TFT display** integrated with a **Raspberry Pi 4**. The system allows a user to send a message via the Blynk app, which is received by the Raspberry Pi, displayed on the **1.8" SPI TFT LCD**, and forwarded as an SMS using **Twilio API**. Challenges included setting up SPI communication, ensuring reliable message transmission, and handling delays in network communication. The implementation also required GPIO handling for LED notification upon message reception.

---

## **2. Components Used**
- **Raspberry Pi 4**
- **1.8" SPI TFT LCD (ST7735)**
- **Internet Connectivity (WiFi)**
- **Twilio Account for SMS transmission**
- **Blynk IoT Platform**
- **LED Indicator**
- **Power Supply (5V, 2.5A)**

---

## **3. System Architecture**
- **User inputs message** via the **Blynk mobile app**.
- **Raspberry Pi receives** the message and **displays it** on the **TFT screen**.
- The same message is **forwarded via Twilio** as an SMS to a designated phone number.
- An **LED blinks** to indicate message reception.
- The system ensures **real-time message transmission** using the **SPI protocol** for display and **Twilio API** for SMS.

---

## **4. Software and Tools Required**
- **Raspberry Pi OS (Debian-based)**
- **Python 3.9**
- **Blynk Python Library**
- **Twilio API**
- **Pillow (PIL) for Display Handling**
- **ST7735 Python Library for SPI TFT**
- **RPi.GPIO for GPIO Handling**

---

## **5. Circuit Diagram**
![Wiring Diagram](https://drive.usercontent.google.com/download?id=1sPbrtoW9kskKZEqlS0FZyknHI0w05ZPq&export=view&authuser=0)
