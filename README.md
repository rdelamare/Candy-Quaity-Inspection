# Candy Quality Inspection System

## Overview
This project explores a vision-based system for detecting wrapped vs unwrapped candy and triggering a rejection mechanism in real time.

## Problem
Manual candy inspection is inconsistent, labor-intensive, and difficult to scale in high-throughput environments.

## System Architecture
- Camera captures candy images on a conveyor
- ML model performs classification
- Embedded controller triggers a reject actuator when defects are detected

## Technologies Used
- Python
- OpenCV
- YOLO-based CNN
- Raspberry Pi
- Embedded I/O (GPIO / solenoid control)

## What This Repository Demonstrates
- Dataset organization and preprocessing
- Model training workflow
- Real-time inference pipeline
- Hardware abstraction for actuation

## Intentionally Omitted
- Factory-specific calibration values
- Production deployment scripts
- Final tuning thresholds

## Status
Prototype stage
