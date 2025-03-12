# L2KiCad
Custom Symbol and Footprint libraries for KiCad

## How-To
To use the libraries you need to add them in KiCad.

Symbol library: `Preferences -> Manage Symbol Libraries... -> Add existing library to table -> L2KiCad_sch.kicad_sym`

Footprint library: `Preferences -> Manage Footprint Libraries... -> Add Existing -> L2KiCad_fp.pretty`

## Symbol library overview
| Symbol | Description | Why custom |
| --- | --- | --- |
| AL5081 | Linear LED Driver | Missing from KiCad standard libraries |
| AL8400 | Linear LED Driver | Missing from KiCad standard libraries |
| AP25810L | USB Type-C DFP Controller | Missing from KiCad standard libraries |
| BQ24618 | Li-Ion Battery Charger | Missing from KiCad standard libraries |
| BQ76925PW | Li-Ion Battery Monitor | Missing from KiCad standard libraries |
| Q_DUAL_NMOS_S1D1S2G2D2G1 | Dual NMOS | Custom pin configuration |
| Q_DUAL_NMOS_S1G1S2G2D2D2D1D1 | Dual NMOS | Custom pin configuration |

## Footprint library overview
| Footprint | Description | Why custom |
| --- | --- | --- |
| Switch_DPDT_MSS-22D18 | DPDT Switch | Missing from KiCad standard libraries |
| USB_C_Receptacle_GCT_USB4110_noNPTH | USB Type-C Connector | Removed PTH from component in KiCad standard library|
Vishay_VLRK31R1S2 | Vishay VLRK31R1S2 LED | Missing from KiCad standard libraries |