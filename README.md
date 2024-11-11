# HP Elitebook 845 G7 Ryzen Pro 4750u Hackintosh
 
Installed macOS Sonoma 14.7 working on this AMD laptop

Specs:
14" Screen
HDMI Port
2-USB-C ports
2-USB-A ports
Ryzen Pro 4750u CPU with Vega 8 iGPU
16GB RAM
1TB NVME - WDC Blue
Realtek ALC285
Intel AC-7260 WIFI and Bluetooh Combo
Synaptic Trackpad

What's working?

- OpenCore 1.0.2
- Dual Boot Windows 10 Pro and Sonoma 14.7.
- SMBIOs MacBook Pro 16,3. Must use a serial number that works for Facetime and iMessage.
- Vega 8 full acceleration with only 512MB VRAM due to BIOS - Smokeless UMAF doesn't work to increase the VRAM.
- Camera
- USB-C and USB-A using Toolbox
- WIFI and Bluetooth work - No Airdrop
- Trackpad Works.
- Backlight works with F3/F4 keys.
- Sound works with only VoodooHDA.kext and NOT AppleALC.kext - Microphone, Headphone, Speakers.
- Keyboard backlight works.
- HDMI works perfectly with Sound.

What's NOT working?

- Sleep/Wake
- AppleALC.kext

Performance - Handbrake over 100fps.
Battery - 3-4hr surfing internet - If turn off wifi and bluetooth, will only loses 20% in 2hr with the lid closed.


'

