# Project_Draupadi
🔎 Problem Statement

In emergencies, especially for women’s safety, the time taken to reach out for help can be the difference between safety and harm.
- Victims often struggle to contact trusted people or police quickly.
- Existing solutions (apps or panic buttons) may fail due to network dependency, lack of accessibility, or slow manual response.
- There is a need for a fast, reliable, and affordable safety system that works even in critical situations.

💡 Our Solution

Project Draupadi is a Women’s Safety and Emergency Alert System developed for Smart India Hackathon 2025.
It provides a dual-alert mechanism combining hardware + software for maximum reliability.
1. Trigger Device (Hardware):
- A small, affordable device (button/sensor-based) that the victim can press in emergencies.
- Designed to be portable and cost-effective, so it can be widely adopted.

2. Software System (App + Backend):
- On trigger, the device communicates with a Flask-based backend.
- The backend immediately sends alerts to:
  - Pre-selected trusted contacts (Krishna network)
  - Authorities/police stations

3. Alerts Include:
- GPS location of the victim
- Timestamp
- Optional medical or identification details

🌟 Key Features

- Dual Alerts: Ensures both personal contacts and authorities are informed.
- Real-time GPS: Accurate location sharing for faster rescue.
- Low-Cost Hardware: Economical design so anyone can afford it.
- Scalable System: Can integrate with future technologies (AI, IoT, cloud).
- User-Friendly: One-button trigger, no complicated setup needed.

🏗 Architecture

- Hardware Module: Trigger button + microcontroller (ESP32/Arduino).
- Firmware: Connects device to backend API.
- Backend (Flask): Handles alert requests, stores data, routes notifications.
- Frontend (React + Tailwind): For registration, settings, and monitoring.
- Database (MySQL/SQLite): Stores user info, contact details, and logs.

🎯 Impact

- Empowers individuals by giving them a simple way to seek help.
- Faster response times by notifying both family and police simultaneously.
- Economically accessible so it can be deployed at scale in urban and rural areas.
- Contributes towards safer communities and supports national women’s safety initiatives.
