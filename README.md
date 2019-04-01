# SolidCam-PocketNC-Post
## A SolidCam postprocessor for PocketNC supporting 4x operations - beta (5x operations - alpha)

**Use this post at your own risk! Always check the produced code before running it on a real machine!**

Cloned and modified from https://github.com/teodoryantcheff/SolidCam-Mach3-Post


-- From original README.md
Inspired by **bogan**.

Special thanks to **Bruno Silva** - test part modelling and code testing.

CNCZone [discussion link](http://www.cnczone.com/forums/solidcam/255556-cnc.html).
-----

Setup (4x): standard 3 axis mill. B axis rotary, along Y, A in zero position.
Setup (5x): in testing.

 - 3 axis - working
 - 4 axis - working / for both repositioning moves and 4x toolpaths
 - 5 axis - working (UNTESTED)
 - Drill cycles - G81 (drill), G82 (drill+dwell), G83 (peck drilling), Cannes: G85, G86, G89 (UNTESTED)
 
## TODO :
 - 4x indexial use may need some more work to avoid unnecessary retracts to clearance. As of now it's safe but can be made faster w/o retracts.
 - Tool offsets and compensation

## Installation and usage notes :
 - Put the .gpp and .vmid files in `C:\Users\Public\Documents\SolidCAM\SolidCAMXXXX\Gpptool`. You need to restart SolidWorks for it to pick up the new files.
 - Usage in SolidCam - Select `Pocket_4X_Y` for CNC-Machine

*Testers needed - any feedback appreciated.*
