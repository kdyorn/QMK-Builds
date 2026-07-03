# Dissect — QMK Build

A custom 70-key split mechanical keyboard designed and built by [kdyorn](https://github.com/kdyorn).

## Overview

| Feature | Detail |
|---|---|
| Layout | 70-key split |
| Firmware | QMK |
| Controller | Pro Micro RP2040 |
| Case | 3D Printed — Sunlu Matte PLA |
| Switches | GK Gamakay Pegasus Tactile |
| Connection | USB Type-C breakout between halves |

## Repository Structure

```
dissect/
├── BOM.md              # Full bill of materials with links
├── firmware/           # QMK firmware files
├── case/
│   ├── stl/            # Print-ready STL files
│   └── source/         # Editable CAD source files
├── pcb/
│   └── gerbers/        # PCB production files
└── docs/
    └── build-photos/   # Build log photos
```

## Bill of Materials

See [BOM.md](BOM.md) for a full parts list with Amazon links.

## Build Notes

- Handwired build using 16 AWG copper wire for row bus bars and 22 AWG solid wire for column bus
- 26 AWG stranded wire used for controller connections
- Wheel weights added inside case for improved feel and stability

## License

This design is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to share and adapt this design for non-commercial purposes with appropriate credit to **kdyorn**.
