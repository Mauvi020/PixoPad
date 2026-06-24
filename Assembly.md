🔧 Assembly Guide

This project does not require a PCB.

The SpaceDuckiPad is completely hand-wired using jumper wire or 30AWG wire.

The case consists of a main enclosure and a removable bottom plate. All components are installed and wired from the bottom before attaching the bottom plate.

⸻

🖥️ ST7735 TFT Display

Display Pin	ESP32-S3 Pin
VCC	3V3
GND	GND
SCL	GPIO12
SDA	GPIO11
CS	GPIO10
DC	GPIO14
RES	GPIO21
BLK	3V3

⸻

🎛️ KY-040 Rotary Encoder

Encoder Pin	ESP32-S3 Pin
VCC	3V3
GND	GND
CLK	GPIO4
DT	GPIO5
SW	GPIO6

⸻

⌨️ Button Wiring

Connect one side of each switch to the GPIO pin and the other side to GND.

Button	GPIO
1	GPIO1
2	GPIO2
3	GPIO3
4	GPIO7
5	GPIO15
6	GPIO16
7	GPIO17
8	GPIO18
9	GPIO40

💡 All button GND pins can be connected together and routed to a single GND pin on the ESP32-S3.

⸻

🔨 Assembly

1. Insert all 9 switches into the case.
2. Install the rotary encoder.
3. Install the ST7735 display.
4. Place the ESP32-S3 inside the enclosure.
5. Solder all display connections.
6. Solder all encoder connections.
7. Solder all switch connections.
8. Connect all GND wires together.
9. Check all wiring.
10. Organize the wires inside the case.
11. Attach the bottom plate.
12. Secure the bottom plate with screws.
13. Install the keycaps.
14. Upload the firmware.

⸻

📦 Downloads

Case Files
(comming soon)
Firmware
<a href="LINK_ZUR_FIRMWARE.cpp" download>
    <button>⬇ Download Firmware</button>
</a>

⸻

🦆 Case Design

* One-piece enclosure
* Removable bottom plate
* No PCB required
* Fully hand-wired
* Components installed from the bottom
* Designed for ESP32-S3

⸻

# 📧 Contact

support.mauvi@gmail.de



Made with 💙 by Mauvi020