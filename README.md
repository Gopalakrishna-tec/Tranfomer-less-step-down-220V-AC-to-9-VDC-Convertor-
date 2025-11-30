# 🔌 Transformer-less 220V AC to 9V DC Converter

A compact transformer-less power supply that converts **220V AC to 9V DC** using a capacitive dropper, bridge rectifier, filter capacitor, and zener regulation. Designed for low-power applications where small size and low cost are essential.

---

## 📦 Components

| No. | Component                        | Quantity | Notes              |
| --- | -------------------------------- | -------- | ------------------ |
| 1   | Bridge Rectifier                 | 4        | Bridge Rectifier   |
| 2   | 470µF 25V Electrolytic Capacitor | 1        | Output Filtering   |
| 3   | 9V Zener Diode                   | 1        | Voltage Regulation |
| 4   | 1MΩ 25W Resistor                 | 1        | Discharge / Safety |
| 5   | 100Ω 2W Resistor                 | 1        | Surge Limiting     |
| 6   | 225J 400V Capacitor              | 1        | Capacitive Dropper |

---

## ⚙️ Working Principle

* **AC Dropping:** 225J 400V capacitor reduces AC current reactively.
* **Discharge Safety:** 1MΩ resistor drains the capacitor when off.
* **Rectification:** Bridge rectifier form a full-bridge rectifier.
* **Filtering:** 470µF capacitor smooths DC output.
* **Regulation:** 9V zener diode stabilizes final voltage.
* **Protection:** 100Ω resistor provides surge control.


## ⚠️ Safety Warning

This is a **non-isolated circuit** directly connected to **220V AC mains**.
Use extreme caution. Not suitable for beginners or high-power loads.

---

## 📂 Repository Structure

```
├── AC-DC.pdf
├── AC-DC_.png
└──Gerber_AC-DC_PCB_AC-DC_2025-11-30.zip
