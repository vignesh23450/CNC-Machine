# CNC Machine with GRBL Firmware

This project implements a CNC (Computer Numerical Control) machine using an Arduino Uno, CNC shield, motor drivers, and stepper motors. It utilizes the GRBL firmware for controlling the motion of the CNC machine.

## Components Used:
- Arduino Uno
- CNC Shield
- Stepper Motor Drivers (e.g., A4988 or DRV8825)
- Stepper Motors
- Power Supply
- Endstop Switches (optional)
- Computer with CNC Control Software (e.g., Universal G-Code Sender)

## Functionality:
- The CNC machine is capable of executing precise movements along multiple axes to carve, engrave, or mill various materials.
- The GRBL firmware translates G-code commands sent from a computer into stepper motor movements.
- The CNC shield provides a convenient interface for connecting stepper motor drivers and endstop switches to the Arduino Uno.
- Stepper motor drivers ensure accurate and controlled movement of the stepper motors.

## Assembly:
1. Mount the CNC shield onto the Arduino Uno.
2. Connect the stepper motor drivers to the appropriate slots on the CNC shield.
3. Connect the stepper motors to the stepper motor drivers.
4. If using endstop switches, connect them to the corresponding pins on the CNC shield.
5. Connect a power supply to the CNC shield to provide power to the stepper motors and other components.
6. Install and configure the GRBL firmware on the Arduino Uno using a computer.

## Usage:
1. Prepare your design using CAD (Computer-Aided Design) or CAM (Computer-Aided Manufacturing) software and generate G-code instructions.
2. Connect the CNC machine to a computer running CNC control software (e.g., Universal G-Code Sender).
3. Load your G-code file into the CNC control software.
4. Power up the CNC machine and ensure it is properly calibrated.
5. Home the CNC machine (if endstop switches are installed).
6. Set the origin (zero point) for your design.
7. Send the G-code commands from the control software to the CNC machine to execute your design.

## Safety Precautions:
- Always operate the CNC machine in a well-ventilated area.
- Ensure that all components are securely connected and fastened before operating the machine.
- Be cautious when handling sharp tools and moving parts.
- Familiarize yourself with emergency stop procedures in case of unexpected behavior.

## Contributing:
Contributions to this project are welcome! If you have ideas for improvements, additional features, or bug fixes, please feel free to open an issue or submit a pull request.

## License:
This project is licensed under the [MIT License](LICENSE).

