# SplitCodeBoard

SplitCodeBoard is a split keyboard with a macropad designed for programming. I made this because I do not have any good keyboards at home, and the idea of a split keyboard appealed to me. 
SplitCodeBoard was made as part of Hack Club Stasis. "SplitCodeBoard.step" is the PCB STEP, the pcb with case is in 'SplitCodeBoard.step_STEP.zip'.
Here are some images: <br>
Macropad:<br>
<img width="859" height="750" alt="Screenshot 2026-03-31 at 4 16 33 pm" src="https://github.com/user-attachments/assets/164359b4-697d-4a40-8b0e-19f0bc39bb4f" /><br>
Left keyboard half:<br>
<img width="512" height="368" alt="Screenshot 2026-03-31 at 4 17 09 pm" src="https://github.com/user-attachments/assets/f880b300-74ff-4596-9736-bbc60f897dcc" /><br>
Right keyboard half:<br>
<img width="484" height="417" alt="Screenshot 2026-03-31 at 4 17 52 pm" src="https://github.com/user-attachments/assets/a43d00a6-9cfc-41c6-b825-f369c57cd915" /><br>
Side schematic:<br>
<img width="1167" height="821" alt="Screenshot 2026-03-31 at 4 19 14 pm" src="https://github.com/user-attachments/assets/6db670b8-36cb-4341-a1ed-0d59901017c8" /><br>
Main and macropad schematic:<br>
<img width="741" height="520" alt="Screenshot 2026-03-31 at 4 18 46 pm" src="https://github.com/user-attachments/assets/8bcac824-548d-4cc4-bd40-bc557158bf5b" /><br>
PCB:<br>
<img width="950" height="666" alt="Screenshot 2026-03-31 at 4 20 12 pm" src="https://github.com/user-attachments/assets/21b6dd03-aff5-4d1d-903d-416c9824cc86" /><br>

## BOM
| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|------|---------|----------|------------------|------|-------------|
| MCP23017-E/SO | GPIO expansion for the nRF52840 on the keyboard sides | 2 | 3.24 | [Link to listing](https://www.digikey.com/en/products/detail/microchip-technology/MCP23017-E-SO/894271) | Digikey |
| Seeed Xiao nRF52840 | Microcontrollers | 3 | 48.54 | [Link to listing](https://www.digikey.com.au/en/products/detail/seeed-technology-co-ltd/102010448/16652893?srsltid=AfmBOopCoDCC1iggG736AFU-o5CQ8K0FazSBUvREHLvtvnr260xrHbc02Ug) | Digikey |
| Kailh PG1350 Choc V1 70PCS Mechanical Keyboard Switch Kailh Low Profile Switches Chocolate Mechanical Keyboard Switch RGB SMD 5-Pin Kailh Switches | Switches for the keyboard | 1 | 49.98 | [Link to listing](https://snapklik.com/en-au/product/kailh-pg1350-choc-v1-70pcs-mechanical-keyboard-switch-kailh-low-profile-switches-chocolate-mechanical-keyboard-switch-rgb-smd-5-pin-kailh-switches-dark-blue-70pcs/0W3L4PV7UIYW5) | Snapklik |
| Kailh Choc Hotswap Sockets (Pack of 10) | Hotswap sockets for the keys | 7 | 24.5 | [Link to listing](https://keebd.com/products/kailh-choc-hotswap-sockets?variant=40393453338776&country=AU&currency=AUD) | KEEBD |
| PURFIELD 3.7V 501012 401010 401012 400909 Polymer Lithium Battery Suitable for I7 i8 i9 i10 Earphone Headset MP3 MP4 Toy GPS | Batteries for each half of the keyboard | 20 | 21.2 | [Link to listing](https://www.aliexpress.com/item/1005008747431465.html) | Aliexpress |
| 1N5819HW-7-F | Diodes for the key matrix | 70 | 17.15 | [Link to listing](https://www.digikey.com.au/en/products/detail/diodes-incorporated/1N5819HW-7-F/814970) | Digikey |

## Licensing

This repository uses split licensing by content type:

- Firmware and firmware configuration (for example, files under `zmk-config/`) are licensed under GNU Affero General Public License v3.0 only (`AGPL-3.0-only`).
- Hardware design files (for example, KiCad schematics/PCBs, footprints, and 3D mechanical files) are licensed under CERN Open Hardware Licence Version 2 - Strongly Reciprocal (`CERN-OHL-S-2.0`).

See the root `LICENSE` file for full licensing scope and notices.

