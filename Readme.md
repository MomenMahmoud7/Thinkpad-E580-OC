# Lenovo Thinkpad E580 OpenCore Hackintosh Big Sur
CPU Intel I5-8250U KabyLake (R).  
GPU Intel UHD 620.

# Not Supported Hardware:

- Discrete graphics card (ATI Radeon RX 550).
- Line/Mic Input (3,5 mm).
- Card reader.
- Fingerprint sensor.
- Trackpad 4-finger gestures. Cannot rotate, pinch, etc.

# Known Issues

- Sleep by lid close works only one time after starting the system  
( Can't sleep by Lid close after first sleep by Lid close ).  
- After wake from sleep slow charger detection (plugged / unplugged).  
- Brightness increase/decrease shortcuts doesn't exist in shortcuts settings after adding battery patch.  
Workaround: Change Brightness increase/decrease shortcuts before adding ssdt-BAT or you can change brightness level from control center.

# Before Use

Generate SMBIOS for your laptop.  
GenSMBIOS: https://github.com/corpnewt/GenSMBIOS  
Guide: https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo 