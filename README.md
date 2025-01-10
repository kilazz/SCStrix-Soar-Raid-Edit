## STRIX SOAR/RAID PRO/DLX Edit

## Compatibility
- **OS:** Windows 10/11 x64, version 19041 and above

## Removal Steps
1. **Uninstall:** Use [Rapr][DriverStoreExplorer] to remove all related packages.
2. **Restart:** Reboot your PC.

## Installation Steps

### Default/OEM Installation
1. **Install ASMedia USB Drivers:** `ASMedia_USB3x_1.16.61.1`
2. **Install STRIX SOAR Setup:** `Strix_Soar_Setup_1.1.23`
3. **Remove Specific Packages:** `nhAsusSC150.inf`/`nhAsusSC200.inf`
4. **Restart:** Reboot your PC. ~
5. **Install STRIX SOAR ASUS SCStrix Edit:**
   - `Install_Default.cmd` for Default installation
   - `Install_DolbyAtmos.cmd` for Dolby Atmos support
   - `Install_DTSXUltra.cmd` for DTS X Ultra support
   - `Install_Nahimic.cmd` for Nahimic support
6. **Restart:** Reboot your PC.

## Troubleshooting
- **Microfreeze Issue:** A brief microfreeze may occur after running `nhAsusStrixSonicStudioSC.exe`. ~
- **DTS Service:** Restart **DtsApo4Service** multiple times if needed. ~

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
