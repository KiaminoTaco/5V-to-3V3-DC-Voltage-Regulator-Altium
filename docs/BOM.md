# Bill of Materials

## Component Summary

| Reference | Quantity | Description | Value / MPN | Role |
|---|---:|---|---|---|
| U1 | 1 | Low-dropout regulator | MIC5317-3.3YM5-TR | Converts +5 V to +3.3 V |
| C1 | 1 | SMD capacitor | 1 µF | Input decoupling |
| C2 | 1 | SMD capacitor | 1 µF | Output decoupling |
| J1 | 1 | 2-position connector | SM02B-GHS-TB(LF)(SN) | +5 V input |
| J2 | 1 | 2-position connector | SM02B-GHS-TB(LF)(SN) | +3.3 V output |

## Functional Groups

### Power regulation
- U1: MIC5317-3.3YM5-TR

### Decoupling
- C1: 1 µF at the input
- C2: 1 µF at the output

### Interfaces
- J1: +5 V / GND input
- J2: +3.3 V / GND output

## Verification Before Ordering

The supplied schematic establishes the electrical values above. Before purchasing or manufacturing, verify the following in the native Altium project and component datasheets:

1. Capacitor voltage rating.
2. Capacitor dielectric and package.
3. Exact connector manufacturer and mating requirements.
4. PCB footprints.
5. Regulator package and assembly orientation.
6. Component availability and approved substitute parts, if required.
