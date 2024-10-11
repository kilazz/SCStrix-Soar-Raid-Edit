## Strix Soar/Raid Edit Default/OEM
#### Compatibility >
- Windows 10 x64 19041+
#### Removal >
- Remove all packages via [Rapr][DriverStoreExplorer]
- Restart PC
#### Installation Default/OEM >
- Install ASMedia_USB3x_1.16.61.1
- Install Strix_Soar_Setup_1.1.23.exe
- Remove package `nhAsusSC150.inf/nhAsusSC200.inf`, check via [Rapr][DriverStoreExplorer]
- Restart PC ~
- Unzip the .7z(Zstandard) archive
- Run _CertTest/`CertTest.bat` ~
- Install `Only one` >
- Default > 
`Install_Default.cmd`
- OEM >
`Install_Dolby.cmd`
`Install_DTS.cmd`
`Install_Nahimic.cmd`
`Install_SonicStudio3.cmd`
- Restart PC
#### Problems >
- After running nhAsusStrixSonicStudioSC.exe a microfreeze for a couple of seconds is possible ~

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
