# Lenovo IdeaPad S145 (Ice Lake) Hackintosh


EFI para Lenovo IdeaPad S145 OpenCore Bootloader

(Compativel com Lenovo Ideapad S145, (i3 & i5 G1 / i7 1065G7*).

![Captura de Tela 2022-04-01 às 18 08 44](https://user-images.githubusercontent.com/84999586/161341590-b4616829-6a02-40b5-b331-b693067bc8fd.png)


### Laptop Especificações:


| Component        | Brank                              |
| ---------------- | ---------------------------------- |
|                                                       |
| CPU              | Intel i7 1065G7 (4C-8T 8MB ICL)    |
| iGPU             | Intel® Iris Plus Graphics          |
| Audio            | Realtek ALC230                     |
| Ram              | 20 GB DDR4 2667 Mhz                |
| Wifi + Bluetooth | BCM94360NG (Broandcom FENVI)       |
| SmBios           | MacBookPro 16,2                    |
| BootLoader       | OpenCore 0.8.0                     |
| macOS            | Monterey 12.3.1                    |


### O que funciona 100%?

- Intel Iris Plus iGPU - H264 & HEVC (excepto saída HDMI)
- Total ALC230 (Som e microfone)
- Sleep / Wake
- I2C Touchpad com gestos (ELAN & SYNA)(Modo Polling)
- Teclado (PS2)
- Teclas de brilho e volume
- Wi-Fi & Bluetooth BCM94360NG
- Leitor Micro SD 
- WebCam (Monterey quebrou varias Webcams se for seu caso conserto via ManyCam 240p)
- ACPI Bateria
- NVRAM (Nativa)
- Recovery (macOS) boot do OpenCore


### Special Config:

- Device ID nativo (0200518A) Fully Graphic and Sleep/Wake.
- USB port mapping performed
- [Maldon](olarila.com) ACPI fix

## Credits

- [Apple](https://apple.com/osx) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and some kexts
- [Mald0n](https://www.olarila.com/topic/9918-olarila-hackintosh-hackbook-lenovo-ideapad-s145-10th-gen-catalina-big-sur-monterey-full-dsdt-patches-clover-and-opencore) for EFI bases, Olarila Vanilla Images and Support!

## Tips

- Use ManyCam (ou um app de terceiro que permita alterar a resolução da WebCam para 240p) caso a camera perca suporte no Monterey.
- [BIOS MOD Tutorial](https://www.youtube.com/watch?v=i5AYuSpQNYY&t=0s) (<3 Mateus!)
- [HiDPI Retina Display](https://www.youtube.com/watch?v=_fNvIfPxOEA&t=0s)

## Warning

I am not responsible for any problem and/or damage to equipment or loss of files. Always back up everything before any changes to your computer
