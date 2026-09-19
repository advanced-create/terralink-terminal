# Project TerraLink

TerraLink is an off-grid field terminal and communication baseboard designed to bridge a Raspberry Pi 5 with an ESP32 co-processor and an SX1262 LoRa module. It allows long-range mesh messaging, telemetry transfer, and offline field computing without cellular or internet connectivity.

## Hardware Features
- **Carrier Baseboard:** Custom 2-layer PCB designed in EasyEDA with dual-layer GND planes (0 DRC errors).
- **Communication Buses:** Dedicated hardware UART (Pi GPIO14/15 ⇄ ESP32 TX0/RX0) and high-speed SPI routing for SX1262 LoRa.
- **Power Delivery:** High-current 5V screw terminal input routed via wide traces to supply both boards cleanly.

## Design Previews
![Schematic](diagram.png)

## Bill of Materials (BOM)
| Item | Part / Description | Qty | Estimated Cost |
| :--- | :--- | :--- | :--- |
| 1 | Custom TerraLink Carrier PCB (JLCPCB 5pcs) | 1 set | ~$15 |
| 2 | Raspberry Pi 5 (4GB) | 1 | ~$60 |
| 3 | SX1262 LoRa SPI Module (868/915MHz) | 1 | ~$12 |
| 4 | Terminal Blocks & 2.54mm Pin Headers | 1 set | ~$5 |
| 5 | Rugged 3D Printed Enclosure & Hardware | 1 | ~$10 |
| **Total** | | | **~$102** |

## Build Roadmap
- [x] Milestone 1: Schematic design, routing, and DRC validation (Complete)
- [ ] Milestone 2: Order fabrication through Hack Club grant
- [ ] Milestone 3: ESP32 packet framing & LoRa SPI bridge firmware
- [ ] Milestone 4: CAD Enclosure integration with 5"/7" DSI Capacitive Touch Display & Field UI
- [ ] Milestone 5: CAD enclosure modeling and assembly
- [ ] Milestone 6: Pi terminal UI & offline data testing

## Bill of custom PCB
![BOM](BOM.png).

## 🧾 Bill of Materials (BOM)
![BOM](BOM.jpg).

ItemComponent / PartQtyPrice (INR)Price (USD)Source / Vendor
1Custom TerraLink Carrier PCB Fabrication + Shipping5 pcs₹1,270.00$15.00JLCPCB
2Raspberry Pi 5 Model (8GB RAM)1 unit₹19,999.00$236.67Robu.in
3Waveshare SX1262 LoRa HAT for Raspberry Pi (868MHz)1 unit₹2,699.00$31.94Robu.in
4ESP32-S3 DevKit (WROOM-1 N16R8 | 16MB Flash + 8MB PSRAM)1 unit₹839.00$9.93Robu.in
520cm 40-Pin Dupont Cables (M-M, M-F, F-F Combo Pack)1 pack₹129.69$1.53Robu.in
Total₹24,936.69~$295.00


## Creator

- Aryan Pandey (@Aryan on Hack Club Slack)
