# Lesion OS — Device Updates

Official public firmware download directory for **Lesion OS**.

**Source code repositories are separate and may remain private.** This repository hosts only published firmware packages, update manifests, and device-specific installation instructions.

## Supported devices

| Manufacturer | Exact hardware model and revision | Firmware and instructions |
| --- | --- | --- |
| Waveshare | **ESP32-S3-ePaper-1.54G V2** | [Waveshare ESP32-S3-ePaper-1.54G V2](waveshare-esp32-s3-epaper-1.54g-v2/README.md) |

## Firmware safety

- Download firmware only for the **exact manufacturer, model, and hardware revision** printed on your device.
- Do not interchange firmware between similarly named Waveshare 1.54-inch models.
- A device-specific manifest must identify the exact compatible hardware and firmware version.
- No firmware is published until its build and compatibility checks have been verified.
- USB installation images and OTA application images are different; follow the instructions for the exact device.

## Repository layout

Each supported hardware model gets its own clearly named directory with a README, update manifest, and firmware releases. The directory name must include the **full hardware model and revision**.

> **Status:** Update delivery infrastructure is being prepared. No firmware download is available from this repository yet.
