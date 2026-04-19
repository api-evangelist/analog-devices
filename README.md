# Analog Devices (analog-devices)
Analog Devices (ADI) is a global semiconductor company designing high-performance analog, mixed-signal, and digital signal processing integrated circuits for industrial, communications, automotive, and consumer markets. ADI provides developer tools through its CodeFusion Studio embedded development environment and the ADI Developer Portal. ADI's APIs are primarily embedded software APIs for microcontrollers and DSPs via the libiio library for Linux Industrial I/O devices, pyadi-iio Python interfaces, and security APIs within the ADI Assure Trusted Edge Security Architecture. The company also maintains the no-OS driver library for bare-metal embedded systems.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/analog-devices/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Embedded Systems, Hardware, IoT, Semiconductor, Signal Processing

## Timestamps

- **Modified:** 2026-04-19

## APIs

### Analog Devices libiio API
The libiio library provides a cross-platform C API for interfacing with Linux Industrial I/O (IIO) devices including ADCs, DACs, and RF transceivers. It supports local and remote device access via a network daemon, enabling developers to control ADI hardware from Linux and other host platforms.

**Human URL:** [https://analogdevicesinc.github.io/libiio/](https://analogdevicesinc.github.io/libiio/)

#### Tags:

 - Embedded Systems, Hardware Interface, IIO, Linux, Signal Processing

#### Properties

- [Documentation](https://analogdevicesinc.github.io/libiio/)
- [GitHubRepository](https://github.com/analogdevicesinc/libiio)

### Analog Devices PyADI-IIO Python API
PyADI-IIO provides Python interfaces for ADI hardware with IIO drivers, enabling Python developers to interact with ADI evaluation boards and production hardware. It abstracts libiio with device-specific high-level interfaces for transceivers, converters, and sensors.

**Human URL:** [https://analogdevicesinc.github.io/pyadi-iio/](https://analogdevicesinc.github.io/pyadi-iio/)

#### Tags:

 - ADC, Embedded Systems, Hardware, Python, RF

#### Properties

- [Documentation](https://analogdevicesinc.github.io/pyadi-iio/)
- [GitHubRepository](https://github.com/analogdevicesinc/pyadi-iio)
- [SDK](https://pypi.org/project/pyadi-iio/)

### Analog Devices CodeFusion Studio
CodeFusion Studio is ADI's embedded software development environment built on Visual Studio Code for ADI microcontrollers and DSPs. It provides graphical system configuration, code generation, debugging, and security APIs for the ADI Assure Trusted Edge Security Architecture. Initially supports MAX32690 and ADSP-SC5xx processor families.

**Human URL:** [https://developer.analog.com/solutions/codefusionstudio](https://developer.analog.com/solutions/codefusionstudio)

#### Tags:

 - Embedded Development, IDE, Microcontrollers, Security, VSCode

#### Properties

- [Documentation](https://developer.analog.com/solutions/codefusionstudio)
- [APIReference](https://developer.analog.com/docs/codefusion-studio/1.0.2/)
- [GitHubRepository](https://github.com/analogdevicesinc/codefusion-studio)
- [SDK](https://marketplace.visualstudio.com/items?itemName=AnalogDevices.cfs-ide)

## Common Properties

- [Portal](https://www.analog.com)
- [DeveloperPortal](https://developer.analog.com)
- [Documentation](https://www.analog.com/en/software.html)
- [GitHubOrganization](https://github.com/analogdevicesinc)
- [Blog](https://www.analog.com/en/resources/media-center/analog-dialogue.html)
- [Support](https://ez.analog.com/)
- [JSONSchema](json-schema/analog-devices-iio-device-schema.json)
- [JSONSchema](json-schema/analog-devices-iio-context-schema.json)
- [JSONLD](json-ld/analog-devices-context.jsonld)
- [Vocabulary](vocabulary/analog-devices-vocabulary.yaml)
- [SpectralRules](rules/analog-devices-spectral-rules.yml)

## Features

| Name | Description |
|------|-------------|
| Linux IIO Interface | libiio library for accessing Linux Industrial I/O devices over USB, network, and local interfaces. |
| Python Hardware Interfaces | PyADI-IIO provides Pythonic device-specific APIs for ADI transceivers, converters, and sensors. |
| Embedded Security APIs | ADI Assure security APIs for hardware root of trust, secure boot, and cryptographic operations. |
| No-OS Drivers | Bare-metal C drivers for ADI ICs without requiring an operating system. |
| CodeFusion Studio | VS Code-based IDE for ADI MCUs and DSPs with graphical configuration and code generation. |
| Open Source Ecosystem | Active contributor to Linux kernel IIO subsystem, Zephyr RTOS, and other open source projects. |

## UseCases

| Name | Description |
|------|-------------|
| Precision Measurement | High-accuracy data acquisition from ADI ADCs and sensors using libiio or PyADI-IIO. |
| RF and Communications | Control of RF transceivers like ADRV9002 and AD9361 for SDR and communications applications. |
| Industrial Automation | Integration of ADI industrial ICs into factory automation and process control systems. |
| Secure IoT Devices | Building secure edge devices with hardware root of trust using ADI Assure security APIs. |
| Motor Control | Developing motor drive applications using ADI ADSP processors and evaluation kits. |

## Integrations

| Name | Description |
|------|-------------|
| Linux Kernel IIO Subsystem | ADI actively contributes drivers to the Linux kernel IIO framework. |
| Zephyr RTOS | ADI maintains hardware support for ADI MCUs in the Zephyr real-time operating system. |
| GNU Radio | Integration with GNU Radio for software-defined radio applications using ADI transceivers. |
| MATLAB/Simulink | MathWorks toolbox support for ADI hardware for signal processing prototyping. |
| Microsoft Visual Studio Code | CodeFusion Studio is built as a VS Code extension for embedded development. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Analog Devices Iio Context Schema](json-schema/analog-devices-iio-context-schema.json)
- [Analog Devices Iio Device Schema](json-schema/analog-devices-iio-device-schema.json)

### JSON-LD

- [Analog Devices Context](json-ld/analog-devices-context.jsonld)

## Vocabulary

- [Analog Devices Vocabulary](vocabulary/analog-devices-vocabulary.yaml) — Taxonomy for ADI APIs covering IIO devices, embedded SDKs, and hardware interfaces

## Rules

- [Analog Devices Spectral Rules](rules/analog-devices-spectral-rules.yml) — Rules enforcing Analog Devices API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
