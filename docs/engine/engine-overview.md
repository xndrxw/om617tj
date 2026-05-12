# Engine Overview

## Platform

The OM617TJ is built around a Mercedes OM617 turbo diesel installed in a 2005 Jeep Wrangler TJ. The engine package is aimed at usable torque, field serviceability, and real off-road reliability rather than a max-effort dyno-only setup.

## Current Configuration

- Engine: Mercedes OM617 turbo diesel
- Chassis: 2005 Jeep Wrangler TJ
- Fueling strategy: diesel / waste-oil capable dual-fuel system
- Turbocharger: Holset HE221W with 7cm housing
- Boost target: approximately 30 PSI
- Injection pump: 7.5mm BenzForce pump currently installed
- Future fuel upgrade path: planned 8mm M-pump
- Injectors: upgraded Bosch units
- Intercooling: water-to-air system using a FrozenBoost core and Meziere WP136S pump
- Exhaust: 3-inch system with wrapped downpipe noted in the current build docs
- Intake: custom snorkel and enclosed cone filter
- Engine oil filter: Baldwin B2-HPG

## Operating Priorities

1. Keep EGT under control under sustained load.
2. Maintain boost control stability near the upper target.
3. Balance fueling against airflow and intercooler effectiveness.
4. Avoid adding complexity that hurts field repairability.

## Known Watch Areas

- Sustained EGT during long pulls or low-speed/high-load off-road use
- High-boost durability margin at roughly 30 PSI
- Boost creep, wastegate control, or inconsistent controller behavior
- Heat management around the wrapped downpipe and nearby components
- Drivetrain stress as fueling and boost are both increased

## Related Documentation

- `docs/engine/om617-specifications.md`
- `docs/turbo-system/turbo-overview.md`
- `docs/intercooler/intercooler-overview.md`
- `docs/fuel-system/fuel-system-overview.md`
