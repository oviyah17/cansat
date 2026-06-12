# System Architecture

## Overview

The CanSat consists of six primary subsystems:

### Payload Subsystem
- BMP280
  - Atmospheric pressure measurement
  - Altitude estimation
  - Temperature sensing

- MPU6050
  - Acceleration measurement
  - Angular motion monitoring
  - Descent stability analysis

### Control & Processing Subsystem
- ESP32
  - Sensor interfacing
  - Data acquisition
  - Mission logic execution
  - Storage management

### Data Handling & Storage Subsystem
- SD Card Module
  - Time-stamped data storage
  - Post-flight analysis support

### Power Subsystem
- LiPo Battery
  - Electrical power supply

### Descent & Recovery Subsystem
- Parachute
  - Controlled descent
  - Safe landing

### Structure Subsystem
- 3D Printed Chassis
  - Component protection
  - Structural support
