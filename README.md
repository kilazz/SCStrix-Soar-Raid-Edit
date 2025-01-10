## STRIX SOAR/RAID PRO/DLX Edit

## Compatibility
- **Supported OS:** Windows 10/11 x64, version 19041 and above

## Removal Steps
1. **Uninstall Packages:** Use [Rapr][DriverStoreExplorer] to remove all related packages.
2. **Restart PC:** Reboot your computer.

## Installation Steps

### Default/OEM Installation
1. **Install ASMedia USB Drivers:** `ASMedia_USB3x_1.16.61.1`
2. **Install STRIX SOAR Setup:** `Strix_Soar_Setup_1.1.23`
3. **Remove Specific Packages:** `nhAsusSC150.inf`/`nhAsusSC200.inf`
4. **Restart PC:** Reboot your computer. ~
5. **Install STRIX SOAR ASUS SC Strix Edit:**
   - `Install_Default.cmd` for default installation
   - `Install_DolbyAtmos.cmd` for Dolby Atmos support
   - `Install_DTSXUltra.cmd` for DTS X Ultra support
   - `Install_Nahimic.cmd` for Nahimic support
6. **Restart PC:** Reboot your computer.

## Troubleshooting
- **Microfreeze Issue:** A brief microfreeze may occur after running `nhAsusStrixSonicStudioSC.exe`. ~
- **DTS Service:** Restart the **DtsApo4Service** multiple times if needed after rebooting. ~

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
