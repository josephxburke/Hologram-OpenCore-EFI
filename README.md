# Hologram-OpenCore-EFI
EFI folder for Hologram (personal Hackintosh build) running OpenCore bootloader.

---

IMPORTANT: While this EFI folder is a working configuration for the hardware below, it is ill-advised to use others' EFI folders for anything beyond
personal research or troubleshooting. If you are building a Hackintosh and plan to use the OpenCore bootloader, start here: 
https://dortania.github.io/OpenCore-Desktop-Guide/

---

OpenCore Version: **0.5.9**
macOS Version: **10.15.5 (Catalina)**

Notes: config.plist has been stripped of all SMBIOS entries. You will want to generate, test, and input your own using corpnewt's GenSMBIOS tool:
https://github.com/corpnewt/GenSMBIOS

Current (shoppable) hardware list:
https://pcpartpicker.com/list/rPtQ4n

- Gigabyte Z390 Designare Motherboard (BIOS Ver. F8)
- Intel i9-9900K CPU (3.6GHz)
- 32GB Corsair Vengeance Performance DDR4-3600 RAM (2x16)
- be quiet! Dark Rock Pro 4 CPU Cooler
- Primary HD (macOS): Samsung 970 Evo 500GB M.2 NVME SSD
- Secondary HD (Windows 10 Pro): Samsung 860 Evo 250GB SSD
- Data Disks: Seagate Barracuda Compute 4TB & 8TB Internal HD
- Sapphire Pulse Radeon RX 580 8GB
- Corsair RMx 850 80+ Gold ATX Power Supply
- NZXT H510i ATX Mid-Tower Case

Wi-Fi / Bluetooth Module (native support in macOS for continuity/handoff/watch unlock features):
- Broadcom BC94360CD (802.11a/b/g/n/ac, Bluetooth 4.0)

To read about this build, visit my personal site:
https://josephx.com/writing/hackintosh-hologram
