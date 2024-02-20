# device-dumps
Firmware, utilities, and documents for various electronic devices and their chipsets

## License

GPL-3.0, but note that it only applies to files I created (i.e. not any .bin files or other firmware dumps - those retain the rights of their respective owners).

## Table of Devices

| Manufacturer | Model | Relevant Chip(s) | Dump Method | Contents |
| ------------ | ----- | ---------------- | ----------- | -------- |
| Monoprice | Blackbird KVM 42643 | ASIX AX68002                                        | Header pins on powered device in ISP mode, FT232R UART adapter, custom Python script | Internal flash, Python dump script |
| Monoprice | Blackbird KVM 42643 | VIA Labs VL817-Q7, H&M Semi/Bright Moon Semi T25S40 | SOIC8 clip on unpowered device, FT232H SPI adapter, flashrom (modified!) | External flash |

