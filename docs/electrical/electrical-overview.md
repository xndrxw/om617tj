# Electrical System Overview

## Core Architecture

The OM617TJ electrical system is built around a dual-battery, breaker-protected layout with emphasis on reliability, serviceability, and reduced sensor noise.

## Power System

- Dual AGM batteries, 800 CCA each
- Blue Sea battery selector switch with A / B / Both functionality
- AD244 alternator
- Premier Power Welder noted as a major high-current support load
- Custom fuse / relay panel for distributed vehicle circuits

## Circuit Protection

- Major protection strategy: 500A breakers and ANL fuses
- Resettable breaker hardware noted in repo docs
- ATO-style fuse protection for smaller branch circuits

## Design Goals

- Waterproof and field-serviceable packaging
- Minimal unnecessary relays
- Centralized, understandable power distribution
- Separation between noisy high-current circuits and sensitive sensor wiring

## Current Sensor / Monitoring Coverage

- EGT
- Boost
- Coolant temperature
- Oil temperature
- Oil pressure
- Intake air temperature pre-intercooler
- Intake air temperature post-intercooler
- Intercooler fluid temperature
- System voltage

## Known Watch Areas

- Grounding topology and return-path quality
- Voltage drop under high-current accessory loads
- Sensor reference stability
- Routing separation between starter/winch/fan circuits and low-level signal wiring
- Documentation completeness for fuse, breaker, and cable sizing
