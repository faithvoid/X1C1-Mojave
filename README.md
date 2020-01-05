# Lain's X1 Carbon 1st Gen macOS Repository
A repository of information and kexts for running macOS Mojave on the X1 Carbon 1st Generation.

Any discoveries and forks to get full functionality are much appreciated! I can't provide support on any of this really, but you can do whatever you want with these files.

Lain's X1 Carbon Specs:
- Model: 3448A47
- BIOS: G6ETC5WW (2.85 )
- CPU: Intel Core i5-3427U @ 1.8 GHz 
- GPU: Intel HD Graphics 4000 
- RAM: 8GB DDR3L SDRAM 
- Bluetooth Card: Broadcom Corp. BCM20702 Bluetooth 4.0 [ThinkPad]
- Wireless Card: Intel Corporation Centrino Advanced-N 6205 [Taylor Peak] (rev 96) (Not Compatible)

## What Works:
Virtually everything.

## What Doesn't Work:
- Wireless (not sure if the X1C1 can be whitelisted for a custom wireless card).
- Microphone and microphone mute button don't register for some reason.
- Trackpoint works maybe 10% of the time.
- Audio usually doesn't work after sleep (requires an SSDT patch + Codec Commander or a program to restart AppleHDA.)
- You tell me.

## Untested:
- Facetime / iMessage / etc. (I don't have an iPhone to use iMessage with so YMMV.)
- Mini-Displayport output
- USB Sleep Charging
- Bluetooth Hand-Off
- Lots of other things, I'm sure. 

## Potential Setbacks:
- X1C1 uses a proprietary Wi-Fi adapter, and has a BIOS that can only be flashed unofficially with a SOIC-8 clip. Adapters exist to convert traditional Wi-Fi cards to Lenovo's proprietary standard, but whether or not these are compatible with any possible BIOS mods is yet to be seen, and may be a discouraging factor.
