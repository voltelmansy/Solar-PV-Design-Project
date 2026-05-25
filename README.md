# 🌞 Off-Grid Solar PV System Design for Residential House

## 📌 Project Overview
This project presents a complete engineering design of an **Off-Grid Solar Photovoltaic (PV) system** for a small residential house.  
The system ensures **reliable and continuous electricity supply 24/7** without dependence on the utility grid by utilizing **solar energy generation and battery storage**.

---

## ⚡ Load Analysis (Daily Energy Consumption)

### 🏠 Household Electrical Loads

| Appliance | Power (W) | Usage (h/day) | Energy (Wh/day) |
|----------|-----------|---------------|-----------------|
| LED Lights (6 units) | 60 W | 5 h | 300 Wh |
| Refrigerator | 150 W | 24 h (40% duty cycle) | 1440 Wh |
| Television | 100 W | 4 h | 400 Wh |
| Fans (2 units) | 120 W | 6 h | 720 Wh |
| Laptop & Charging | 100 W | 4 h | 400 Wh |

### 🔋 Total Daily Energy Consumption
\[
E_{load} = 3260 \text{ Wh/day} \approx 3.26 \text{ kWh/day}
\]

---

## ☀️ Solar Resource Assumption
- 📍 Location: Cairo, Egypt  
- ☀️ Average Peak Sun Hours (PSH): 5.5 hours/day  
- ⚙️ System Efficiency: 75%

---

## ☀️ PV Array Sizing

### 🔹 Required PV Power
\[
P_{PV} = \frac{E_{load}}{PSH \times \eta}
\]

\[
P_{PV} = \frac{3260}{5.5 \times 0.75} \approx 790 \text{ W}
\]

### 🔆 Final PV Sizing (with safety margin)
👉 **Recommended PV Array: 1 kW system**

### 🔹 Selected Panels
- 2 × 550 W Mono-crystalline PV panels  
👉 Total Capacity = **1100 Wp**

---

## 🔋 Battery Bank Design

### 🔹 Requirement
- Autonomy: 1 day backup  
- System Voltage: 24V  
- Depth of Discharge (DoD): 80–85%

### 🔹 Battery Capacity Calculation
\[
C_{bat} = \frac{E_{load}}{V \times DoD}
\]

\[
C_{bat} \approx 160 \text{ Ah}
\]

### 🔋 Final Selection
👉 **24V – 200Ah Battery Bank**

---

## ⚙️ Charge Controller Sizing

\[
I_{cc} = \frac{P_{PV}}{V}
\]

\[
I_{cc} = \frac{1100}{24} \approx 46A
\]

### ⚙️ Final Selection
👉 **MPPT Charge Controller: 60A / 24V**

---

## 🔌 Inverter Sizing

### ⚡ Peak Load Estimation
- Estimated simultaneous load: 1500 – 1800 W

### 🔌 Final Selection
👉 **Pure Sine Wave Inverter: 2 kW / 24V**

---

## ⚡ Final System Configuration

- ☀️ PV Array: 2 × 550W (Total 1100W)
- 🔋 Battery Bank: 24V – 200Ah
- ⚙️ Charge Controller: 60A MPPT
- 🔌 Inverter: 2kW Pure Sine Wave

---

## 📊 System Performance Summary

- ⚡ Daily Energy Supply: 3.26 kWh
- 🔋 Backup Autonomy: 1 Day
- ⚙️ System Type: Off-Grid PV System
- 📈 Efficiency: ~75–80%

---

## 🎯 Engineering Considerations

- Battery Depth of Discharge (DoD): 80–85%
- System losses included (wiring, inverter, temperature)
- PV oversizing for cloudy conditions
- MPPT controller improves energy harvesting efficiency
- Scalability for future load expansion

---

## 🌍 Project Applications

- Rural electrification
- Remote residential houses
- Backup power systems
- Sustainable off-grid living solutions

---

## 👨‍💻 Author
Solar Energy & IoT Engineer  
Specialized in Renewable Energy Systems, PV Design, and Smart Energy Solutions

---

## 📌 Conclusion
This system demonstrates a complete **engineering-based off-grid solar PV design**, ensuring reliable energy independence for residential applications with optimized component sizing and system efficiency.
