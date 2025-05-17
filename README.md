# LabVIEW Pulse Control System using PCI-CTR05

This project presents a LabVIEW-based pulse timing control system developed for precise pulse generation using the National Instruments PCI-CTR05 counter/timer board. The system enables the user to generate programmable +5V digital pulses through the board’s counter outputs, which are essential for coordinating high-speed switching and laser timing in experimental setups.

## 🔧 Key Features

- ✅ Pulse ON and OFF time control (separately adjustable)
- ✅ Initial delay setting before pulse generation starts
- ✅ User-controlled start/stop functionality
- ✅ GUI front panel for real-time interaction
- ✅ Supports up to 5 channels on the PCI-CTR05 board
- ✅ Can run multiple pulse channels in parallel

## 🎯 Applications

This LabVIEW pulse control system was used to:
- Precisely time the **ON and OFF cycles of high-voltage switches** in experimental circuits
- Control **laser pulse triggering** for **Time-of-Flight (TOF)** and **Inverted Field Time-of-Flight (IFTOF)** experiments on amorphous selenium (a-Se) photoconductors

The flexibility of this system allowed full synchronization between the laser source, HV switching, and data acquisition without needing manual intervention during the experiments.


### Front Panel GUI
User interface to input parameters and start/stop pulses:
![LabVIEW GUI](images/front_panel_gui.png)

## 📁 Folder Structure

