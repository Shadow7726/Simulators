| Simulator Name            | Platform     | Description                                                               | Source/Link                                                       |
|---------------------------|--------------|---------------------------------------------------------------------------|-------------------------------------------------------------------|
| ModbusPal                  | Windows/Linux | Free and open source Modbus simulator. Supports TCP, RTU, and ASCII.     | [ModbusPal](https://www.modbustools.com/modbuspal.html)           |
| Modbus Poll                | Windows      | Free basic Modbus master simulator from Real Time Automation. TCP only.  | [Modbus Poll](https://store.chipkin.com/products/modbus-poll)    |
| QModMaster                 | Windows      | Free and open source Modbus simulator with a graphical interface.        | [QModMaster](http://qmodmaster.sourceforge.net/)                 |
| modbus-tk                  | Linux        | Python Modbus toolkit with simulator. Open source under LGPL license.    | [modbus-tk](https://github.com/ljean/modbus-tk)                  |
| mbserver                   | Linux        | Open source Modbus server in C. Supports TCP and RTU slave simulation.  | [mbserver](https://github.com/stephane/mbserver)                |
| pyModbus                   | Linux        | Python Modbus library. Includes modbus simulator example. MIT licensed. | [pyModbus](https://github.com/pymodbus/pymodbus)                |
| CAS Modbus Scanner         | Windows/Linux | Free scanning and simulation tool. Closed source freeware.              | [CAS Modbus Scanner](https://www.chipkin.com/cas-modbus-scanner/) |
| ModbusPal                  | Windows/Mac/Linux | Open source. Works on Windows, MacOS, Linux. Full-featured simulator.  | [ModbusPal](https://www.modbustools.com/modbuspal.html)           |

---

# ModbusPal - Modbus Slave Simulator

**Overview:**
ModbusPal is a free and open-source Java application designed to simulate Modbus slave devices. It serves as a valuable tool for testing, debugging Modbus masters, and creating training environments for Modbus users. ModbusPal supports both TCP/IP and serial communication.

## Complete Usage Guide:

**1. Download and Install ModbusPal**

- Download the latest version from SourceForge: [ModbusPal Releases](https://sourceforge.net/projects/modbuspal/files/)
- Extract the downloaded file to a directory on your computer.
- Launch the application by double-clicking `ModbusPal.jar`.

**2. Configure a Modbus Slave**

- Click the "Add Slave" button in the main window.
- Enter slave details in the "Add Slave" dialog:
  - Slave ID: Address of the Modbus slave device.
  - Protocol: Communication protocol (TCP/IP or serial).
  - Port: Port number for TCP/IP communication.
  - Serial Settings: Settings for serial communication.
- Click "Add" to create the slave device.

**3. Add Modbus Registers and Coils**

- Select the configured slave in the main window.
- Click "Add Holding Register" or "Add Coil" to add register or coil.
- Provide details in the dialog:
  - Address: Address of the register or coil.
  - Initial Value: Initial value of the register or coil.
  - Data Type: Data type (e.g., int, float, string).
  - Automation: Optional script for value automation.
- Click "Add" to create the register or coil.

**4. Start the Simulation**

- Click "Run" in the main window to start the Modbus slave simulation.
- Connect a Modbus master to read or write registers and coils.

**5. Stop the Simulation**

- Click "Stop" in the main window to halt the Modbus slave simulation.

## Additional Features:

- Supports various data types: integers, floats, strings, and booleans.
- Simulates holding registers, input registers, discrete coils, and analog inputs.
- Supports read and write operations.
- Automation using Python scripts.
- Logs Modbus traffic for debugging.

## Additional Tips:

- Ensure correct Modbus libraries are installed.
- Use meaningful names for slaves, registers, and coils.
- Document your Modbus simulation environment.
- Thoroughly test before deploying in a production environment.

