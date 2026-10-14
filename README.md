# lora-rssi-rf-frontend

Custom sub-GHz LoRa RF front-end (STM32WL) with matching, harmonic filtering and TX/RX switching, plus RSSI-based localization. Entry for the SPECTRA 2026 RF Circuit Design Challenge.

> Status: ongoing

## Overview
- **RF front-end:** impedance matching network, low-pass harmonic filter, TX/RX switch, 50 Ω SMA test port
- **Localization:** log-distance path-loss calibration and least-squares trilateration from RSSI
- **Validation:** simulation (Qucs-S, Python) vs VNA and USRP measurements, with Monte Carlo tolerance analysis

## Repository map
| Folder | Contents |
|---|---|
| `docs/` | proposal, report, presentation, references |
| `simulation/` | Qucs-S projects, Python notebooks, result plots |
| `hardware/` | KiCad project, Gerbers, BOM, assembly notes |
| `firmware/` | dev-board, beacon and receiver firmware |
| `localization/` | path-loss and trilateration notebooks, RSSI data |
| `measurements/` | VNA (Touchstone), USRP and field-test data |

## Results
_To be added as measurements are completed._

## Team
_Add names and roles._

## Licenses
- Code (firmware, scripts, notebooks): MIT
- Hardware (schematics, PCB): CERN-OHL-P-2.0
- Documentation and figures: CC BY 4.0

Full texts are in `LICENSES/`.
