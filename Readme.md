# Hydrovar HV Pump Reverse Engineering

## 📖 Description
This repository documents a **draft reverse engineering project** for the **Lowara Hydrovar HV 2.015-4.220** pump controller. It serves as a technical resource for hardware analysis, featuring high-resolution **photographs** of the internal assembly and **draft schematics** of the Power PCB.

Lowara **does not** offer **any** replacement parts for their units, so a complete pump controller must the thrown out, when anything goes wrong!

## Known issues

### Vcc capacitor of fly back converter U6 (ICE2A180Z)

* **Failure description:** Display of unit gets dark and unit does not react any longer.
* **Failure mode:** Vcc capacitor (Chemicon MZA 35V 47uF) of fly back converter gets bad and Vcc of U6 becomes unstable. U6 then does not turn on any longer, which make the complete DC power supply fail. Issue can be resolved by replacing this capacitor, e.g. with  HXC350ARA680.

<img width="716" height="646" alt="image" src="https://github.com/user-attachments/assets/387366a2-6c0d-4590-9b8f-3ee80bb57918" />


---

## ⚠️ Disclaimer
**DANGER: High Voltage.** This project is for **educational purposes only**. The Lowara Hydrovar HV operates at lethal voltages; only qualified professionals should handle these units. 

The provided schematics are **drafts** and may contain inaccuracies. The authors assume no liability for damage or injury. This independent project is not affiliated with or endorsed by Xylem or Lowara.

---

## 🛠 Project Contents
* **Hardware Imagery:** Detailed photos of the controller layout and component placement.
* **Power PCB Analysis:** Preliminary circuit mapping of the power stage and motor drive sections.
