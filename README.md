# Real-Time-EV-Dashboard-ADAS-Warning-System

# Real-Time EV Dashboard & ADAS Warning System

An embedded systems internship project implementing a real-time Electric Vehicle (EV) telemetry dashboard and Advanced Driver Assistance System (ADAS) warning unit using STM32, PICSimLab simulation, and a Python telemetry link.

---

## 🛠️ System Architecture & Workflow

1. **Firmware (STM32 / STM32CubeIDE):** 
   Handles sensor processing (speed, battery metrics), threshold monitoring, and ADAS event logic.
2. **Hardware Simulation (PICSimLab):** 
   Simulates microcontroller hardware, peripheral mapping, and serial transmission.
3. **Serial Communication Bridge (VSPE & Python):** 
   - **VSPE (Virtual Serial Ports Emulator):** Establishes virtual COM port pairs to link PICSimLab to the host machine.
   - `ev.py`: Python serial script (written in VS Code) that reads streaming UART telemetry and renders the dashboard output.

---

## 📁 Repository Contents

- `Core/` - STM32 C source files (`main.c`, hardware drivers, system initialization)
- `ev_dash.ioc` - STM32CubeMX peripheral pinout and clock configuration file
- `ev_dash.pzw` - PICSimLab board setup and workspace configuration
- `ev.py` - Python serial communication and telemetry parsing script
- `.gitignore` - Build and binary artifact exclusion rules

---

## 💻 Tech Stack & Tools

- **Embedded Firmware:** C / STM32CubeIDE
- **Hardware Simulator:** PICSimLab
- **Serial Link:** VSPE (Virtual Serial Ports Emulator), Python (`pyserial`)
- **IDE:** VS Code (Scripting) & STM32CubeIDE
