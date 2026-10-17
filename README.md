# OpenDrive

**An open, modular platform for truck simulation telemetry, vehicle control, and driving automation.**

OpenDrive is a Windows desktop application developed primarily in C#, focused on building a comprehensive environment for telemetry, navigation, vehicle control, and driving automation in Euro Truck Simulator 2 (ETS2).

The project is designed with a modular architecture, independent processing logic, and dedicated systems for game integration, telemetry, navigation, automation, and diagnostics.

## Features

The following capabilities define the project's development scope:

- **Telemetry** — Real-time acquisition, processing, and validation of available simulator data.
- **Vehicle Control** — Steering, acceleration, braking, and transmission management.
- **Navigation** — Map processing, route planning, and trajectory generation.
- **Driving Automation** — Automated driving based on vehicle state, route geometry, and road conditions.
- **Automated Parking** — Parking-space selection, manoeuvre planning, and precision positioning.
- **Diagnostics** — Connection monitoring, fault detection, structured logging, and runtime status reporting.
- **Desktop Interface** — A dedicated Windows application for configuration, monitoring, and system operation.

These capabilities represent development objectives and will be marked as implemented only after verification.

## Technology Stack

| Component | Technology |
|---|---|
| Primary language | C# |
| Platform | Windows desktop |
| Initial simulator | Euro Truck Simulator 2 |
| Game integration | Supported telemetry interfaces and SDKs |
| Testing | Automated tests and in-game validation |

## Architecture

OpenDrive is intended to separate responsibilities into well-defined components:

- **Core** — Application lifecycle, configuration, and orchestration.
- **Game Integration** — Communication with the simulator.
- **Telemetry** — Data acquisition, validation, and state processing.
- **Controls** — Vehicle input and control management.
- **Navigation** — Map data, route planning, and trajectory generation.
- **Automation** — Driving and parking systems.
- **Diagnostics** — Logging, error handling, and runtime monitoring.
- **User Interface** — Desktop configuration and monitoring.

Components will be implemented as required by the system, avoiding unnecessary abstractions and incomplete modules.

## Development Principles

- Complete, integrated implementations.
- Reliable telemetry and predictable control behaviour.
- Robust error handling and safe failure states.
- Automated testing and validation in the simulator.
- Clear separation of responsibilities and maintainable code.
- AI-assisted development, code analysis, debugging, and testing.

## Project Status

**Early development.**

Initial development focuses on establishing reliable simulator integration and telemetry processing. Vehicle controls, navigation, driving automation, and automated parking will build on these foundations.

## Requirements

- Windows desktop environment.
- Euro Truck Simulator 2 for simulator integration and in-game testing.
- Additional SDKs and dependencies as documented during implementation.

## Building from Source

Build instructions and dependency requirements will be documented once the initial project structure is established.

## License

See the [`LICENSE`](LICENSE) file for licensing terms.

## Disclaimer

OpenDrive is an independent software project and is not affiliated with, endorsed by, or officially supported by SCS Software.

Euro Truck Simulator 2 is a trademark of its respective owner. Third-party components remain subject to their respective licenses.

---

**OpenDrive — Open engineering for truck simulation.**