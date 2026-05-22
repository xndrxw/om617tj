# SA150-975L Super Capacitor

## Component Overview

**Model:** SA150-975L  
**Type:** Series SuperCap™ battery backup  
**Purpose:** Peak power assist for starter and high-draw loads during high-boost operation

## Specifications

| Parameter | Value |
|-----------|-------|
| Nominal Voltage | 48V DC |
| Capacitance | 975F @ 1.8V per cell (4 cells in series) |
| Energy Storage | ~1.5kWh total (distributed across 4 series cells) |
| Charge Time | <5 minutes via standard 48V charging circuit |
| Cycle Life | 500,000+ cycles |
| Temperature Range | -40°C to +70°C operating |

## Integration Notes

### Wiring Integration
- **Series Connection:** 4 cells in series to achieve 48V nominal system voltage
- **Parallel Option:** Multiple modules can be paralleled for extended runtime if needed
- **Charging:** Requires dedicated 48V charging circuit from alternator output

### Mounting
- **Location:** Engine bay, near alternator for minimal voltage drop
- **Orientation:** Vertical mounting recommended for optimal internal cell alignment
- **Protection:** Requires external thermal protection and reverse polarity protection

### Integration Points

**Target Loads:**
- Starter motor assistance during cold cranking
- Peak power support for alternator under high-boost (30 PSI) conditions  
- Supplemental power for onboard air compressor
- Buffer for sudden high-draw loads

**Charging Circuit Requirements:**
- Dedicated 48V line from alternator output
- Current-limited charging (max 3A per cell recommendation)
- BMS required to prevent overvoltage on individual series cells

## Performance Characteristics

### Peak Current Capability
- **Short-term burst:** Can deliver 1000A+ for 10-30 seconds
- **Sustained load:** 200-400A for extended periods
- **Recovery time:** Full recovery in 5-10 minutes at moderate loads

### Use Case Rationale

The SA150-975L addresses several high-current scenarios in the OM617TJ build:

1. **Starter Assistance:** Reduces alternator load during cranking, especially beneficial in cold weather or when engine is hot after high-load operation

2. **High-Boost Power Demand:** At 30+ PSI boost, the turbocharger and intercooler pump draw significant power. The supercap provides immediate burst support without overloading the alternator.

3. **Onboard Air:** Compressor loads can spike to 200-400A briefly. Supercap buffers these spikes.

## System Impact

### Benefits
- Reduces alternator thermal load
- Provides instantaneous high-current capability
- Minimal weight penalty vs. equivalent AGM backup
- Fast recovery time between cycles

### Considerations
- **Cost:** Higher initial cost than AGM battery
- **Charging Complexity:** Requires dedicated 48V charging circuit with BMS
- **Maintenance:** No traditional maintenance, but requires BMS health monitoring
- **Cold Weather:** Performance degrades at extreme temperatures (normal for supercaps)

## Future Integration

Pending decisions:
- [ ] Final charging circuit design
- [ ] BMS selection and installation
- [ ] Mounting bracket fabrication
- [ ] Integration into power distribution diagram
- [ ] Testing and validation under load

## References

- **SA150-975L Datasheet:** Supercap battery manufacturer specifications
- **Charging Circuit Design:** To be documented in separate file
- **BMS Selection:** Pending selection based on current requirements

---

*Last Updated: 2025-05-19*
*Author: OM617TJ Build Team*
