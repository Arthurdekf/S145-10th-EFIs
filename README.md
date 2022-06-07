# Lenovo IdeaPad S145 (Ice Lake) Hackintosh


EFI para Lenovo IdeaPad S145 OpenCore Bootloader

(Compativel com Lenovo Ideapad S145, (i3 & i5 UHD / i7 1065G7 Iris*).

![Screen Shot 2022-06-07 at 14 29 08 1](https://user-images.githubusercontent.com/84999586/172447015-c643260e-1ccc-43ee-9e04-3fe7ed32e4f7.png)


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
| BootLoader       | OpenCore 0.8.2                     |
| macOS            | Ventura 13.0.                      |


### O que funciona 100%?

- iGPU (excepto saída HDMI)
- Total ALC230 (Som e microfone) ALC ID layout 20
- Sleep / Wake
- I2C Touchpad com gestos (ELAN & SYNA)(Modo Polling)
- Teclado (PS2)
- Teclas de brilho e volume
- Wi-Fi & Bluetooth BCM94360NG
- Leitor Micro SD 
- WebCam (Monterey > talvez precise ManyCam modo 240p / Ventura > iPhone Camera pode ser uma solução)
- ACPI Bateria
- NVRAM (Nativa para i7/bios mod)
- Recovery (macOS) boot do OpenCore


### Special Config:

- Device ID nativo (0200518A) Fully Graphic and Sleep/Wake.
- USB port mapping performed
- [Maldon](olarila.com) ACPI fix

## Credits

- [Apple](https://apple.com/osx) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and some kexts
- [Mald0n](https://www.olarila.com/topic/9918-olarila-hackintosh-hackbook-lenovo-ideapad-s145-10th-gen-catalina-big-sur-monterey-full-dsdt-patches-clover-and-opencore) for EFI bases, Olarila Vanilla Images, DSDT and Support!

## Tips

- Use ManyCam (ou um app de terceiro que permita alterar a resolução da WebCam para 240p) caso a camera perca suporte no Monterey. Ventura possui novos features com a camera do iPhone;
- [BIOS MOD Tutorial](https://www.youtube.com/watch?v=i5AYuSpQNYY&t=0s)
- [HiDPI Retina Display](https://www.youtube.com/watch?v=_fNvIfPxOEA&t=0s)

## Warning

Não me responsabilizo por danos. Sempre faça Backup;
