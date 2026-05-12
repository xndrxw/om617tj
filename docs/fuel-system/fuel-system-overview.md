# Fuel System Overview

## System Type

Dual-fuel system using separate tanks for diesel and waste oil, with a shared downstream final filtration stage before the injection pump.

## Current Architecture

Current routing documented in the wiki:

Tank -> primary filter -> selector valve -> final filter -> injection pump

## Tanks and Feed Layout

- Driver side tank: diesel
- Passenger side tank: waste oil
- Both tanks use Beans Diesel sump fittings
- Feed lines noted in repo docs: -10AN from tanks

## Filtration Baseline

- Primary filters: Baldwin BF1272-SPS, one per tank
- Final fuel filter: Donaldson P551313
- Engine oil filter: Baldwin B2-HPG

## Design Intent

The fuel system is set up to support both conventional diesel operation and waste-oil operation while keeping final filtration centralized and service points easy to understand.

## Critical Watch Areas

- Waste-oil viscosity during cold starts and cold ambient operation
- Purge behavior between fuels before shutdown and restart
- Selector-valve failure modes and air intrusion points
- Contamination control during filter changes or fuel switching
- Hose material compatibility and long-term sealing under heat/vibration

## What Is Still Not Pinned Yet

These items are known gaps, not hidden assumptions:

- Exact selector valve part number and wiring details
- Any dedicated tank-heating hardware or procedure
- Formal startup / purge / shutdown procedure for waste-oil use
- Final hose-size, check-valve, and return-layout documentation
