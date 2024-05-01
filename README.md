# IR Turret

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

IR Turret is an unofficial based on the Crunch Labs Hackpack project that aims to create a turret controlled by infrared (IR) signals. It can be used for various applications such as security systems, remote control devices, or even as a fun DIY project.

## Purpose

For those who have already leveled up and want to push even further, you may find the web-based IDE a bit stifling. Environments like [platform.io](https://platformio.org) provide a more advanced development experience with features like advanced code editing, debugging, and library management.

I have made some modifications to the basic code for fun but it has been tested on the IR turret robot provided in the first hackpack box.  That said, your mileage may very and I provide no garantees or liability for damage to  your device.  Legal business aside, have fun and be safe!

## Features

- Control the turret using IR signals
- Adjustable rotation and elevation angles
- Support for different IR protocols
- Easy integration with other projects

## Crunch Labs

[![IR Turret Demo](https://img.youtube.com/vi/1j1kAuqePJo/0.jpg)](https://www.youtube.com/watch?v=1j1kAuqePJo)

## Getting Started

### Prerequisites

- PlatformIO installed on your system
- IR receiver and transmitter modules
- Servo motors for turret rotation and elevation
- Arduino or compatible microcontroller

### Installation

1. Clone the repository: `git clone https://github.com/foomoon/ir-turret.git`
2. Change to the project directory: `cd ir-turret`
3. Build the project: `platformio run`
4. Upload the firmware to your microcontroller: `platformio run --target upload`

### Usage

1. Connect the IR receiver and transmitter modules to your microcontroller according to the pin configuration in the code.
2. Power up the system and ensure that the turret is properly assembled and connected.
3. Use an IR remote control to send commands to the turret and observe its movement.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

