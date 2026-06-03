# Mallesh S 👋

I am an **Embedded Systems & IoT Developer** and **Full-Stack Engineer** specializing in bridging the gap between hardware edge computing and modern cloud ecosystems. I design and build edge architectures (ESP32, microcontrollers), telemetry processing networks (WebSockets, HTTP, I2C), and high-fidelity cloud dashboards.

---

## 🛠️ Technical Competencies

- **Embedded Systems & IoT**: C/C++, ESP32, 8051 Microcontrollers, Keil C51, WebSockets, I2C, SPI protocols
- **Hardware Design & HDL**: Verilog HDL, Xilinx Vivado, LTspice simulation
- **Web & Backend**: JavaScript (React, ES6+), HTML5, CSS3 (TailwindCSS), Node.js (Express.js), Python (Flask)
- **Cloud & Databases**: Firebase Realtime Database & Firestore, PostgreSQL, RESTful APIs, Git

---

## 🚀 Featured Engineering Projects

### 🏃‍♂️ [Real-Time Athlete Monitoring Dashboard](https://github.com/mallesh7040-droid/Athlete-Monitoring-Dashboard)
A dual-tier Internet of Things (IoT) ecosystem designed to stream and visualize live athletic biometric and movement data.
* **Edge Hardware**: ESP32 core controller processing **MPU6050** IMU (motion, squat count, fall detection) and **MAX30102** PPG (Heart Rate and SpO2 vital signs) sensors.
* **Architecture**: Direct local WebSocket connection (Vanilla HTML5/CSS3/Chart.js) combined with a production-grade full-stack Node.js gateway and React cloud client.
* **Key Features**: Auto-reconnect with exponential backoff, real-time rolling statistics, and local CSV/JSON telemetry data exporter.
* **Source Code**: [Athlete-Monitoring-Dashboard Repo](https://github.com/mallesh7040-droid/Athlete-Monitoring-Dashboard)

### 💊 [PharmaCare - POS & Pharmacy Management System](https://github.com/mallesh7040-droid/PharmaCare)
A premium Pharmacy Management & Point-of-Sale (POS) System with a sleek glassmorphic dashboard interface.
* **Tech Stack**: React, Vite, Tailwind CSS, Zustand (state management), and Firebase Firestore.
* **Key Features**: Real-time sales KPIs, automated packaging converters, drug scheduling brackets (OTC, Schedule H/X/G), and print-ready tax invoice generation.
* **Live Demo**: [tk-pharma-connect.netlify.app](https://tk-pharma-connect.netlify.app/)
* **Source Code**: [PharmaCare Repo](https://github.com/mallesh7040-droid/PharmaCare)

### 🧠 [Aether Med App (AI Tumor Detection Monorepo)](https://github.com/mallesh7040-droid/Aether-med-app)
A full-stack medical analysis platform designed to parse MRI/CT scans and provide brain tumor classification.
* **Frontend**: Single Page Application using `cornerstone-core` and `dicom-parser` to parse and render 16-bit diagnostic `.dcm` files directly on browser canvas frames.
* **Backend**: Flask API gateway supporting dual-channel parsing (accepts both JSON base64 payloads and traditional `multipart/form-data` uploads).
* **AI Integration**: Connects with **Google Gemini AI** to act as a patient-friendly diagnostic explainer.
* **Source Code**: [Aether-Med-App Repo](https://github.com/mallesh7040-droid/Aether-med-app)

### 🔌 [Telemetry Data Gateway](https://github.com/mallesh7040-droid/sense-backend)
A Node.js/Express.js gateway server designed to route incoming edge data packages to cloud services.
* **Role**: Acts as the cloud gateway for the Athlete Monitoring ESP32, accepting HTTP POST payloads and pushing them directly to Firebase Realtime Database.
* **Source Code**: [Telemetry Data Gateway Repo](https://github.com/mallesh7040-droid/sense-backend)

---

## 💼 Professional Experience

### **Hardware & FPGA Design Intern** | *CSIR Lab*
- Engineered Verilog HDL modules for digital signal processing, including baseline correction and signal filtering stages.
- Validated RTL architectures using Xilinx Vivado, optimizing logic utilization and resource constraints for custom signal preprocessing boards.

### **IoT Systems Engineer Intern** | *Sensor Technology Lab*
- Configured local WebSocket servers on ESP32 microcontrollers to stream raw biometric sensor data (MAX30102 & MPU6050) to local web sockets.
- Designed rolling filter algorithms to smooth noisy photoplethysmogram (PPG) waveforms, improving visual chart stability.

### **Systems Observer Intern** | *Chennai Metro Rail Limited (CMRL)*
- Studied industrial metro signaling systems, passenger information systems, and core fiber-optic communications infrastructure.

---

## 📬 Connect With Me

- **Email**: [mallesh7040@gmail.com](mailto:mallesh7040@gmail.com)
- **LinkedIn**: [Mallesh S](https://linkedin.com) *(Update with your direct LinkedIn URL)*
- **GitHub**: [@mallesh7040-droid](https://github.com/mallesh7040-droid)
