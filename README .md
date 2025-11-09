# Custom Bootloader for STM32F446RE

## Project Overview
A custom bootloader implementation for the STM32F446RE Nucleo board that enables dual-bank firmware operation. The bootloader manages two independent application images in Flash memory, allowing seamless switching and safe firmware updates.

## Key Features
- **Dual-Image Firmware Management**: Toggles between two application images stored at different Flash offsets
- **Memory Protection**: Robust memory mapping and boundary checks
- **Hardware Integration**: Developed for STM32F446RE Nucleo board
- **Bare-Metal Efficiency**: Optimized for minimal footprint and maximum performance
- **Safe Boot Process**: Verified application jumping with proper initialization

## Technical Specifications
- **Development Board**: STM32F446RE Nucleo
- **MCU**: STM32F446RET6 (ARM Cortex-M4 @ 180MHz)
- **IDE**: STM32CubeIDE
- **Programming Language**: Embedded C
- **Key Technologies**: Linker scripts, memory mapping, VTOR, Flash memory operations

## Project Structure
