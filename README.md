# 🚘 Vision Guardian – Intelligent Driver Monitoring System

![test](https://github.com/user-attachments/assets/f1e73140-66ec-4b43-aa69-c4ee98295f02)
![lane](https://github.com/user-attachments/assets/2b458133-2dc7-44db-a3ae-4f7547422ee2)


## 📌 Project Overview

**Vision Guardian** is a smart, compact, and cost-effective system designed to reduce road accidents caused by driver fatigue and alcohol consumption. It uses real-time sensors and intelligent algorithms to monitor the driver's condition and take immediate safety actions, such as sounding alerts, stopping the vehicle, and sending emergency GPS coordinates.

---

## 🧠 Problem Statement

According to the Ministry of Road Transport and Highways (MoRTH) 2024 report:

- Over **1.55 lakh** people died in road accidents in 2022.
- **13%** of fatalities were due to drowsiness or driver inattention.
- **5,500+ deaths** were attributed to drunk driving.
- Most incidents occur late at night or early morning when fatigue is common.

---

## 🎯 Objectives

- Detect drowsiness and alcohol levels in real time.
- Alert or stop the vehicle when the driver is unfit.
- Send emergency location to predefined contacts.
- Provide affordable safety for both private and commercial vehicles.

---

## 🔧 Technologies Used

| Component              | Description                                 |
|------------------------|---------------------------------------------|
| NodeMCU ESP8266        | Microcontroller for data processing         |
| Eyeblink IR Sensor     | Detects drowsiness based on eye movement    |
| MQ3 Alcohol Sensor     | Detects alcohol level from driver’s breath  |
| GPS Module             | Tracks real-time vehicle location           |
| Buzzer + Relay Module  | Issues alerts and controls vehicle ignition |
| YOLO Algorithm (Future)| Detects fatigue using AI/ML vision models   |

---

## 🛠️ How It Works

1. **Eyeblink Sensor** tracks eye closure duration. If eyes stay closed too long, it triggers an alert.
2. **MQ3 Sensor** checks for alcohol levels in the breath.
3. If risk is detected:
   - **Buzzer** sounds a warning.
   - **Relay module** can disable the engine.
   - **GPS Module** sends real-time location to emergency contacts via cloud/server.
4. YOLO algorithm (planned) enhances fatigue detection using object detection:
Detection Score = P(Object) × IOU × Class Confidence
---

## 📦 Installation

1. Clone the repository:

git clone https://github.com/RajarajachozhanVK/Vision-Guardian-Intelligent-Driver-Monitoring-System-MAI125
Open the code in Arduino IDE and upload to NodeMCU ESP8266 / Arduino UNO

Connect:

IR Sensor to digital input
MQ3 to analog input
GPS Module via Serial (TX/RX)
Buzzer and Relay via digital outputs
Configure Wi-Fi and phone numbers for alerts (via code or dashboard if used).

🚨 Live Demo


🌐 Future Enhancements
AI-based fatigue detection using camera + YOLO.
Brainwave & heart rate monitoring.
Cloud dashboard for fleet-level emergency alerts.
Lane departure assist and thermal imaging.

🧩 SDG Alignment
SDG 3: Good Health and Well-Being
SDG 9: Industry, Innovation and Infrastructure
SDG 11: Sustainable Cities and Communities
SDG 13: Climate Action (through accident prevention & reduced traffic jams)

📸 Screenshots
![Architecture](https://github.com/user-attachments/assets/486a4ea4-5794-450f-989e-7e485daaeafe)
![Alert Output](https://github.com/user-attachments/assets/58d53501-8f30-43f9-98e1-c3ec03ef39fe)



🤝 Contributors
Raja Raja Chozhan V K – vtu18963@veltech.edu.in | vkrajarajachozhan@gmail.com
Raja Balamurugan - vtu18964@veltech.edu.in
Nandagopal J - vtu19087@veltech.edu.in


📜 License
MIT License — Feel free to use and modify this project for educational and non-commercial purposes.

💡 Acknowledgments
Vel Tech Institute, Avadi
MoRTH India for data insights
Arduino & open-source sensor libraries
