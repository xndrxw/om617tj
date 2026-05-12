# Fuel Filtration

## Current Filter Setup

| Position | Filter |
|---|---|
| Diesel primary | Baldwin BF1272-SPS |
| Waste-oil primary | Baldwin BF1272-SPS |
| Final fuel filter | Donaldson P551313 |
| Engine oil filter | Baldwin B2-HPG |

## Functional Layout

The current documented order is:

Tank -> primary filter -> selector valve -> final filter -> injection pump

This keeps the tank-specific primary filtration upstream of fuel selection and uses a common final filter to protect the injection system.

## Why This Layout Makes Sense

- Each tank gets its own first-stage cleanup.
- The final filter protects the injection pump regardless of which tank is selected.
- Service points stay relatively obvious and centralized.
- The arrangement fits the build goal of diesel + waste-oil capability without adding unnecessary parallel complexity downstream.

## Service / Reliability Watch Items

- Watch for air intrusion after primary-filter service.
- Track restriction increase if waste oil quality varies.
- Treat water separation performance as more critical on the waste-oil side.
- Keep contamination control tight when switching filters or opening the system.
- If cold-flow behavior becomes a problem, filtration performance has to be evaluated together with oil temperature and purge behavior, not in isolation.
