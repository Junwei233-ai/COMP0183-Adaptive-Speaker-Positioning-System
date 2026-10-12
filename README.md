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





# COMP0183 自适应音响定位系统

## 项目简介

本项目用于 **COMP0183 – Designing Sensor Systems**。

项目目标是设计一套能够检测听者位置，并通过 **XY 双轴移动平台** 自动调整音响位置的自适应系统。

目前项目总预算约为 **£700**。

---

## 系统概念

```text
听者
 ↓
Camera + ToF 传感器
 ↓
位置估计
 ↓
控制算法
 ↓
ESP32
 ↓
X/Y 电机
 ↓
XY 音响移动平台
```

系统会估计听者的二维位置，并将音响移动到对应的目标位置。

---

## 主要组成

### 感知部分

- USB Camera
- VL53L5CX ToF 距离传感器
- Computer Vision
- Sensor Fusion

### 处理部分

- Laptop
- OpenCV / YOLO
- ESP32

### 运动部分

- 2 × NEMA 17 步进电机
- Motor Driver
- XY 线性滑轨
- Belt 和 Pulley
- Limit Switch

### 现有设备

- 音响

音响已经具备，因此不需要额外购买。

---

## 主要目标

- 检测室内听者
- 估计听者二维坐标
- 融合 Camera 和 ToF 数据
- 控制 XY 双轴运动平台
- 让音响准确、安全地移动
- 减少传感器噪声导致的不必要运动

---

## 开发计划

1. 实现 Camera 人体检测
2. 测试 ToF 距离检测
3. 计算听者二维位置
4. 搭建并测试单轴滑轨
5. 搭建完整 XY 平台
6. 集成人体定位与电机控制
7. 优化滤波、运动速度和系统稳定性

---

## 初步性能目标

- 人体检测范围：**1–3 m**
- 人体位置估计误差：**< 10–15 cm**
- XY 平台定位误差：**< 10 mm**
- 系统响应时间：**约 1–2 秒**

---

## 后期优化

后续可以加入：

- Kalman Filter
- 闭环步进电机
- Encoder 位置反馈
- 降低机械噪声
- 多人检测
- 麦克风声学验证

麦克风测量暂时作为后期优化和验证部分，不属于第一阶段核心功能。

---

##

##

## 当前状态

**概念设计 → 传感器选型 → 可行性测试**

