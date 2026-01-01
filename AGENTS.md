# Repository Guidelines

## Project Structure & Module Organization
```
. 
├─ hardware/        # 3‑D models and Arduino sketch
│   ├─ 3d-models/  # STL / PNG files for the shell
│   └─ ble-gamepad/ble-gamepad.ino  # ESP32‑C3 firmware
├─ images/          # Photos used in documentation
└─ software/        # Python OBS controller C# application
```
Source code lives under `software/`; tests (if added) should mirror this layout.

## Coding Style & Naming Conventions
* Indentation: 4 spaces, no tabs.
---
These guidelines aim to keep contributions consistent and the repo easy to navigate. Feel free to suggest improvements via issues or PRs.
