# Lain's X1 Carbon 1st Gen macOS Repository
A repository of information and kexts for running macOS Mojave on the X1 Carbon 1st Generation.

Any discoveries and forks to get full functionality are much appreciated! I can't provide support on any of this really, but you can do whatever you want with these files.

Lain's X1 Carbon Specs:
- Model: 3448A47
- BIOS: G6ETC5WW (2.85 )
- CPU: Intel Core i5 (3rd Gen) 3427U / 1.8 GHz (Compatible w/ Clover modifications) 
- GPU: Intel HD Graphics 4000 (Compatible)
- RAM: 8GB DDR3L SDRAM (Compatible)
- Bluetooth Card: Broadcom Corp. BCM20702 Bluetooth 4.0 [ThinkPad] (Compatible)
- Wireless Card: Intel Corporation Centrino Advanced-N 6205 [Taylor Peak] (rev 96) (Not Compatible)

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
- Bluetooth Support (haven't tried any Handoff/etc. stuff but it works well enough to connect to my phone's network.)
- SD Card Support
- Filevault
- APFS

## What Doesn't Work:
- Wireless (not sure if the X1C1 can be whitelisted for a custom wireless card).
- Brightness Keys (requires DSDT patching, which I'm still learning about.)
- Battery Information
- Microphone doesn't register for some reason.
- Using two USB devices that require a more than a modicrum of power. Whenever I hook up my Akai Midi and my Blackberry KeyOne, I get an error that whatever was added last is not getting enough power. This is most likely an issue that needs DSDT patching.
- You tell me.

## Untested:
- Facetime / iMessage / etc. (I don't have an iPhone to use iMessage with so YMMV.)
- Mini-Displayport output
- USB Sleep Charging
- Lots of other things, I'm sure. 
