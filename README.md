# RAGE (Rapid Automated Gateway Exploiter)

RAGE is a lightweight, ultra-fast local gateway analysis and automated routing emulation tool written in modern C++. Built for raw speed and terminal efficiency, it automates the evaluation of network exit nodes and yields performance security metrics directly inside the console.

## Features
- **Rapid Gateway Auditing:** Automatically evaluates local routing vectors and response times.
- **Automated Processing Loops:** Simulates parallel node checks with low microsecond overhead.
- **Zero Framework Footprint:** Compiled as a static, self-contained binary for extreme mobility.
- **Clean Architecture:** Written using explicit Allman-style formatting and localized namespaces.

## Usage
Run the executable with an optional target gateway IP address to initiate the automated exploitation sequence:
```bash
./rage 192.168.1.254
```

## Architecture & Style
RAGE strictly follows the **KISS** (Keep It Simple, Stupid) principle and is optimized for low memory usage. The codebase uses the Allman style for bracket alignment, ensuring high readability and seamless minification for single-line deployment architectures.

## License
This project is open-source and licensed under the **GNU GPL v3.0**. See the LICENSE file for details. All rights reserved by **hypernova-developer**.
