# Lain's X1 Carbon 1st Gen macOS Repository
A repository of information and kexts for running macOS Mojave on the X1 Carbon 1st Generation.

Any discoveries and forks to get full functionality are much appreciated!

Lain's X1 Carbon Specs:
- Model: 3448A47
- BIOS: G6ETC5WW (2.85 )
- CPU: Intel Core i5 (3rd Gen) 3427U / 1.8 GHz 
- GPU: Intel HD Graphics 4000 
- RAM: 8GB DDR3L SDRAM
- Bluetooth Card: Broadcom Corp. BCM20702 Bluetooth 4.0 [ThinkPad]
- Wireless Card: Intel Corporation Centrino Advanced-N 6205 [Taylor Peak] (rev 96)

## What Works:
- Booting
- GPU Acceleration
- Sound (including controls, microphone mute doesn't work)
- Webcam
- MIDI devices (used an Akai MPK II in GarageBand just fine)
- Brightness (not via controls but via the Display section manually).
- Touchpad (registers as only a mouse so no real gesture support).
- Trackpoint, partially. (works randomly, but don't count on it.)
- USB support, mostly (plugging in two will cause one to not receive enough power according to the OS, needs to be rectified via DSDT.)
- SD Card Support
- Filevault

## What Doesn't Work:
- Wireless (not sure if the X1C1 can be whitelisted for a custom wireless card).
- Brightness Keys (requires DSDT patching, which I'm still learning about.)
- 
## Untested:
- Mini-Displayport output
- Microphone
- USB Sleep Charging
- Lots of other things, I'm sure. 
