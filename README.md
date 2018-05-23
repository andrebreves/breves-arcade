# breves-arcade

## Features
* __Form Factor__: Bartop
* __Main Screen__: 19" LCD 1280x1024
* __Dynamic Marquee__: 2 x 9" LCD 800x480
* __Input__: 

---

## Components
* __Raspberry Pi 3__: main board, runs the emulator
* __Raspberry Pi Zero__: 
* __LCD Driver__:
* __Arduino Nano__:
* __Controller Interface__:
* __Sound Amplifier__:

---
## Power Comsuption

| Component         | Power   | Count     | Total     |
| ----------------  | ------: | --------: | --------: |
| Raspberry Pi 3    | 2.50A   |    x  1   | 2.50A     |
| Raspberry Pi Zero | 1.20A   |    x  2   | 2.40A     |
| LCD Driver        | 1.00A   |    x  2   | 2.00A     |
| Arduino Nano      | 0.50A   |    x  1   | 0.50A     |
| Adressable LED    | 0.06A   |    x 20   | 1.20A     |
| Sound Amplifier   | 1.20A   |    x  1   | 1.20A     |
|                   |         | __Total__ | __9.80A__ |

## USB Hub Connections

| Port  | Component         | Power | Data  |
| :---: | ---               | :---: | :---: |
| Uplink| Raspberry Pi 3    |       | __X__ |
| 1     | Raspberry Pi Zero | __X__ | __X__ |
| 2     | Raspberry Pi Zero | __X__ | __X__ |
| 3     | Arduino Nano      | __X__ | __X__ |
| 4     | Raspberry Pi 3    | __X__ |       |
| 5     | LCD Driver        | __X__ |       |
| 6     | LCD Driver        | __X__ |       |
| 7     | Sound Amplifier   | __X__ |       |
| 8     | LED Strip         | __X__ |       |

## Raspberry Pi 3 USB Connections
Port  | Component
:---: | ---
1     | Hub Uplink
2     | Controller Interface
3     | External Connector
4     | External Connector