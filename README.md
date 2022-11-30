# A list of things useful to owners of the GPD Win Max 2

## A check list of things to check on a new device, credits to SuperSexySoapTurtle#6606 on discord.
1. Test gpu under load for black screen. (Use graphically heavy games, 3dmark, photoshop, etc.)
2. Check bios version to make sure its up to date (Only update if necessary, see #1)
3. Test all keyboard keys (A lot of people are having issues with missed inputs) If you're having issues, try putting tape under the keycap
4. Test analog deadzones and update firmware if needed
https://www.mediafire.com/file/2lqucxtobzk0wfc/GPD_Gamepad_Firmware_Tool%25288%2529.exe/file
5. Test for static shock (Some dude was getting shocked by his unit occasionally lmao)
6. Look for dead pixels
7. Test if micro sd & sd card can be read. A lot of users were having issues with it disconnecting and reconnecting. This problem doesn't immediately show up, so if you use  SD and Micro SD a lot, I would monitor this.
8. Touch screen deadzones. Make sure all corners of the screen can be touched correctly. (I'd recommend touching and dragging each corner on the desktop to test this)
9. Make sure touch pad isn't going insane. (If it is, install firmware update from gpd) https://drive.google.com/file/d/1QlJEQPft1qemrM8F5jseteMwCc7-kVY_/view
10. Make sure screen is glued correctly (Some dude could see into his unit through a gap in the upper half of the screen lmao)
11. Do a full scan for malware with Microsoft defender. It should catch whatever worm or virus if any. Or just reinstall OS if you aren't lazy like me. 
12. Test analog stick circularity. (https://gamepad-tester.com/)
13. Make sure keycaps don't have cracks in them.
14. Make sure Dpad is working correctly.
15. Make sure remote play is working correctly. (A user was having issues with the screen randomly going black and having to force the machine to shut down.)

## Tools:
AMD Software: Adrenalin Edition(https://www.amd.com/en/support)
Driver pack from GPD(https://drive.google.com/file/d/161AkrveUcKXvo2ZEnsnmK-NPVLaCbc7r/view?usp=sharing)
Windows 11 21H2 with inclued drivers from GPD(https://drive.google.com/file/d/1PXQXYhxqyNU3t-T-MWH4cnsPz32KuHID/view?usp=sharing)
WIN Max 2 grip customization tool(https://www.gpd.hk/filedownload/88995)
MotionAssistant(https://discord.com/channels/243411108940087297/826965330965430272/1037625013441933382)
GamePad Test Calibration Tool V1.02(https://www.gpd.hk/filedownload/89292)
Power Control Panel(https://github.com/project-sbc/Power-Control-Panel-v2)
GPD Gamepad Firmware Tool V3.09/V1.21 (https://www.mediafire.com/file/2lqucxtobzk0wfc/GPD_Gamepad_Firmware_Tool%25288%2529.exe/file)
Script for adding extra resolutions and refresh rates(https://discord.com/channels/243411108940087297/802730777443958824/1040061390158827650)
Performance overlay for WM2(https://discord.com/channels/243411108940087297/826965330965430272/1045420389368594472)
WM2 Bios files(https://discord.com/channels/243411108940087297/826965330965430272/1040093726380396554)
Ciphray's TDP bat menu(https://discord.com/channels/243411108940087297/826965330965430272/830845629978247209)

## Workarounds
###### SD card slots disconneting constantly workaround, credits to ciphray#8122 on discord.
For anyone having SD/MicroSD disconnect/reconnect issues, the wonderful Ciphray has found a temporary solution that will work until GPD comes up with a fix. It lowers your SD readers speeds to USB 2.0 speeds, but they will stop having problems.

1. Shut your WM2 down
2. Boot and press delete until you enter the bios screen
3. Hold ALT and press F5 to see advanced BIOS
4. Go to Chipset > South Bridge > SB USB Configuration > USB1 Ports
5. Change XHC1 Port 1 to “Disabled”
6. Save and exit BIOS