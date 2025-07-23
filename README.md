# 🔋 Battery Voltage and Current Smoother

This project presents the design, simulation, and implementation of a battery voltage and current smoother to stabilize the output of a 9V battery. It is designed to provide a **steady 7.5V voltage** and **constant 50 mA current**, which are ideal for powering sensitive electronic components.

## 📌 Project Overview

Batteries often exhibit fluctuations in voltage and current due to load variations, temperature, and degradation. This circuit solves the issue by:

- Using a **Low Dropout (LDO) Regulator** for precise voltage regulation.
- Implementing a **constant current source** using a Zener diode, transistor, and resistors.
- Ensuring **stability and protection** for sensitive loads like microcontrollers or LEDs.

## 🧰 Tools & Technologies

- **Altium Designer** – PCB Design  
- **SolidWorks** – Enclosure Design  
- **LTSpice & Proteus** – Circuit Simulation  
- **JLCPCB** – PCB Manufacturing  

## 🛠️ Features

- ✅ Regulated output voltage: **7.5V**
- ✅ Constant current output: **~50 mA**
- ✅ Optimized energy usage from 9V battery
- ✅ Designed for use in embedded and low-power applications

## 📁 Repository Contents

- `Proposal.pdf` – Initial project proposal
- `Final_Report.pdf` – Complete technical report  
- `Enclosure/` – SolidWorks design files  
- `PCB/` – Altium Designer project files and Gerbers  
- `Simulation/` – Proteus simulations

## 🧪 Testing

- Simulations were performed using **Proteus** for both voltage and current regulation circuits.
- Final hardware was tested on a breadboard and with fabricated PCBs.
- Results showed minor deviations, which will be addressed in future work.

## 📈 Future Work

- Add user-adjustable knobs for tuning voltage/current
- Improve output precision for variable loads
- Miniaturize PCB and improve thermal efficiency

## 👨‍🔬 Team Members

| Name             | Task                                     |
|------------------|------------------------------------------|
| Aashir M.R.M.    | Constant current circuit design and simulation   |
| Priyanjana T.P.I.M. | PCB design and hardware testing        |
| Ilukkumbura I.M.E.I.B | Constant voltage circuit and simulation |
| Basith M.N.A.    | Enclosure design and hardware testing    |



