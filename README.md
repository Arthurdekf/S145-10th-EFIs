# Lenovo IdeaPad S145 (Ice Lake) Hackintosh


EFI para Lenovo IdeaPad S145 OpenCore bootloader

(Compatible for Lenovo Ideapad S145, (i3 G1 - i5 G1 - i7 G7) these laptops use the same bios file).

### Computer Spec:

| Component        | Brank                              |
| ---------------- | ---------------------------------- |
| CPU              | Intel i7 1065G7 (4C-8T 8MB ICL)    |
| iGPU             | Intel® Iris Plus Graphics          |
| Audio            | Realtek ALC230                     |
| Ram              | 20 GB DDR4 2667 Mhz                |
| Wifi + Bluetooth | BCM94360NG (Broandcom FENVI)       |
| SmBios           | MacBookAir 9,1                     |
| BootLoader       | OpenCore 0.7.8                     |
| macOS            | Monterey 12.1                      |


### What works and What doesn't or WIP:

- [ ] Intel Iris Plus iGPU HDMI Output (Not supported at the moment)
- [x] Intel Iris Plus iGPU - H264 & HEVC
- [x] ALC230 Internal Speakers
- [x] ALC230 Internal microphone
- [x] SpeedStep / Sleep / Wake
- [x] I2C Touchpad with gesture (ELAN and SYNA)
- [x] Keyboard (PS2-Internal)
- [x] F11 & F12 Brightness Key
- [x] F1 & F2 & F3 Sound Key
- [x] Wi-Fi and Bluetooth BCM94360NG
- [x] Micro SD Cardreader (USB-Internal)
- [x] WebCam (USB-Internal)( Se tiver problemas baixe o ManyCam e defina para 240p).
- [x] All Sensors CPU, IGPU, BATTERY, NVME, FAN
- [x] ACPI Battery
- [x] NVRAM (Native)
- [x] Recovery (macOS) boot from OpenCore


### Special Config:

- Usb port mapping performed
- DSDT mald0n

## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html)
- [Mald0n(Olarila)] (https://www.olarila.com/topic/9918-olarila-hackintosh-hackbook-lenovo-ideapad-s145-10th-gen-catalina-big-sur-monterey-full-dsdt-patches-clover-and-opencore
