# Real-Time-EV-Dashboard-ADAS-Warning-System
# Real-Time EV Dashboard & ADAS (STM32 & PICSimLab)

An embedded systems internship project implementing a real-time Electric Vehicle (EV) dashboard and Advanced Driver Assistance System (ADAS) simulation using an STM32 microcontroller and PICSimLab hardware simulator.

## Key Features
- **Real-Time Data Processing:** Monitored simulated EV parameters including speed, battery state, and sensor telemetry.
- **Peripheral Control:** Utilized STM32 timers, ADC, GPIOs, and communication interfaces for dashboard telemetry feedback.
- **Hardware Simulation:** Designed and executed virtual hardware testing via PICSimLab.

## Repository Structure
- `Core/Src/` - Embedded C source files (`main.c`, `ev_control.c`, etc.).
- `Core/Inc/` - Header files and driver configurations.
- `ev_dash.ioc` - STM32CubeMX peripheral pinout and clock configuration file.
- `ev_dash.pzw` - PICSimLab board layout and workspace setup.

## Tools & Hardware
- **IDE:** STM32CubeIDE
- **Simulation Suite:** PICSimLab
- **Microcontroller Architecture:** ARM Cortex-M (STM32)
