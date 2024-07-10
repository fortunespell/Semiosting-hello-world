# Semiosting-hello-world-
# STM32 F767ZI Semihosting Example

This repository contains an example project for the STM32 F767ZI microcontroller to demonstrate semihosting by printing "Hello, World!" to the debug console.

## Prerequisites

- **STM32CubeIDE**: Download and install from [ST's website](https://www.st.com/en/development-tools/stm32cubeide.html).
- **GNU Arm Embedded Toolchain**: Download from [Arm's website](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm).
- **OpenOCD**: Ensure it is installed and configured properly.

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/stm32f767zi-semihosting-example.git
cd stm32f767zi-semihosting-example


2. Open the Project in STM32CubeIDE
Open STM32CubeIDE.
Select File > Open Projects from File System....
Browse to the cloned repository and open it.
3. Configure Semihosting
Open main.c in the Src directory.
Ensure your main.c looks like this:
