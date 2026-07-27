# UMaT Building Automation System - Abstraction Lab

## Task Overview
This repository contains a Python implementation demonstrating **Abstraction** using the `abc` (Abstract Base Class) module for the UMaT Auditorium Automation System.

The `BuildingSystem` abstract class acts as a blueprint, enforcing standard operational methods (`start()`, `stop()`, and `status()`) that every automated system in the building must implement.

## Key Features
- **Strict Contract Enforcement:** Abstract methods ensure consistent behavior across all subclasses (`AirConditioningSystem`, `LightingSystem`, `SecuritySystem`, and `FireAlarmSystem`).
- **Extensibility:** New modules (like `FireAlarmSystem`) integrate cleanly into existing execution loops without breaking runtime stability or requiring structural modifications.
- **Polymorphism:** Iterates through a unified system list calling common interfaces dynamically.

## How to Run
```bash
python main.py
