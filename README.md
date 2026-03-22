# ST-Link_V2.1

<p align="center">
  <img src="1-1.jpg" height="300"/>
</p>

One more ST-Link v2.1 design.
Key Features
  - Virtual COM Port (VCP): The most notable addition; it provides a hardware UART-to-USB bridge, allowing you to use a single USB cable for both   - debugging/programming and serial terminal communication with the target MCU.
  - USB Mass Storage Class (MSC): The device appears as a USB drive on your PC. You can flash a binary file to the microcontroller simply by dragging and dropping it into this "drive".
  - USB Power Management: Supports requesting more than 100 mA from the host PC to power the application board.
SWO Support: Includes a Serial Wire Output (SWO) pin for real-time trace debugging, which is often missing on common "dongle" clones of the V2.
