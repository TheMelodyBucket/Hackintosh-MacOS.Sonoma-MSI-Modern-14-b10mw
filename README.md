Brief guide for Hackintoshing MSI Modern 14 b10mw (Intel® Core™ i3/i5/i7 10th Generation/ comet lake) Models.

## Screenshots

![Screenshot](https://private-user-images.githubusercontent.com/103637434/305134853-5fc0c894-7777-46be-96ce-f73a9622addb.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDgwMTI1NzksIm5iZiI6MTcwODAxMjI3OSwicGF0aCI6Ii8xMDM2Mzc0MzQvMzA1MTM0ODUzLTVmYzBjODk0LTc3NzctNDZiZS05NmNlLWY3M2E5NjIyYWRkYi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMjE1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDIxNVQxNTUxMTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00OTU2MWIwNzAxYzhhM2FhYjc0ODk4MzdmODk1NjhhY2ExOTM0N2Q3NzM3OTFjZTEzOTk5ZmJiOTNmYjcwYTQxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.OdDVJWDCYle9qenlBC5M0aZt0rmB6YBKNrTjfq6lekY)



## WARNING
Testing out something experimental may cause your device lagging/ battery draining problems/ excessive heating/ dead devices or other hardware issues. Test at your own risk.

Use Opencore Configurator (OCC) to add ROM, MLB and Serial to config.plist.
See [mackie100Projects](https://mackie100projects.altervista.org/download-opencore-configurator) to download OCC and [Dortania guides](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html) for help.

- *A Backlit issue have been addressed and using an external monitor is advised.*
## Support/ Feedback

For support and feedback, [send an email](sithumkottearachchi@outlook.com)


## Features (Working)

- Sound
- keyboard with keyboard brightness adjustment.
- Webcam and Mic (no spatial audio support or animated reactions on calls)
- Display (Found issues with backlit, strict attention advised until a fix is being released)
- Brightness/ Sound shortcut keys in function key row.
- Wifi (99% Working, try a restart if doesn't work)
- Bluetooth (Might misbehave)
- All USB 2 ports (right hand side)
- 3.5mm headphone/mic combo jack.
- USB 3.2 Thunderbolt port.
- Card reader.
- HDMI out.
- Sleep/ Wake up (might restart automatically after putting into sleep)
- Charging and all other basic functionalities.

## Features (Not working)/ Issues
Working on fixes for all issues. But don't keep high hopes.
- Backlight may be delayed to hit on. Use an external monitor until a fix is released.
- Airdrop.
- iMessages and Facetime (Working on a fix, do not try to log in as your apple ID could be flagged as a bot)
- Fans (are working but working on higher demand applications may cause overheating as fans cannot exceed their speed more than around 1500rpm. Working on a fix)
- Lossless playback on Apple Music.
- Some hardware accelerated decoding (it's a hardware limitation so no fixes)
## Documentation

[Check out the Dortania's guide for using Opencore config](https://dortania.github.io/OpenCore-Install-Guide/) 

For additional support, check out [tonymacx86](https://www.tonymacx86.com/)
## Installation
According to your need, use the whole EFI file with all it's content after extracting compressed zip files. ( for upgrading from a lower MacOS version to MacOS Sonoma or installing a fresh MacOS Sonoma copy ). Do some research before testing.

## Credits
[Apple](https://www.apple.com/) for MacOS.

[Dortania](https://github.com/dortania) for guides and help.

[OpenIntelWireless](https://openintelwireless.github.io/) for WiFi and Bluetooth kexts.

[Acidenthera](https://github.com/acidanthera) for Lilu, VirtualSMC, OpencorePKG, AppleALC, and WhateverGreen kexts. 
