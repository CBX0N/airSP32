---
layout: page
title: Getting Started
---

## Prerequisites

- ESP32 development board
- Air suspension hardware
- USB cable
- Flashing tool (e.g., esptool.py)

## Flash the Firmware

```bash
esptool.py --chip esp32 --port /dev/ttyUSB0 write_flash -z 0x1000 firmware.bin
```

## Connect the Hardware

Wire up valves, sensors, and the compressor as shown in the docs.
