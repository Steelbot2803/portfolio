---
title: Water Level Automation System
summary: Building an Arduino-based IoT water automation system with WiFi control, dry-run protection, and a Flutter app for real-time monitoring and override.
# tags:
#  - NLP
date: 2025-08-06
draft: false
# external_link: ''
---

Currently developing a smart water level automation system powered by the Arduino Uno R4 WiFi, designed to automate water tank filling, prevent pump failures, and provide remote access via a custom mobile app.

The system uses float switches to monitor tank levels and current sensors to detect pump dry-run conditions. It intelligently controls a primary and backup pump, automatically switching or disabling them based on sensor input. Manual override buttons mounted near the Arduino allow local control without relying on network access.

WiFi communication between the Arduino and a Flutter-based mobile app enables real-time updates on water levels and pump status, while also allowing users to send commands—like toggling pumps or switching modes—remotely. The app is designed with a responsive UI and minimal latency for seamless interaction.

Currently in the prototyping phase, this project combines embedded system design, IoT architecture, and Flutter frontend development to build a robust, user-friendly solution for household and apartment-level water automation. The system emphasizes fault tolerance, user feedback, and remote accessibility.