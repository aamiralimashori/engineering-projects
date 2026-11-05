# Engineering Projects

I'm Aamir Ali, an Electronic Engineering graduate from Mehran University of Engineering and Technology (MUET). This portfolio brings together my work in edge AI, assistive technology, embedded systems, and IoT.

[Portfolio](https://amiralimashori.pages.dev/) · [LinkedIn](https://www.linkedin.com/in/aamiralimashori/)

| Project | Focus |
| --- | --- |
| [BrailleGenAI](#braillegenai) | Assistive learning and edge AI |
| [RefriScan](#refriscan) | Embedded diagnostics and telemetry |
| [IoT Health Monitoring and Alert System](#iot-health-monitoring-and-alert-system) | Sensor acquisition and Wi-Fi monitoring |
| [Lights Automation Using Arduino](#lights-automation-using-arduino) | Motion-triggered lighting |
| [Edge NLP for Customer Feedback](#edge-nlp-for-customer-feedback) | Sentiment classification on edge devices |

## BrailleGenAI

**MUET final-year team project · October 2024–November 2025**

BrailleGenAI explores how a portable device can support Braille practice for blind learners. The project combined voice and image-based interaction with local AI processing on NVIDIA Jetson hardware. The design goals included spoken feedback, automatic grading, and progress records.

- **Hardware explored** — NVIDIA Jetson AGX Orin 64 GB and Jetson Nano 2 GB and 4 GB.
- **Recognition** — EPICS in IEEE project funding and second place at the 2025 MUET departmental final-year project exhibition.

[EPICS in IEEE project page](https://epics.ieee.org/project/braillegenai-empowering-braille-learning-with-edge-ai-and-voice-interaction-pakistan/)

## RefriScan

**Dawlance graduate traineeship · April–September 2026**

RefriScan was an ESP32-S3 project for refrigerator diagnostics and control-board testing. The work involved decoding UART telemetry, tracking equipment state, forwarding readings to Node-RED, and working with service-mode controls. The project also used I²C.

This case study covers the system at a high level.

## IoT Health Monitoring and Alert System

**MUET team project · March–May 2024**

This educational prototype combines local sensor display with remote telemetry. The course report describes an Arduino Uno R3 reading an LM35 temperature sensor and a fingertip pulse sensor, then displaying readings on a 16×2 LCD. An ESP8266 provides Wi-Fi connectivity for telemetry. A red LED serves as a local indicator when a reading crosses a configured threshold.

- **Signal flow** — LM35 and pulse sensor → Arduino Uno → LCD, LED, and ESP8266 Wi-Fi module.
- **Portfolio tools** — ThingSpeak and MicroPython are also listed in my portfolio. The course report describes the Arduino and ESP8266 hardware design.
- **Scope** — Classroom prototype for sensor acquisition, telemetry, and alert logic. Clinical validation would be required for patient use.

## Lights Automation Using Arduino

**MUET Measurements and Instrumentation team project · March–April 2023**

An Arduino Uno reads a passive infrared (PIR) motion sensor on digital pin 8 and switches a light through an active-low relay. When the PIR output is HIGH, the Arduino drives the relay input LOW and turns the light on. When the PIR output goes LOW, the Arduino drives the relay input HIGH and turns the light off.

A PIR sensor responds to motion, so a person sitting still can be missed once the sensor output returns LOW.

## Edge NLP for Customer Feedback

**Edge AI project · October 2025**

This project explored offline sentiment classification for customer feedback using Python and TensorFlow. It used GloVe word embeddings as inputs to a compact one-dimensional convolutional neural network (1D CNN).

## Repository contents

This repository contains project documentation. Original firmware, model files, and reproduction instructions are pending. Each project section can be updated here as code, diagrams, and demos become available for release.
