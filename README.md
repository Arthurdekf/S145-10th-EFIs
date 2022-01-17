# Lenovo IdeaPad S145 (Ice Lake) Hackintosh


EFI for Lenovo IdeaPad S145 OpenCore bootloader

(Compatible for Lenovo Ideapad S145, (i3 G1 - i5 G1 - i7 G7) these laptops use the same bios file).

### Computer Spec:


| Component        | Brank                              |
| ---------------- | ---------------------------------- |
|                                                       |
| CPU              | Intel i7 1065G7 (4C-8T 8MB ICL)    |
| iGPU             | Intel® Iris Plus Graphics          |
| Audio            | Realtek ALC230                     |
| Ram              | 20 GB DDR4 2667 Mhz                |
| Wifi + Bluetooth | BCM94360NG (Broandcom FENVI)       |
| SmBios           | MacBookAir 9,1                     |
| BootLoader       | OpenCore 0.7.8                     |
| macOS            | Monterey 12.1                      |


### What works on this EFI??

- Intel Iris Plus iGPU - H264 & HEVC
- Full ALC230 (Sound and microphone)
- ACPI correction SpeedStep / Sleep / Wake
- I2C Touchpad with gesture (ELAN and SYNA)
- Keyboard (PS2)
- Keyboard shortcuts (Sound and screen brightness)
- Native Wi-Fi and Bluetooth BCM94360NG
- Micro SD Cardreader (USB mapping)
- WebCam (USB Mapping)
- AppleSMC chip emulation (thanks to VirtualSMC)
- ACPI Battery
- NVRAM (Native)
- Recovery (macOS) boot from OpenCore


### Special Config:

- USB port mapping performed
- [Maldon](olarila.com) ACPI fix

## Credits

- [Apple](https://apple.com/osx) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and some kexts
- [Mald0n](https://www.olarila.com/topic/9918-olarila-hackintosh-hackbook-lenovo-ideapad-s145-10th-gen-catalina-big-sur-monterey-full-dsdt-patches-clover-and-opencore) for EFI bases, Olarila Vanilla Images and Support!

## Tips

- Use ManyCam to use your WebCam's full performance
- [Bios Mod Tutorial](https://www.youtube.com/watch?v=i5AYuSpQNYY&t=0s) (thanks Mateus!)
- [Active Retina Display](https://www.youtube.com/watch?v=_fNvIfPxOEA&t=0s)

## Warning

I am not responsible for any problem and/or damage to equipment or loss of files. Always back up everything before any changes to your computer
