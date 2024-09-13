## Strix Soar (SC150) Edit Default/OEM
#### Compatibility >
- Windows 10/11 x64 18363/26100+
#### Removal >
- Remove all packages via [Rapr][DriverStoreExplorer]
- Restart PC
#### Installation Default >
- Install Strix_Soar_Setup_1.1.23.exe
- Install ASMedia_USB3x_1.16.61.1
- Remove package `nhAsusSC150.inf`, check via [Rapr][DriverStoreExplorer]
- Unzip the .7z(Zstandard) archive
- Run _CertTest/`CertTest.bat`
- Install using `Install_Default.cmd`
- Restart PC
#### Installation OEM >
- Install Strix_Soar_Setup_1.1.23.exe
- Install ASMedia_USB3x_1.16.61.1
- Remove package `nhAsusSC150.inf`, check via [Rapr][DriverStoreExplorer]
- Unzip the .7z(Zstandard) archive
- Run _CertTest/`CertTest.bat`
- Install `only one` using `Install_Dolby.cmd`/`Install_DTS.cmd`/`Install_Nahimic.cmd`
- Restart PC
#### Problems >
- After running nhAsusStrixSonicStudioSC.exe a microfreeze for a couple of seconds is possible ~
- DTS applications not working properly (Legacy Service) ~

[DriverStoreExplorer]: https://github.com/lostindark/DriverStoreExplorer
