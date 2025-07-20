**Pong Game on RISC-V (Nios V) | DE1-SoC FPGA** 


**1. Overview**

This is a fully functional Pong game developed in C, running on a RISC-V (Nios V) soft-core processor implemented on the DE1-SoC FPGA development board. Designed for smooth real-time gameplay, the project demonstrates tight hardware-software integration in an embedded systems environment.


**2. Techbase**

Language: C

Processor: RISC-V (Nios V)

Platform: DE1-SoC FPGA Board


**3. Interfaces Used:**

- VGA (graphics output)

- PS/2 (keyboard input)

- Audio (game sounds)

- LEDs & 7-segment displays (scoreboard)
  
**4. Features**

- VGA-rendered Pong gameplay with real-time paddle and ball motion

- Keyboard-based paddle control via PS/2 interface

- Score displayed using on-board LEDs and HEX displays

- Sound effects triggered on point and game-over via audio out

- Optimized for low-latency and responsiveness on embedded hardware

**5. Deployment Instructions**

_▶ To run on DE1-SoC Board_

1. Load the Nios V processor on the FPGA using Quartus

2. Compile and upload the C project using the Intel Monitor Program or Nios II Command Shell

3. Connect a PS/2 keyboard, VGA monitor, and audio out

4. Run the program — play begins immediately after reset

_▶ Run on CPUlator (Web-based Simulator)_

Try it directly in your browser:
1.  Launch on CPUlator (RISC-V DE1-SoC): https://cpulator.01xz.net/?sys=rv32-de1soc

2. Select **C** from the language dropdown

3. Upload the code (.c file)

4. Click **Compile and Load**
5. Click **Continue**
6. Output will appear on the righthand side of the screen (VGA output)
