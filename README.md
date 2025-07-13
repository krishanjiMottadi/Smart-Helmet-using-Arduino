# Smart-Helmet-using-Arduino-and-RF-Module
Simple smart helmet using the RF Module

# Smart Helmet using Arduino 🚀

A safety-focused Smart Helmet system that integrates multiple sensors and modules using Arduino to enhance rider security and accident response.

## 🧠 Key Features

- 🪖 **Helmet Detection** – Uses an IR sensor to verify if the helmet is being worn.
- 🍺 **Alcohol Detection** – MQ3 sensor checks for alcohol presence near the mouth region.
- 💥 **Accident Detection** – Vibration sensor detects sudden impacts/crashes.
- 🚦 **Ignition Control** – Bike ignition system controlled through safety checks.
- 📱 **Emergency Alert System** – Sends SMS to emergency contact using GSM module upon accident detection.

## 🛠️ Hardware Components

- Arduino UNO
- MQ3 Alcohol Sensor
- IR Sensor
- Vibration Sensor
- GSM Module (SIM800L/SIM900A)
- Relay Module
- Battery & Buzzer
- Connecting Wires, Helmet

## 💡 How It Works

1. **Helmet Status Check**: The IR sensor inside the helmet detects whether it is worn.
2. **Alcohol Check**: MQ3 detects alcohol vapor from breath.
3. **Start Authorization**: Only if both checks pass, the relay turns ON, allowing the bike to start.
4. **Crash Detection**: Vibration sensor identifies abrupt impacts.
5. **Emergency Alert**: GSM module sends an SMS to a preset contact with an accident alert.

## 🚀 Getting Started

To replicate this project:

1. Clone or download this repository.
2. Connect hardware as per the circuit diagram.
3. Upload the Arduino sketch using the Arduino IDE.
4. Insert a SIM card in the GSM module.
5. Power the circuit and test the functionality.


## 🧠 Future Improvements

- Add a GPS module for real-time location tracking
- Integrate IoT (e.g., Blynk or Firebase) for live status monitoring
- Add a voice feedback module or an LCD for alerts

## 🧑‍💻 Author

**M. Krishnaji**  
- [GitHub](https://github.com/krishanjiMottadi)  

## 📜 License

This project is licensed under the MIT License.

---

> ⚠️ *Note: This project is a prototype and should be further developed and tested for real-world deployment.*
