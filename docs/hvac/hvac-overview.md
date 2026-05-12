# HVAC Overview

## System

Custom HVAC and A/C control setup focused on simple direct controls instead of full dependence on a stock integrated control scheme.

## Current / Planned Controls

- Toggle switch for A/C clutch
- Switch for heater-core enable / disable
- Stock vacuum controls for blend-door actuators
- PWM DC motor controller for blower fan

## Design Intent

The setup is meant to stay understandable and serviceable while still retaining the functions that matter: A/C clutch control, heater-core control, blend-door operation, and variable blower speed.

## Real Engineering Concerns

- Compressor-clutch wiring protection and switching logic
- Pressure-switch integration and fail-safe behavior
- Blower current handling and PWM-controller reliability
- Vacuum integrity for blend-door control
- Heater-core coolant routing and shutoff behavior

## Documentation Still Missing

- Compressor wiring diagram
- Pressure-switch logic
- Blower-control wiring and current capacity
- Heater-core valve or shutoff arrangement
- Operating notes for A/C mode vs heater mode
