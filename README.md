# COMP0183 Adaptive Speaker Positioning System

## Overview

This project is developed for **COMP0183 – Designing Sensor Systems**.

The aim is to build an adaptive speaker positioning system that detects the position of a listener and automatically moves a loudspeaker using an **XY two-axis motion platform**.

The current project budget is approximately **£700**.

---

## System Concept

```text
Listener
   ↓
Camera + ToF Sensors
   ↓
Position Estimation
   ↓
Control Algorithm
   ↓
ESP32
   ↓
X/Y Motors
   ↓
XY Speaker Platform
```

The system will estimate the listener's 2D position and move the speaker to a corresponding target position.

---

## Main Components

### Sensing
- USB Camera
- VL53L5CX Time-of-Flight sensor
- Computer vision
- Sensor fusion

### Processing
- Laptop
- OpenCV / YOLO
- ESP32

### Motion
- 2 × NEMA 17 stepper motors
- Motor drivers
- XY linear rail system
- Belts and pulleys
- Limit switches

### Existing Equipment
- Loudspeaker

The loudspeaker is already available and does not need to be purchased.

---

## Main Objectives

- Detect a listener indoors
- Estimate the listener's 2D position
- Combine camera and ToF measurements
- Control an XY motion system
- Move the speaker accurately and safely
- Reduce unnecessary movement caused by sensor noise

---

## Development Plan

1. Implement camera-based human detection
2. Test ToF distance sensing
3. Estimate listener 2D position
4. Build and test one motion axis
5. Build the full XY platform
6. Integrate sensing and motion control
7. Optimise filtering, speed and movement stability

---

## Initial Targets

- Human detection range: **1–3 m**
- Position estimation error: **< 10–15 cm**
- XY positioning error: **< 10 mm**
- System response time: **around 1–2 seconds**

---

## Future Improvements

Possible later improvements include:

- Kalman filtering
- Closed-loop motor control
- Encoder feedback
- Reduced mechanical noise
- Multi-person tracking
- Acoustic evaluation using a microphone

Acoustic measurement will be treated as a later optimisation and validation stage rather than part of the initial prototype.

---

# COMP0183 Adaptive Speaker Positioning System

## Overview

This project is developed for **COMP0183 – Designing Sensor Systems**.

The aim is to build an adaptive speaker positioning system that detects the position of a listener and automatically moves a loudspeaker using an **XY two-axis motion platform**.

The current project budget is approximately **£700**.

---

## System Concept

```text
Listener
   ↓
Camera + ToF Sensors
   ↓
Position Estimation
   ↓
Control Algorithm
   ↓
ESP32
   ↓
X/Y Motors
   ↓
XY Speaker Platform
```

The system will estimate the listener's 2D position and move the speaker to a corresponding target position.

---

## Main Components

### Sensing
- USB Camera
- VL53L5CX Time-of-Flight sensor
- Computer vision
- Sensor fusion

### Processing
- Laptop
- OpenCV / YOLO
- ESP32

### Motion
- 2 × NEMA 17 stepper motors
- Motor drivers
- XY linear rail system
- Belts and pulleys
- Limit switches

### Existing Equipment
- Loudspeaker

The loudspeaker is already available and does not need to be purchased.

---

## Main Objectives

- Detect a listener indoors
- Estimate the listener's 2D position
- Combine camera and ToF measurements
- Control an XY motion system
- Move the speaker accurately and safely
- Reduce unnecessary movement caused by sensor noise

---

## Development Plan

1. Implement camera-based human detection
2. Test ToF distance sensing
3. Estimate listener 2D position
4. Build and test one motion axis
5. Build the full XY platform
6. Integrate sensing and motion control
7. Optimise filtering, speed and movement stability

---

## Initial Targets

- Human detection range: **1–3 m**
- Position estimation error: **< 10–15 cm**
- XY positioning error: **< 10 mm**
- System response time: **around 1–2 seconds**

---

## Future Improvements

Possible later improvements include:

- Kalman filtering
- Closed-loop motor control
- Encoder feedback
- Reduced mechanical noise
- Multi-person tracking
- Acoustic evaluation using a microphone

Acoustic measurement will be treated as a later optimisation and validation stage rather than part of the initial prototype.

---

## Current Status
