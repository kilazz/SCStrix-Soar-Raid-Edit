# STRIX SOAR/RAID PRO/DLX Edit
## Compatibility
- Windows 10/11 x64 (Build 19041 or later) support.
## Features
- Default, DolbyAtmos, DTSXUltra, Nahimic support.
- Enhancements Tab support.
## Default/OEM Installation
1. Install `ASMedia_USB3x_1.16.61.1`.
2. Install `Strix_Soar_Setup_1.1.23`.
3. Uninstall existing `nhAsusSC150.inf`/`nhAsusSC200.inf` drivers using [RAPR][DriverStoreExplorer].
4. Run `AsusSCStrixInstaller.ps1`.
5. Remove Drivers.
6. Install the required configuration.
7. Restart PC.
## Troubleshooting
   - After launching `nhAsusStrixSonicStudioSC.exe`, a brief micro-freeze may occur. This is a known issue that usually resolves itself.
   - After updating to a new Windows build, you may need to reinstall a driver. Not sure what the issue is.

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
