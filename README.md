# Semiosting-hello-world
# NUCLEO F767ZI Semihosting Example

This repository contains an example project for the NUCLEO F767ZI microcontroller to demonstrate semihosting by printing "Hello, World!" to the debug console.

![image](https://github.com/user-attachments/assets/c9cb8b23-7e30-4f09-a817-686de9f89243)

## Prerequisites

- **STM32CubeIDE**: Download and install from [ST's website](https://www.st.com/en/development-tools/stm32cubeide.html).
- **GNU Arm Embedded Toolchain**: Download from [Arm's website](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm).
- **OpenOCD**: Ensure it is installed and configured properly.
## Development Environment
### Software

Windows 10

STM32CubeIDE v1.13.2

FreeRTOS v20

### Hardware
SWD debugger

NUCLEO-F767ZI

## Getting Started

### 1. Clone the Repository

### 2. Open the Project in STM32CubeIDE
Open STM32CubeIDE.

Select File > Open Projects from File System....

Browse to the cloned repository and open it.


### 3. Configure Semihosting
Open main.c in the Src directory.

Ensure your main.c looks like above repo...


### 4. Build and Debug
Click on the build button (hammer icon) to compile the project.

Click on the debug button (bug icon) to start a debug session.

Ensure semihosting is enabled in the debugger configuration:

Go to Run > Debug Configurations....
Select GDB OpenOCD Debugging.

### 5. Run the Program
Start the debug session.
Open the console to see the "hello world" message.

![image](https://github.com/user-attachments/assets/ad19092e-28bd-4427-95cb-da80e21eae65)
