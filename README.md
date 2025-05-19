# Chrono Trigger Speedrun practice ROM Hack

An IPS patch for SNES Chrono Trigger to create a practice version of the ROM for speedrun practice


To use this patch you will need an unaltered Chrono Trigger SNES ROM (with the Header) and a patching utility such as [Lunar IPS](https://fusoya.eludevisibility.org/lips/). In Lunar IPS select `Apply IPS Patch`, then select the downloaded patch and the file to patch.

The ROM should have a SHA1 hash of `b0b89cedcc5ae40f8003f196ab90010249234b44`

On Windows you can verify the hash by running certutil:
`certutil -hashfile "Chrono Trigger (U) [!].smc" SHA1`

> Note: Lunar IPS will overwrite the original ROM, so make a copy if you want to keep the original ROM as well.