# IR Turret

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

IR Turret is a project that aims to create a turret controlled by infrared (IR) signals. It can be used for various applications such as security systems, remote control devices, or even as a fun DIY project.

## Features

- Control the turret using IR signals
- Adjustable rotation and elevation angles
- Support for different IR protocols
- Easy integration with other projects

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