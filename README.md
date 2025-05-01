# ESP32-MOTORCYCLE-ECU

An open-source fuel control system designed for small-displacement motorcycles using the ESP32 microcontroller. This project manages fuel injection based on real-time engine data and is ideal for DIY EFI experiments, student projects, or performance upgrades.

## 🚀 Features

- Real-time fuel injection control via ESP32 (MicroPython)
- Compatible with standard motorcycle sensors
- Fuel map stored in EEPROM for persistent tuning

## 🔧 Hardware Requirements

- **Microcontroller**: ESP32 or ESP32-S3
- **Injector**: Yamaha Mio J series
- **Sensors** (VEGA Force FI compatible):
  - Manifold Air Pressure (MAP)
  - Intake Air Temperature (IAT)
  - Throttle Position Sensor (TPS)
- **Power Supply**: 12V DC motorcycle battery (with proper regulation)

## 🎯 Project Scope

This ECU system is **fuel-only** — it does **not** control ignition timing. The system is focused on:
- Stable and tunable fuel delivery
- Learning platform for EFI concepts
- Integration into existing motorcycles without altering ignition

## ⚠️ Disclaimer

Use at your own risk. This system is meant for learning, testing, and controlled environments. Always verify fuel delivery and engine behavior before running full load or long durations.

---
