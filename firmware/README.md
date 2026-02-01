# Firmware

ESP32-based firmware for PadProxy.

## Structure

- `src/` - Source code
- `include/` - Header files

## Features

- Bluetooth gamepad pairing and connection
- USB HID device emulation (gamepad proxy to PC)
- WiFi configuration portal
- PC power management (Wake-on-LAN, power button control)
- OTA firmware updates

## Building

This project uses PlatformIO. To build:

```bash
cd firmware
pio build
```

To flash:

```bash
pio upload
```

## Configuration

WiFi and pairing settings are stored in NVS (Non-Volatile Storage) and can be configured via:
- Initial setup portal (AP mode)
- Web interface
- Serial commands

## Dependencies

- ESP-IDF (via PlatformIO)
- Bluepad32 (Bluetooth gamepad library)
- TinyUSB (USB HID implementation)
