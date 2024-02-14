Brief guide for Hackintoshing MSI Modern 14 b10mw (Intel® Core™ i3 10th Generation/ comet lake) Model. May work with i5/ i7 models but try at your own risk.

## Screenshots

![Screenshot](https://private-user-images.githubusercontent.com/103637434/304711056-05324ca9-d345-47c0-9d4f-3ad4f0646abc.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDc5MDg3NDYsIm5iZiI6MTcwNzkwODQ0NiwicGF0aCI6Ii8xMDM2Mzc0MzQvMzA0NzExMDU2LTA1MzI0Y2E5LWQzNDUtNDdjMC05ZDRmLTNhZDRmMDY0NmFiYy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMjE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDIxNFQxMTAwNDZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xZWE1YTEyNWUyYjAyZTRjYWE2N2E1MGViOTBiOWM2NGQ1NzE4YTVjODQ1NTc0OTVkYmQ0MGE2ZDdmMGUzZWE3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.gI9CrkqJb_umq7_zzOIArEqrjQdjiyivkHvUxyxDYGY)



## WARNING
Testing out something experimental may cause your device lagging/ battery draining problems/ excessive heating/ dead devices or other hardware issues. Test at your own risk.

Use Opencore Configurator (OCC) to add ROM, MLB and Serial to config.plist.
See [mackie100Projects](https://mackie100projects.altervista.org/download-opencore-configurator) to download OCC and [Dortania guides](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html) for help.

- *A Backlit issue have been addressed and using an external monitor is advised.*
## Support/ Feedback

For support and feedback, [send an email](sithumkottearachchi@outlook.com)


## Features (Working)

- Sound
- keyboard
- Webcam and Mic (no spatial audio support or animated reactions on calls)
- Display (Found issues with backlit, strict attention advised until a fix is being released)
- Brightness/ Sound shortcut keys in function key row.
- Wifi (99% Working, try a restart if doesn't work)
- Bluetooth (Might misbehave)
- Backlit keyboard with keyboard brightness adjustment.
- All USB 2 ports (right hand side)
- 3.5mm headphone/mic como jack.
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
