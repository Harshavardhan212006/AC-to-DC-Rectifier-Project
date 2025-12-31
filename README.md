# AC–DC POWER CONVERSION USING BRIDGE RECTIFIER AND VOLTAGE REGULATION

## Abstract
This project presents the design and implementation of an AC to DC rectifier system capable of delivering stable +5 V and −5 V regulated outputs. The circuit employs a step-down transformer, full-wave bridge rectifier configuration using silicon diodes, capacitor-based ripple filtering, and linear voltage regulation through IC regulators. The experiment validates reliable power conversion suitable for low-power electronic applications.

---

## 1. Introduction
Power conversion is one of the most fundamental functions in electronic systems. Most electronic circuits require stable DC supply even though the main utility delivers AC power. This work focuses on developing a laboratory-scale AC–DC conversion system that demonstrates rectification, filtering, and regulation processes.

---

## 2. Objective
To design and implement a power supply capable of:
- Converting AC input to DC
- Reducing ripple using filtering techniques
- Providing stable +5 V and −5 V regulated outputs

---

## 3. Components and Specifications
| Component | Specification |
|----------|--------------|
| Transformer | Step-down |
| Silicon Diodes | IN4007 |
| Capacitors | Filter Capacitors |
| Voltage Regulators | IC7 (Two Units) |
| Board & Wiring | PCB / Breadboard |

---

## 4. System Theory
The AC input is stepped-down using a transformer. A full-wave bridge rectifier converts the AC waveform to pulsating DC. Capacitors perform smoothing by reducing ripple voltage. Linear voltage regulators stabilize output to obtain precise +5 V and −5 V.

Key Processes:
1. Step-down transformation  
2. Full-wave rectification  
3. Filtering  
4. Linear regulation  

---

## 5. Circuit Implementation
- Bridge rectifier constructed using four IN4007 diodes
- Capacitors connected across output for ripple suppression
- Regulator ICs configured to provide +5 V and −5 V
- Output validated using measurement instruments

---

## 6. Results
- Stable +5 V DC output achieved
- Stable −5 V DC output achieved
- System demonstrated reliable performance

(Insert images in GitHub repo)
- <img width="960" height="1280" alt="img 1" src="https://github.com/user-attachments/assets/d462213b-42a7-4928-8eb6-558ddcdd734a" />

- <img width="1280" height="960" alt="img 2" src="https://github.com/user-attachments/assets/9c0e7466-32e5-4a9f-b9cf-4cb1f00bb8ec" />


---

## 7. Challenges and Resolution
| Issue Faced | Resolution |
|------------|-----------|
| Difficulty in soldering multiple wires | Adopted improved soldering techniques |

---

## 8. Conclusion
The design successfully demonstrated AC-to-DC conversion with effective rectification, filtering, and regulation. The project reinforces the significance of rectifier circuits in power supply design for electronic systems.

---

