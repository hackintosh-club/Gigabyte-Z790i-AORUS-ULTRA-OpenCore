# Gigabyte Z790i AORUS ULTRA Hackintosh OpenCore EFI

![image](ScreenShot/Gigabyte-Z790i-AORUS-ULTRA.jpg)

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 0.9.7](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x 
- macOS Sonoma  14.x 


### Hardware

- BIOS Version: F7  2023-12-14
- Motherboard: Gigabyte Z790i AORUS ULTRA
- CPU: Intel 14th i7-14700KF
- GPU: AMD Radeon RX 6800 XT 16GB GDDR6
- Memo: Gloway International 32GB(16GB*2) DDR5-6400 Mhz
- SSD:  Asgard AN4.0 2TB   MacOS Sonoma + Windows 11
- SSD:  ‎Seagate FireCuda 520 1TB   Data
- HDA: Realtek ALC4080
- LAN: Intel L225-V
- WiFI: Killer(R) Wi-Fi 6E Ax1690i 160MHz

### BIOS

```

Settings
  |-- IO Ports
      |-- Above 4G Decoding: Enabled
      |-- IOAPIC 24-119 Entries: Disabled
      |-- USB Configuration
          |-- XHCI Hand-off: Enabled 
          |-- Port 60/64 Emulation: Disabled
      |-- SATA Configuration
          |-- SATA Controllers): Enabled 
  |-- Miscellaneous 
      |-- VT-D: Enabled    
Boot 
  |-- CFG Lock: Disabled
  |-- Fast Boot: Disable Link
  |-- CSM Support: Disabled
  |-- Secure Boot
      |-- Secure Boot: Disabled
```

### Notes

 - Use  [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools/releases) build your SMBIOS
 - If you want to use a CPU without  Efficient-Core, you must uncheck the option in the config.plist file Kernel--ProvideCurrentCpuinfo
 - Use the Power button to wake up from sleep
 - Intel AX211 WiFi driver ([AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases) in this EFI is only applicable to MacOS 14 Sonoma. Please download and replace this driver yourself when installing other MacOS versions
 - Intel AX211 Not Supported  Airdrop

### ScreenShot

![image](ScreenShot/Sonoma.jpg)

### Contact Us 

- QQ Group: 23304408

![image](ScreenShot/QRCode.png)