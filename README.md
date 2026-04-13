# 🔥 Project IGNIS - Complete Thrust Vector Control System

## Three Module Architecture

### 🚀 IGNIS_CORE (Flight Computer)
- **Hardware**: STM32F411CEU6
- **Sensors**: MPU6500, MS5611, NEO-6M
- **Telemetry**: SX1278 LoRa
- **Output**: PWM to IGNIS_CTRL servos
- **3D Printed**: Enclosure, mounts, battery holder

### ⚙️ IGNIS_CTRL (Mechanical TVC)
- **Components**: 2x Servos, Gimbal, Linkages
- **No Electronics** - Just mechanical parts
- **3D Printed**: Brackets, gimbal, motor mount

### 📡 IGNIS_NET (Ground Station)
- **Hardware**: STM32/ESP32 + SX1278 + OLED + LEDs
- **3D Printed**: Handheld enclosure, antenna mount, stand
- **PC Software**: Python GUI for telemetry display

## Communication Flow


## Quick Links
- [IGNIS_CORE Firmware](IGNIS_CORE/Firmware/)
- [IGNIS_CORE Hardware](IGNIS_CORE/Hardware/)
- [IGNIS_CTRL CAD](IGNIS_CTRL/Mechanical_Design/CAD_Files/)
- [IGNIS_NET Firmware](IGNIS_NET/Firmware/)
- [IGNIS_NET 3D Models](IGNIS_NET/Hardware/3D_Models/)
- [IGNIS_NET PC Software](IGNIS_NET/PC_Software/)

## Status
🚧 Active Development
