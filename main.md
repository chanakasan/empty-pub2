# main

## winget
- https://github.com/microsoft/winget-cli/releases/tag/v1.4.10173
- https://github.com/microsoft/winget-cli/releases/download/v1.4.10173/Microsoft.DesktopAppInstaller_8wekyb3d8bbwe.msixbundle
- https://aka.ms/Microsoft.VCLibs.x64.14.00.Desktop.appx

```
Add-AppxPackage Microsoft.VCLibs.x64.14.00.Desktop.appx
Add-AppxPackage $latestWingetMsixBundle
```
