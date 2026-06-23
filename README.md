# ESP32-Multi-Motor-Controller-Board-
Custom ESP32-WROOM-32 robotics controller PCB with onboard buck/LDO power regulation, auto-program circuit, and BTS7960/RMCS/relay/servo interfaces. Designed in KiCad.
# ESP32 Dual BTS7960 Motor Driver Breakout Board

A custom 2-layer PCB designed to handle heavy-duty robotics applications. It acts as a central control board breaking out an ESP32 to interface with dual BTS7960 motor drivers, an RMCS driver, and features onboard power regulation.

## Features
- **Microcontroller:** ESP32-WROOM-32
- **Power Stage:** LM2596 Buck Regulator (12v to 5v switching) & AMS1117-3.3 (5v to 3.3v switching)
- **Motor Control Interfaces:** 2x BTS7960 H-Bridge Drivers, 1x RMCS Driver interface
- **Peripherals:** Integrated Micro USB for programming (CH340C), Boot & Reset tactile switches, and broken-out GPIO headers.

## Design Highlights
- Optimized high-frequency switching loops for the buck regulator to minimize EMI.
- Completely isolated RF antenna keepout zone on both layers for maximum wireless signal integrity.
- Solid ground planes on both layers for optimal return paths.
<img width="777" height="677" alt="Screenshot 2026-06-24 011219" src="https://github.com/user-attachments/assets/4a383574-238e-4939-897b-7e28e23955de" />
<img width="508" height="542" alt="Screenshot 2026-06-24 011050" src="https://github.com/user-attachments/assets/255f32db-a524-45c8-a1ec-8bec6feb83d2" />
<img width="516" height="542" alt="Screenshot 2026-06-24 011103" src="https://github.com/user-attachments/assets/1a1decaf-27ed-46dc-9d63-330b6b780d59" />
<img width="1316" height="701" alt="Screenshot 2026-06-23 231602" src="https://github.com/user-attachments/assets/dff1a315-b747-4f8c-927e-22db14b84688" />
