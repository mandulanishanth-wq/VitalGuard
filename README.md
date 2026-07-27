# VitalGuard

**A smart wearable device that continuously monitors vital health parameters and detects falls using multiple sensors integrated with an ESP32 microcontroller.**

VitalGuard sends real-time health data and emergency alerts to caregivers through an IoT platform, enabling remote monitoring and timely medical assistance for elderly individuals.

🔗 **Live Demo:** [https://mandulanishanth-wq.github.io/VitalGuard/](https://mandulanishanth-wq.github.io/VitalGuard/)

---

## 📖 Overview

Elderly and chronically ill individuals often live alone or in low-resource settings where continuous medical supervision isn't practical. VitalGuard aims to close that gap with an affordable, wearable device that:

- Continuously monitors key vital signs
- Detects falls in real time using an accelerometer
- Sends instant alerts to caregivers when something looks abnormal
- Provides remote, real-time visibility into a patient's health status

## ✨ Features

- **Continuous vitals monitoring** — tracks health parameters such as heart rate and body temperature
- **Fall detection** — identifies sudden falls using motion sensor data
- **Real-time alerts** — notifies caregivers immediately when abnormal readings or a fall is detected
- **IoT-connected** — streams live data to a cloud/IoT platform for remote monitoring
- **ESP32-powered** — compact, low-power microcontroller suited for a wearable form factor

## 🛠️ Tech Stack

- **Microcontroller:** ESP32
- **Sensors:** Pulse/heart-rate sensor, temperature sensor, accelerometer (fall detection)
- **Connectivity:** Wi-Fi
- **Platform:** IoT/cloud dashboard for real-time data visualization and alerts

> Update this section with the exact sensors, libraries, and services your build uses.

## 🚀 Getting Started

### Prerequisites

- ESP32 development board
- Compatible vitals/motion sensors (as listed above)
- Arduino IDE or PlatformIO
- Wi-Fi network for connectivity
- Account/credentials for your chosen IoT/cloud platform

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/mandulanishanth-wq/VitalGuard.git
   cd VitalGuard
   ```
2. Open the firmware project in the Arduino IDE or PlatformIO.
3. Install the required libraries for your sensors and IoT platform.
4. Update your Wi-Fi and IoT platform credentials in the configuration file.
5. Flash the firmware to your ESP32 board.
6. Power on the device and confirm it connects to your dashboard/IoT platform.

## 📊 Usage

Once powered on and connected, VitalGuard continuously reads sensor data and streams it to the connected IoT platform. Caregivers can view live vitals on the dashboard, and the system automatically triggers an alert if a fall is detected or vitals fall outside a safe range.

## 🗺️ Roadmap

- [ ] Add support for additional vitals (e.g., SpO2, ECG)
- [ ] Mobile app for caregivers with GPS tracking
- [ ] AI-based anomaly detection
- [ ] Secure authentication for caregiver/doctor dashboards

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with improvements, bug fixes, or new features.

## 📄 License

This project is open source. Add your preferred license (e.g., MIT) here.

## 📬 Contact

For questions or feedback, open an issue on this repository.
