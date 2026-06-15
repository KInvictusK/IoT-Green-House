# IoT-Green-House
Link 3D Design: 
https://www.tinkercad.com/things/lWL874RG4mu-ergasia 

# IoT Smart Greenhouse Automation System

An open-source Smart Greenhouse automation and monitoring system designed to promote precision agriculture and resource sustainability. This project utilizes an Arduino Uno architecture to control microclimate, automate irrigation, and ensure perimeter security using various IoT sensors.

## 🌟 Features & Automation Subsystems

*   **Microclimate & Ventilation Control:** Monitors ambient temperature using a `TMP36` sensor. Automatically triggers a DC ventilation fan when temperatures exceed 30°C, displaying real-time data on an I2C LCD screen.
*   **Smart Irrigation:** Utilizes a **Soil Moisture Sensor** to prevent water waste. The automated water pump triggers only when soil moisture drops below 40%.
*   **Automated Supplemental Lighting:** Features an outdoor **Photoresistor (LDR)** with a 10kΩ voltage divider to dynamic-control an indoor 5-LED lighting array during low light conditions.
*   **Water Resource Monitoring:** Measures the water tank's level via an **HC-SR04 Ultrasonic Sensor**, calculating and rendering the remaining capacity (%) on a display.
*   **Perimeter Security & Access Control:** Features a 4x4 Keypad matrix and a **PIR Motion Sensor** for anti-intrusion security. Unauthorized movement or wrong passcodes trigger a piezo buzzer alarm.
*   **Gas & Air Quality Safety:** Integrated **Gas Sensor** to detect hazardous CO₂ accumulations inside the greenhouse, combined with an auditory alarm system.

---

## 📐 3D Design & Environment Architecture

The structural prototype was engineered using a contemporary arched tunnel form-factor. All automated nodes, control units, and water reservoirs are fully mapped in 3D.

| Internal Layout Overview | External Reservoir & Assembly |
| :---: | :---: |
| <img src="assets/" width="400"> | <img src="assets/" width="400"> |



---

## 🔌 Circuit Topology & Simulation Links

The firmware is written in **Wiring C / C++** and simulated on Arduino Uno boards.

1.  **Thermal Regulation:** [TinkerCAD Circuit](https://www.tinkercad.com/things/aru40slRLph-thermansi-psiksi)
2.  **Automated Irrigation:** [TinkerCAD Circuit](https://www.tinkercad.com/things/fW2cB100X4d-potisma)
3.  **LDR Supplemental Lights:** [TinkerCAD Circuit](https://www.tinkercad.com/things/frNiAxCoHg7-fota)
4.  **Ultrasonic Level Tracking:** [TinkerCAD Circuit](https://www.tinkercad.com/things/5HCwQGeWnx2-deksameni-nerou)
5.  **Secure Keypad System:** [TinkerCAD Circuit](https://www.tinkercad.com/things/3gyZGkJXEvb-codelock)
6.  **Gas Isolation Safety:** [TinkerCAD Circuit](https://www.tinkercad.com/things/3khtqnspBEQ-esthitiras-aeriou)

---

## 🛠️ Hardware Requirements
*   Arduino Uno R3 Mircocontroller
*   TMP36 Temperature Sensor / Soil Moisture Sensor / Photoresistor (LDR)
*   HC-SR04 Ultrasonic Sensor / PIR Motion Sensor / MQ Gas Sensor
*   16x2 LCD Display (I2C Module)
*   4x4 Keypad Matrix
*   DC Motors (Pump & Fan simulation) & Piezo Buzzers
*   Resistors (10kΩ, 220Ω), LEDs, and Breadboard jumper wires.

## 👥 Contributors
*   **Charisios Mousios**: sirxarisios
*   Kosmas Karagkoulas: KInvictusK
*   Konstantinos Dedousis: dedoukwsta-cloud
