# Asus F556U (X556UQK) - Big Sur Hackintosh Open Core 0.66
![](Screenshot/BigSur.png)

Release Version
- Modern Opencore Picker (Disabled), Require to enable for OS installation
- Bootchime

### Note
Please use SSDTTime to patch your own SSDT, do not use mine as not all the configuration work the same on your device.

Please generate your own SMBIOS SN, UUID using MacBookPro14,2 and change your ROM based on your Ethernet Mac Address.

### Technical Specifications
---

| Name              | Specifications                                                                                                                           |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Processor         | Intel Core i7 - 7600u                                                                                                                    |
| Memory            | 1x 8 GB DDR4 2133 Mhz                                                                                                                    |
| Storage           | SSD 840 EVO 250GB                                                                                                                        |
| Video             | Integrated Intel HD 520 + NVIDIA 940MX                                                                                                   |
| Wi-Fi + Bluetooth | ~~Qualcomm Atheros 9565~~ Replaced by Intel AX200                                                                                         |
| Ethernet          | Realtek RTL8111                                                                                                                          |
| Audio             | Realtek ALC255                                                                                                                           |
| Touchpad          | ELAN 1000 I2C Interface                                                                                                                  |
| Screen Size       | 15,6 Inch                                                                                                                                |
| Screen Resolution | 1920 x 1080                                                                                                                              |
| Others            | 1x Card Reader, 1x WebCam, 1x VGA Port, 1x HDMI, 1x Combo Audio Jack, 1x USB 2.0, 1x USB 3.0 Type A, 1x USB 3.0 Type C, 1x Optical Drive |

# What works
✅ Intel HD 620 
✅ VGA/HDMI (Audio + Video)
✅ All USB Type A ports
✅ USB type C port
✅ Keyboard
✅ Touchpad
✅ Internal screen backlight change
✅ Wi-Fi
✅ UVC HD Webcam
✅ Speaker
✅ Laptop lid
✅ Native power managment
✅ Battery status
✅ ️Sleep
✅ ️Bluetooth 
✅  IServices  (IMessage, FaceTime, ICloud)  (Make sure you set your own SMbios and generate your own Serial Number using GenSMBIOS)
⚠️ FN Keys (Volume Control, Disable TouchPad, Sleep works except for Brightness Control)
⚠️ Onboard Ethernet (Not Tested)
⚠️ SD Card (Not Tested)
❌ Realtek SD card reader
❌ NVIDIA GeForce 940MX (Optimus - impossible to get working at the moment)