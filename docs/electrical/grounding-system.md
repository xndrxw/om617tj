# Grounding System

## Grounding Strategy

Grounding is treated as a reliability and signal-quality system, not an afterthought. The build philosophy is to use heavy backbone grounds for major loads and keep sensor returns stable so gauges and monitoring stay trustworthy.

## Current / Planned Ground Paths

- Battery to frame
- Battery to engine
- Engine to frame
- Frame to body / cab
- Front frame ground
- Rear frame ground
- Dedicated sensor-ground backbone
- Alternator ground
- Starter ground

## Design Intent

- Reduce voltage drop during cranking and winch-type loads
- Keep engine, chassis, and body on known low-resistance ground paths
- Prevent noisy accessory returns from corrupting sensor readings
- Make future troubleshooting simpler by keeping the topology intentional

## High-Value Watch Items

- Shared grounds between high-current loads and sensitive sensors
- Corrosion or paint under lugs that raises resistance over time
- Long return paths through body sheetmetal instead of dedicated cables
- Ground-point sprawl that becomes impossible to audit later
- Weak alternator or starter return paths that hide as intermittent issues

## Documentation Still Needed

- Actual wire gauges by ground leg
- Lug and stud locations with photos
- Measured resistance / voltage-drop checks under load
- Final dedicated sensor-ground routing map
