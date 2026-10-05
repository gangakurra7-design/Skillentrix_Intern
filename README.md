# Skillentrix_Intern
An Arduino-based Light Intensity Measurement System that uses an LDR (photoresistor) to detect ambient light levels. The Arduino Uno processes the sensor's analog value and displays the ADC reading and light status (DARK, NORMAL, or BRIGHT) on a 16×2 LCD, with LED indicators for visual feedback. Designed and simulated using Tinkercad.
# 💡 Light Intensity Measurement System

## 📌 Project Overview

The Light Intensity Measurement System is an Arduino-based embedded system designed to detect and monitor ambient light intensity using an LDR (Light Dependent Resistor).

The LDR senses the surrounding light and produces an analog signal. The Arduino Uno reads and processes this signal, then displays the ADC value and corresponding light condition on a 16×2 LCD. LED indicators provide visual feedback for different light levels.

---

## 🎯 Objectives

- Measure the intensity of surrounding light.
- Read and process the analog output from an LDR.
- Display the measured ADC value on an LCD.
- Classify the light condition as DARK, NORMAL, or BRIGHT.
- Provide visual indication using LEDs.
- Understand sensor interfacing with a microcontroller.

---

## 🛠️ Components Used

| Component | Quantity | Purpose |
|-----------|----------|---------|
| Arduino Uno | 1 | Main microcontroller |
| LDR / Photoresistor | 1 | Detects light intensity |
| 16×2 LCD Display | 1 | Displays ADC value and status |
| LEDs | 3 | Visual indication |
| Resistors | As required | Current limiting and sensor circuit |
| Breadboard | 1 | Circuit assembly |
| Jumper Wires | As required | Electrical connections |

---

## ⚙️ Working Principle

The LDR changes its resistance according to the amount of light falling on it.

1. The LDR senses the surrounding light intensity.
2. The sensor circuit produces an analog voltage.
3. Arduino Uno reads this voltage through its analog input.
4. The Arduino converts the sensor signal into an ADC value.
5. Based on predefined threshold values, the system identifies the condition as:
   - 🌑 DARK
   - 💡 NORMAL
   - ☀️ BRIGHT
6. The ADC value and light status are displayed on the 16×2 LCD.
7. LEDs provide additional visual indication.

---

## 🔌 Hardware Setup

The main components are connected as follows:

- **LDR** → Arduino analog input
- **16×2 LCD** → Arduino digital pins
- **LEDs** → Arduino digital output pins through resistors
- **Arduino Uno** → Power and control unit
- Components are assembled on a breadboard.

---

## 💻 Technologies Used

- Arduino Uno
- Embedded Systems
- C/C++ (Arduino Programming)
- Analog Sensor Interfacing
- LCD Interfacing
- Tinkercad Circuits

---

## 🖥️ Output

The LCD displays the sensor's ADC value along with the detected light condition.

### Example:

```text
ADC: 6
Status: DARK
