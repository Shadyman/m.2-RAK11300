# RAK11300 LoRa Module on m.2 Key A-E

This is a board in the _m.2 Key A-E_ form factor to allow the use of the [RAK11300](https://docs.rakwireless.com/Product-Categories/WisDuo/RAK11300-Module/) module. 

RAK11300 contains an RP2040 microcontroller, an SX1262 and supporting circuitry on a castellated green PCB. The RAK11300 provides 8xx-9xxMhz-Band communications, depending on the model used. The RAK11300L variant may be substituted, and operates on 433 or 470 Mhz depending on the model.

# m.2 Pins Used
- PERST0n
- Vendor-Defined 38,40,42
- W_DISABLEn
- LED_1n
- LED_2n
- USB+/-

# RAK11300 Pins Used
- RESETn
- BOOT
- SWCLK/SWDIO
- GPIO6, 9, 22, 23, 24
- USB_DP/_DM

# Project Status
- [x] Schematic Creation
- [ ] PCB Creation
  - [X] PCB Layout
  - [ ] TODO: Verify BOOT/SWCLK/SWDIO pinout vs other modules for ease of use
  - [ ] TODO: Calculate LED series resistors where needed
- [ ] Initial PCB Test Run
  - [ ] Finalize BOM
  - [ ] Assembly
- [ ] PCB Testing

# References
- [RAK11300 Item Page - RAK Store](https://store.rakwireless.com/products/wisduo-lpwan-module-rak11300)
- [RAK11300 WisDuo LPWAN Module - Reference Documents](https://docs.rakwireless.com/Product-Categories/WisDuo/RAK11300-Module/Overview/)
  - Backup snapshot of reference documents and .STL file available in /Documents/
- [SX1262 Product Page - Semtech](https://www.semtech.com/products/wireless-rf/lora-connect/sx1262)
