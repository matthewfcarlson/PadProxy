# PCB Design

KiCad project files for the PadProxy hardware.

## Board Features

- ESP32-S3 microcontroller (USB OTG support)
- USB-C connector for PC connection
- External WiFi/BT antenna connector (U.FL/IPEX)
- PC power header (ATX front panel connector compatible)
- Status LEDs
- Optional OLED display header
- Compact form factor for internal PC mounting

## Files

- `PadProxy.kicad_pro` - KiCad project file
- `PadProxy.kicad_sch` - Schematic
- `PadProxy.kicad_pcb` - PCB layout
- `gerbers/` - Manufacturing files
- `bom/` - Bill of materials

## Manufacturing

Gerber files are provided for PCB fabrication. The design is optimized for:
- 2-layer PCB
- Standard 1.6mm thickness
- HASL or ENIG finish

## Assembly

See `bom/` for component list and placement files for automated assembly.
