# Winget-AutoUpdate-Configurator
This project uses the Winget tool to daily update apps (with system context) and notify users when updates are available and installed.

WinGet-AutoUpdate-Configurator is based on WinGet-AutoUpdate (WAU) and allows you to configure Winget-AutoUpdate within the Microsoft Intune console using ADMX backed policies.

The WinGet-AutoUpdate-Configurator takes the configuration from Microsoft Intune and applies it to WinGet-AutoUpdate so your users stay up-to-date with their software.

![image](https://user-images.githubusercontent.com/96626929/150645599-9460def4-0818-4fe9-819c-dd7081ff8447.png)

## Intune integration using ADMX backed profiles
Winget-AutoUpdate-Configurator integrates well into Microsoft Intune by using ADMX backed policies. You can configure nearly all aspects of Winget-AutoUpdate from your Microsoft Intune console and change settings when you need without redeploying Winget-AutoUpdate.

You can also configure your white- and blacklist from within the Microsoft Intune console and do not need to host them on an external data source.

![image](https://github.com/Weatherlights/Winget-AutoUpdate-Intune/blob/b4e70d7e476eef0e99c841bb807c0604ba2d7676/docs/img/teaser1.png)

## Features
* Updates (nearly) every 3rd Party App that using WinGet
* Fully ADMX backed configuration using Microsoft Intune
* White- or Blacklist apps you want to update
* Easy deployment using a single MSI file
