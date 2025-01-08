## Strix Soar/Raid Edit Default/OEM
#### Compatibility >
- Windows 10/11 x64 19041+
#### Removal >
- Remove all packages, check via [Rapr][DriverStoreExplorer]
- Restart PC
#### Installation Default/OEM >
- Install ASMedia_USB3x_1.16.61.1
- Install Strix_Soar_Setup_1.1.23
- Remove package `nhAsusSC150.inf/nhAsusSC200.inf`, check via [Rapr][DriverStoreExplorer]
- Restart PC ~
- Install Strix_Soar_AsusSCStrix_Edit >
  - `Install_Default.cmd`
  - `Install_DolbyAtmos.cmd`
  - `Install_DTSXUltra.cmd`
  - `Install_Nahimic.cmd`
- Restart PC
#### Problems >
- After running nhAsusStrixSonicStudioSC.exe a microfreeze for a couple of seconds is possible ~
- You may have to restart DTS "DtsApo4Service" a few times to get it working ~

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
