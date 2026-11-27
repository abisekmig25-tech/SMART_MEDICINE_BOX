# 💊 SmartMed Box – IoT-Based Smart Medicine Reminder System

An ESP32-powered smart medicine reminder system designed to help users manage their daily medication schedules through automated reminders, real-time notifications and intelligent compartment access.

SmartMed Box integrates IoT technology, a web-based interface, an OLED display and an automated medicine dispensing mechanism to make medication management easier and more organized.

---

## 🚀 Project Overview

Remembering to take medicines at the correct time can be challenging, especially for people managing multiple medications throughout the day.

**SmartMed Box** aims to solve this problem by providing an automated and customizable medicine reminder system.

Users can configure medicine names, dosage information and medication schedules through a web interface without modifying or recompiling the ESP32 firmware.

When a scheduled medication time arrives, the system displays the medicine information on an OLED screen, activates a buzzer alert and sends a notification through Telegram.

An automated solenoid-based mechanism provides controlled access to the medicine compartment.

---

## ✨ Key Features

### 1. 📅 Customizable Medicine Scheduling
- Add and manage medicine names.
- Configure medication timings.
- Set the number of tablets required.
- Update schedules through a web interface.
- No need to recompile ESP32 firmware whenever medication details change.

### 2. 🌐 Web-Based Management
- User-friendly web interface.
- Remotely configure medication information.
- Update medicine schedules dynamically.
- Communicate with the ESP32 through an IoT-based backend.

### 3. 📟 OLED Display
- Displays the current medicine name.
- Shows the required number of tablets.
- Provides information about upcoming medication reminders.
- Displays system status.

### 4. 🔔 Smart Reminder System
- Buzzer alerts when medication is due.
- Visual indication through LEDs.
- Displays medication information when an alert is triggered.

### 5. 📱 Telegram Notifications
- Sends medication reminder notifications through Telegram.
- Provides remote notification access.
- Helps users stay informed about scheduled medication times.

### 6. ⚙️ Automated Medicine Compartment
- Uses a solenoid-based mechanism for controlled compartment access.
- Activates according to the medication reminder logic.
- Designed to provide convenient access to scheduled medication.

### 7. 🔄 Medication Queue Management

Displays a waiting status when no medication is currently due.

Presents the current scheduled medicine when its time arrives.

Allows the user to acknowledge the current medication.

Advances to the next scheduled medication after the current one is marked as taken.

🛠️ Hardware Components

Component

Purpose

ESP32-WROOM-32

Main microcontroller

0.96-inch OLED Display

Displays medicine information

Buzzer

Audio medication reminders

LED

Visual status indication

Solenoid

Automated compartment mechanism

MOSFET Driver Circuit

Controls the solenoid

Flyback Diode

Protects the solenoid driver circuit

USB-C Power Input

Main power supply

Custom PCB

Integrates the electronic components

Additional supporting components include resistors, capacitors, connectors and power-management components.
