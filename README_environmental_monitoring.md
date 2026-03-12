# Environmental Monitoring using ESP32

## 📌 Project Overview

This project presents a **real-time environmental monitoring system**
using the ESP32 microcontroller. The system measures **temperature,
humidity, and air quality** using sensors and helps monitor
environmental conditions in indoor or outdoor environments.

The system uses: - ESP32 microcontroller - DHT11 sensor for temperature
and humidity - Smoke/Gas sensor for air quality detection

The collected data can be processed and transmitted wirelessly using the
ESP32's built‑in **Wi‑Fi and Bluetooth capabilities**.

------------------------------------------------------------------------

## 🎯 Objectives

-   Monitor environmental conditions in real time
-   Measure **temperature and humidity**
-   Detect **smoke or harmful gases**
-   Provide a **low‑cost and efficient monitoring solution**
-   Enable **wireless data communication** using ESP32

------------------------------------------------------------------------

## 🧰 Components Used

| Component \| Description \|

\|-----------\|-------------\| ESP32 \| Main microcontroller for data
processing and communication \| \| DHT11 Sensor \| Measures temperature
and humidity \| \| Smoke Sensor \| Detects smoke and harmful gases \| \|
Jumper Wires \| Connections between components \| \| Power Supply \|
Provides required voltage \| \| Breadboard \| For circuit prototyping \|

------------------------------------------------------------------------

## ⚙️ System Architecture

The system works by collecting environmental data from sensors connected
to the ESP32.\
The ESP32 processes the sensor readings and can transmit the data
wirelessly for monitoring purposes.

Basic workflow:

1.  Sensors collect environmental data
2.  ESP32 reads sensor values
3.  Data is processed by the microcontroller
4.  Information is transmitted or displayed

------------------------------------------------------------------------

## 🔌 Circuit Connection

Typical connections:

-   **DHT11 Data Pin → ESP32 GPIO**
-   **Smoke Sensor Output → ESP32 Analog/Digital Pin**
-   **VCC → 3.3V/5V**
-   **GND → GND**

------------------------------------------------------------------------

## 🚀 How to Run the Project

1.  Install **Arduino IDE**
2.  Add **ESP32 board support**
3.  Connect ESP32 to your computer
4.  Upload the program code
5.  Open **Serial Monitor** to view sensor readings

------------------------------------------------------------------------

## 📊 Applications

-   Smart homes
-   Industrial safety monitoring
-   Air quality monitoring systems
-   Environmental research
-   IoT-based monitoring systems

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Add **IoT cloud integration**
-   Mobile app for monitoring
-   Data logging and analytics
-   Additional sensors (CO2, dust, etc.)

------------------------------------------------------------------------

## 👨‍💻 Authors

-   R. Rohith\
-   E. Vamshi\
-   S. Surender Reddy\
-   S. Naga Vamsi

Department of **Electronics and Communication Engineering**\
KL Deemed to be University, Hyderabad

------------------------------------------------------------------------

## 📄 License

This project is created for **academic purposes**.
