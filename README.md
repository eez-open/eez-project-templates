# EEZ Project Templates

Official project templates repository for [EEZ Studio](https://github.com/eez-open/studio).

## Overview

This repository contains starter templates used by EEZ Studio when creating new projects. These templates provide pre-configured project structures for various project types.

## Available Templates

| Template | Description |
|----------|-------------|
| **Dashboard** | Interactive dashboard projects for T&M, data visualization and control |
| **EEZ-GUI (Firmware)** | Embedded GUI projects using EEZ Framework |
| **LVGL** | Projects using the LVGL graphics library |
| **LVGL with EEZ Flow** | LVGL projects with EEZ Flow visual programming |
| **IEXT** | Instrument extension projects (SCPI and Proprietary) |
| **BB3 Applet** | Applet projects for EEZ BB3 modular test bench |
| **BB3 MicroPython Script** | MicroPython script projects for EEZ BB3 |

## Usage

### Online (Default)

EEZ Studio automatically fetches templates from this repository when creating new projects. No additional setup is required.

### Local Templates

For offline development or custom template modifications, you can use a local copy:

1. Clone this repository:
   ```bash
   git clone https://github.com/eez-open/eez-project-templates
   ```

2. In EEZ Studio, go to **Settings** → **Project Templates**

3. Enable **"Use local templates folder"**

4. Select the path to your cloned repository

> **Note:** When updating EEZ Studio, make sure to pull the latest changes from this repository to ensure template compatibility:
> ```bash
> git pull
> ```

## Related Projects

- [EEZ Studio](https://github.com/eez-open/studio) - Cross-platform visual development tool
- [EEZ Project Examples](https://github.com/eez-open/eez-project-examples) - Example projects and demos
- [EEZ Framework](https://github.com/eez-open/eez-framework) - Embedded GUI framework

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.
