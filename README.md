# IoT-Based Automated Grain Drying and Rain Protection System

## 📌 Project Overview

The **IoT-Based Automated Grain Drying and Rain Protection System Using Telegram Alerts** is a smart agriculture project designed to reduce grain loss caused by unexpected rain, excess moisture, and other crop-related risks.

The system uses sensors to monitor environmental conditions such as **rain, soil moisture, temperature, humidity, animal movement, and fire**. Based on the sensor readings, the system automatically controls drying, rain protection, irrigation, and safety mechanisms.

The system also sends real-time notifications to the farmer through **Telegram**, allowing remote monitoring of important events.

---

## 🎯 Objectives

- Automate the grain drying process based on environmental conditions.
- Protect grains from unexpected rainfall using an automated cover.
- Monitor soil moisture and automate irrigation when required.
- Detect animal movement near the crop area.
- Detect fire-related hazards.
- Send real-time alerts and system updates through Telegram.
- Reduce manual monitoring and improve crop safety.

---

## ⚙️ How the System Works

The system continuously collects information from different sensors and processes the readings through the microcontroller.

### 1. Rain Detection and Protection

The rain sensor detects rainfall conditions.

When rain is detected, the system automatically activates the motorized protective shield to protect the grains from rainwater.

### 2. Grain Drying

Temperature and humidity conditions are continuously monitored.

When high humidity is detected, the drying fan is activated to help reduce the moisture around the grains.

### 3. Irrigation

The soil moisture sensor monitors the moisture level.

When the soil moisture falls below the required threshold, the water pump is activated. The pump is stopped when the required moisture level is reached.

### 4. Animal Detection

A PIR motion sensor detects movement near the crop area.

When animal movement is detected, the system activates an alert and sends a notification to the farmer through Telegram.

### 5. Fire Detection

The fire sensor monitors the system for possible fire hazards.

When fire is detected, the buzzer is activated and an emergency notification is sent through Telegram.

### 6. Telegram Alerts

The system provides real-time Telegram notifications for important events such as:

- Rain detection
- Animal movement
- Fire detection
- System status
- Environmental conditions

---

## 🧩 Hardware Components

- ESP32 Microcontroller
- DHT11 Temperature and Humidity Sensor
- Rain Sensor
- Soil Moisture Sensor
- PIR Motion Sensor
- Fire Sensor
- DC Motors
- Water Pump
- Drying Fan
- Buzzer
- LCD Display
- Relay Module
- L298N Motor Driver
- Limit Switches

---

## 💻 Software and Technologies

- Arduino / ESP32
- Embedded C/C++
- Telegram Bot API
- ThingSpeak
- Arduino IDE

---

## 🌱 Main Features

- Automated grain drying
- Automatic rain protection
- Soil moisture-based irrigation
- Animal intrusion detection
- Fire detection
- Real-time Telegram notifications
- LCD-based status display
- IoT-based remote monitoring

---

## 🏗️ System Architecture

```text
             Sensors
                ↓
        ESP32 Microcontroller
                ↓
       Sensor Data Processing
                ↓
    ┌───────────┼────────────┐
    ↓           ↓            ↓
 Rain Sensor  Soil Moisture  Safety Sensors
    ↓           ↓            ↓
Rain Shield  Water Pump   Animal / Fire
    ↓           ↓            ↓
    └───────────┼────────────┘
                ↓
            Actuators
                ↓
       Telegram Notifications
                ↓
             Farmer

📊 Results

The developed system was tested for its major automated functions.

🌧️ Rain Protection

The rain sensor successfully detected rainfall conditions. When rain was detected, the protective shield was automatically deployed based on the system conditions. This helped protect the grains from direct exposure to rainwater.

A Telegram notification was also generated when rain was detected.

💧 Irrigation

The irrigation system responded to the soil moisture readings.

When the soil moisture level dropped below the defined threshold, the water pump was activated. The pump was turned off after the required moisture level was reached.

🌾 Grain Drying

The grain drying mechanism responded to high humidity conditions.

When the humidity level increased, the drying fan operated to help reduce the moisture surrounding the grains.

🐾 Animal Detection

The PIR motion sensor successfully detected movement near the crop area.

When movement was detected, the system generated an alert and sent a notification to the farmer through Telegram.

🔥 Fire Detection

The fire detection system successfully detected the presence of a flame.

When fire was detected:

The buzzer was activated.
An emergency notification was generated.
The farmer received an alert through Telegram.

📱 Telegram Notifications

Telegram was used for real-time communication between the system and the farmer.

The system provided notifications related to important events such as:

Rain detection
Animal movement
Fire detection
System activities
Environmental conditions
✅ Overall Result

The testing demonstrated that the proposed system could integrate grain drying, rain protection, irrigation, animal detection, fire detection, and Telegram-based notifications into a single automated agriculture system.

The project demonstrated the practical use of IoT-based sensing and automation for agricultural monitoring and crop protection.
