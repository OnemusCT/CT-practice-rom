# Chrono Trigger Speedrun practice ROM Hack

An IPS patch for SNES Chrono Trigger to create a practice version of the ROM for speedrun practice


To use this patch you will need an unaltered Chrono Trigger SNES ROM (with the Header) and a patching utility such as [Lunar IPS](https://fusoya.eludevisibility.org/lips/). In Lunar IPS select `Apply IPS Patch`, then select the downloaded patch and the file to patch.

To use the main IPS file `Chrono Trigger Practice ROM.ips` your base ROM should have a SHA1 hash of `b0b89cedcc5ae40f8003f196ab90010249234b44`

On Windows you can verify the hash by running certutil:
`certutil -hashfile "Chrono Trigger (U) [!].smc" SHA1`

The `Alternate Patches` directory contains a patch for a different base ROM with SHA1 hash of `de5822f4f2f7a55acb8926d4c0eaa63d5d989312`. If additional base ROMs are discovered they can be added as well, but these seem to be the two most common.

> Note: Lunar IPS will overwrite the original ROM, so make a copy if you want to keep the original ROM as well.