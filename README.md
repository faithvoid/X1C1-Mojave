# Lain's X1 Carbon 1st Gen macOS Repository
A repository of information and kexts for running macOS Mojave on the X1 Carbon 1st Generation.

Any discoveries and forks to get full functionality are much appreciated! As of June 28th, 2021, I can no longer provide support on any of this due to my X1C1 needing repairs (although I may just sell it for parts as I've started using an X220 again) but you can do whatever you want with these files. If you would like to donate so I can repair my X1C1 and continue testing, my PayPal is [here!](https://www.paypal.com/donate/?cmd=_s-xclick&hosted_button_id=8GF4A3XS7ZHFY) 

*Please be respectful of the fact that I may not be able to provide too much support for this. I'll update it regularly as new discoveries and modifications are made, but I very frequently take breaks from GitHub due to health issues and cannot be relied on for tech support. Consider this repo a starting point more than a finished product until stated otherwise. Thank you and stay safe!*


Lain's X1 Carbon Specs:
- Model: 3448A47
- BIOS: G6ETC5WW (2.85 )
- CPU: Intel Core i5-3427U @ 1.8 GHz 
- GPU: Intel HD Graphics 4000 
- RAM: 8GB DDR3L SDRAM 
- Bluetooth Card: Broadcom Corp. BCM20702 Bluetooth 4.0 [ThinkPad]
- Wireless Card: Intel Corporation Centrino Advanced-N 6205 [Taylor Peak] (rev 96) 

## What Works:
Virtually everything.

## What hopefully works but might not:
- Wireless. I've added a two new kexts to the repository to try thanks to the OpenIntelWireless team, but I don't have a usable X1C1 to test this on. To my knowledge it SHOULD work as it shares a wireless card (albeit a different connector) with the X220 (Intel Centrino N-6205) that functions with the same kext. If the default kext included works and you want AirPort support, you can try to replace the "itlwm" kext in your EFI/Clover with the "AirportItlwm.kext" file in the "Other" folder of the repo. Please note that this may noticeably tank your internet speeds if it works, so I've set itlwm as the default to ensure stability/performance. **DO NOT USE BOTH DRIVERS AT ONCE. You'll probably crash your system.**

## What Doesn't Work:
- Microphone and microphone mute button don't register for some reason.
- Trackpoint works maybe 10% of the time.
- Audio usually doesn't work after sleep (requires an SSDT patch + Codec Commander or a program to restart AppleHDA.)
- You tell me.

## Untested:
- Facetime / iMessage / etc. (I don't have an iPhone to use iMessage with so YMMV. You'll most likely need an intricate knowledge of modifying your config.plist with valid serial numbers to get either of these to work, as I've never gotten this to work on the first attempt of any Hackintosh.)
- Mini-Displayport output
- USB Sleep Charging
- Bluetooth Hand-Off
- Lots of other things, I'm sure. 

## Potential Setbacks:
- X1C1 uses a proprietary Wi-Fi adapter, and has a BIOS that can only be flashed unofficially with a SOIC-8 clip. Adapters exist to convert traditional Wi-Fi cards to Lenovo's proprietary standard, but whether or not these are compatible with any possible BIOS mods is yet to be seen, and may be a discouraging factor.
