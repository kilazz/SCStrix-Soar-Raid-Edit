# STRIX SOAR/RAIDR PRO/DLX Edit
## Compatibility
- Windows 10/11 x64 (Build 19041 or later) support.
## Features
- Default, Dolby Atmos, DTS X Ultra, Nahimic support.
- Enhancements Tab support.
## Default/OEM Installation
1. Install ASMedia USB Drivers: Run `ASMedia_USB3x_1.16.61.1` to install the ASMedia USB 3.x drivers.
2. Install STRIX SOAR Setup: Run `Strix_Soar_Setup_1.1.23` to install the base STRIX SOAR software.
3. Uninstall existing `nhAsusSC150.inf`/`nhAsusSC200.inf` drivers using [RAPR][DriverStoreExplorer].
4. Run `RealtekUADInstaller.ps1`.
5. Install the required configuration.
6. Restart PC.

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
