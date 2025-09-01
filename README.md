# MAP-205 Automation – PLC-Code+HMI-Design
This branch contains all **source code and project files** developed for the automation and control of the **SMC MAP-205 training kit**.  
The code integrates **PLC ladder logic** (CX-Programmer) with a **custom HMI interface** (CX-Designer).  

---

## 📂 Contents  
📂 PLC-Code+HMI-Design/
│── backup code trial 2.cxp → Omron CX-Programmer project file
│── NewProject.IPP → Omron CX-Designer project file
│── Simulation_Files/ → Grafcet diagrams & flowcharts

---

## ⚙️ Requirements  
To run and edit these files, you will need:  
- **Omron CX-Programmer** (for PLC ladder logic)  
- **Omron CX-Designer** (for HMI design)  
- Compatible **Omron CP1H PLC** (hardware or simulator)  

---

## 🚀 How to Use  
1. Open **`backup code trial 2.cxp`** in **CX-Programmer**.  
   - Download the program into the Omron CP1H PLC.  
   - Alternatively, run in simulator mode.  

2. Open **`NewProject.IPP`** in **CX-Designer**.  
   - Deploy to the NB-series HMI.  
   - The HMI provides real-time control, manual/auto mode, and alarm handling.  

3. Review **`Simulation_Files/`** for Grafcet diagrams and sequence workflows.  
   - These explain the logic behind the automation process.  

---

## 🔹 Features Implemented in Code  
- Full **assembly & disassembly sequence** automation.  
- **Manual and Auto operation modes**.  
- **Sensor-actuator integration** with PLC logic.  
- **HMI interface** for real-time visualization and alarms.  

---

## 📌 Notes  
- These files are designed specifically for the **SMC MAP-205 training kit**.  
- If you want to reuse/adapt them, adjust I/O mapping according to your own PLC and hardware.  

---

## 👤 Author  
**Mazen Mohamed Mahrous**  
🎓 Universiti Teknologi Malaysia (UTM) – Electrical-Mechatronics  
