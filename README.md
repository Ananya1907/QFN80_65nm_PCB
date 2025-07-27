# QFN80_65nm_PCB
This repository contains the PCB design files for a test board created to evaluate a QFN80 packaged integrated circuit. The board interfaces with an FPGA development board through a standard FMC (FPGA Mezzanine Card) connector.
Each PDF file includes the complete design documentation: the schematic, the PCB layout, and a 3D view of the assembled board.

## Repository Contents
* 'PCB_v1.pdf': Contains the complete design files for the first version of the test board.
* 'PCB_v2.pdf': Contains the complete design files for the revised, final version of the test board.
* 'PCB_v3.pdf': Contains the complete design files for an alternate version of the test board using a QFN socket.

## Design Versions

### Version 1 (PCB_v1.pdf)
This is the initial design, which functions as a carrier board. It's designed to accept a separate, smaller PCB module that already has the QFN80 IC mounted on it. The connection between the two boards is made using standard 4x20 female headers on this main test board.

### Version 2 (PCB_v2.pdf)
This is the revised, integrated version of the design. In this version, the QFN80 IC is intended to be soldered directly onto the test board. This approach eliminates the need for a separate module and headers, providing a more direct electrical connection for improved signal integrity and a more compact final assembly.

### Version 3 (PCB_v3.pdf)
This alternate version is designed for solderless testing by incorporating a QFN socket. This allows for the simple insertion and removal of different ICs, making it ideal for rapid, repeated, and non-destructive testing for smoother and more accurate evaluation.
