# Gigabyte Aero 14's Hackintosh Collection

Contains clover configs, kexts and useful softs. 

Contents:

- Soft :  contains some basic tools you need 
  - Clover Configurator: used to mount efi and make changes to clover config
  - IOJones : Check your IO, Alternative to IORegistryExplorer
  - Kext Utility :Install kext, rebuild cache
- Drivers: contains some kext you need to install to system
  - AppHDA Patcher : for audio
  - Kext : wifi drivers and Battery 
  - SmartTouchPad : trackpad and keyboad.
    - this is original archive. 
- Clover : contains clover settings 
  - a config.plist
  - ACPI  : contains acpi patches for :
    - SSDT-UIAC : usb patches
    - SSDT-PNLF : backlight 
    - SSDT-pr : Skylake HWP
  - Kext/Other : contains basic kexts for 
    - ApplePS2SmartTouchPad : drivers for trackpad and keyboard
      - NOTE : i've made some changes. see below
    - FakeSMC : smc driver
    - USBInjectAll : Usb 