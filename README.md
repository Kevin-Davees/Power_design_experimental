# Experimental 20A Battery Charger PCB (Failed Design)

## Overview

This repository contains an early experimental PCB design for a 20A battery charger with an integrated battery protection IC.

This design is one of my early PCB layout attempts and is NOT suitable for manufacturing, production, or real-world usage.

The design is published only for documentation and learning purposes.

IMPORTANT:
This design contains major electrical and thermal design flaws.

DO NOT attempt to manufacture, assemble, or use this PCB in any real system.

---

## Project Intent

The purpose of publishing this repository is to:

- Document early design mistakes
- Demonstrate poor high-current PCB layout practices
- Help others understand what not to do in power PCB design
- Track personal learning progress in PCB development

---

## Major Design Problems

This PCB has multiple serious issues that make it unsuitable for high-current applications.

### 1. Poor Copper Pour Design

The copper pour implementation is incorrect and does not properly support high current flow.

Problems include:

- Poor copper distribution
- Narrow current paths for a 20A design
- Inconsistent copper connectivity
- Inefficient current return paths
- Copper pours that do not significantly reduce resistance

A 20A power design requires much larger copper areas and carefully designed current paths.

---

### 2. Bad Heat Dissipation

Thermal management in this PCB is insufficient.

Issues include:

- High-current components lacking adequate copper area for heat spreading
- No effective thermal vias
- Poor thermal distribution across the board
- Suboptimal placement of power components

Under high load, this design would likely overheat.

---

### 3. Layout Not Suitable for High Current

The PCB layout does not follow correct high-current design practices.

Examples:

- Trace widths are insufficient for a 20A system
- Power routing is inefficient
- High-current paths are not optimized
- Potential voltage drop across traces

A properly designed 20A charger PCB requires extremely low resistance power paths, which this design does not provide.

---

### 4. Experimental Quality Layout

This board was created while learning PCB design fundamentals.

As a result:

- The layout structure is not professional
- Power routing is poorly optimized
- Thermal considerations are inadequate
- Design rule practices are incomplete

---

## Warning

This PCB should NOT be used for:

- Manufacturing
- Commercial products
- Battery charging systems
- High current electronics
- Safety critical applications

Using this design may result in:

- Overheating
- PCB damage
- Component failure
- Safety hazards

---

## Why This Repository Exists

Engineering improvement comes from learning through mistakes.

This repository exists to:

- Document an early failed design
- Maintain a record of design evolution
- Show progress in PCB design skills over time

Future designs will focus on:

- Proper high-current layout techniques
- Correct copper pour usage
- Improved thermal management
- Better power routing practices

---

## License

Shared for educational and documentation purposes only.

Use the files at your own risk.
