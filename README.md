# STRIX SOAR/RAIDR PRO/DLX Edit
## Compatibility
- **OS:** Windows 10/11 (64-bit), version 19041 or later.
## Removal
1. **Uninstall:** Use [RAPR][DriverStoreExplorer] to remove all related packages.
2. **Restart:** Reboot PC.
## Installation
### Default/OEM Installation
1. **Install ASMedia USB Drivers:** Run `ASMedia_USB3x_1.16.61.1` to install the ASMedia USB 3.x drivers.
2. **Install STRIX SOAR Setup:** Run `Strix_Soar_Setup_1.1.23` to install the base STRIX SOAR software.
3. **Remove Specific Packages:**
   - Use DriverStore Explorer to delete the following packages:
     - `nhAsusSC150.inf`
     - `nhAsusSC200.inf`
4. **Restart:** Reboot PC.
5. **Install STRIX SOAR ASUS SCStrix Edit:**
   - Choose one of the following installation scripts based on your preference:
     - Run `Install_Default.cmd` for the default installation.
     - Run `Install_DolbyAtmos.cmd` for Dolby Atmos support.
     - Run `Install_DTSXUltra.cmd` for DTS X Ultra support.
     - Run `Install_Nahimic.cmd` for Nahimic support.
6. **Restart:** Reboot your PC to finalize the installation.

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
