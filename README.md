# STRIX SOAR/RAID PRO/DLX Edit

## Compatibility
- Windows 10/11 x64 (Build 19044 or later) support.

## Features
- Default, DolbyAtmos, DTSXUltra, Nahimic support.
- Enhancements Tab support.

### Prerequisites
1. Uninstall existing `nhAsusSC150.inf`/`nhAsusSC200.inf` drivers using [RAPR][DriverStoreExplorer].
2. Restart PC.

## Default/OEM Installation
1. Install `ASMedia_USB3x_1.16.61.1`. (optional: High DPC Latency. Use Microsoft driver) ~
2. Install `Strix_Soar_Setup_1.1.23`.
3. Run `AsusSCStrixInstaller.cmd`.
4. Remove Drivers.
5. Install the required configuration.
6. Restart PC.

## Troubleshooting
- **DTS Issues**: If DTS does not work, restart the DTS service a few times.
- **Windows Update**: Use **Toggle WU Driver Updates** and **Reset WU Cache & Ghost Devices** in the installer menu.
- **Voice Call Volume Drop**: Win+R -> `mmsys.cpl` -> Communications tab -> Select "Do nothing".

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
