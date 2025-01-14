
# Fire Detection and Alarm System

## Project Aim
The aim of this project is to detect fire using an infrared (IR) sensor and trigger a signal or alarm as a warning.

---

## Tools Used
- Breadboard
- Transistor (PNP type)
- Power Supply
- LED Light
- 10-Ohm Resistor
- Buzzer
- Connecting Wires

---

## Working Principle
This project utilizes an IR receiver as a sensor connected to the base pin of a transistor. The combination of the sensor and the transistor acts as a switch.  
- Fire emits infrared rays, and when these rays fall on the IR receiver, it conducts a small current from the positive terminal to the transistor's base, triggering the alarm.

---

## Circuit Diagram
[Include the circuit diagram as an image file here.]

---

## Theory

### A. IR Detector/Sensor
An **Infrared Sensor (IR sensor)** is a radiation-sensitive optoelectronic component with a spectral sensitivity in the infrared wavelength range (780 nm to 50 µm).  
IR sensors are commonly used in:
- Motion detectors to switch on lights.
- Alarm systems to detect intruders.

### B. Transistor
A **Transistor** is a semiconductor device used for amplifying or switching electrical signals.  
- It consists of three terminals: **Emitter**, **Base**, and **Collector**.
- This project uses a **PNP Transistor**, where:
  - Majority charge carriers are **holes**.
  - The emitter emits holes, which are collected at the collector.
  - The base current is amplified when entering the collector.

---

## Connections
1. Connect the **collector terminal** of the transistor to the **negative terminal** of the buzzer and the resistor.
2. Connect the **emitter terminal** of the transistor to the ground.
3. Connect the **base terminal** of the transistor to the **positive terminal** of the IR sensor.
4. Connect the **negative terminal** of the IR sensor to the **positive terminal** of the LED and then to the **positive terminal** of the buzzer.
5. Connect the **negative terminal** of the LED to the resistor.
6. Provide power supply:
   - **Negative terminal** to the IR sensor.
   - **Positive terminal** to the LED.

---

## Working
- **Normal Condition:** The infrared beam from the IR transmitter reaches the IR receiver, keeping its impedance low. The base voltage of the transistor remains low, preventing it from conducting.
- **Fire Detection:** Infrared rays from fire disrupt the IR beam. The IR receiver’s resistance increases, raising the base voltage of the transistor. This activates the buzzer, signaling the fire alarm.

---

## Result
Upon detecting fire:
- The IR beam is blocked.
- The receiver's resistance increases.
- The transistor conducts, activating the alarm.

---

## Applications
1. **Fire Detection:** Alerts when fire or heat is detected.
2. **Occupant Alerting:** Warns people in the vicinity of danger.
3. **Risk Management:** Reduces potential fire damage.
4. **Authority Notification:** Can integrate with systems to notify emergency services.
5. **Equipment Inspection:** Ensures regular system checks for functionality.

---

