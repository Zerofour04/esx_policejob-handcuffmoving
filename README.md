<h1 align="center"> 🚓esx_policejob</h1>

## 👑Creator: [ESX Framework](https://github.com/esx-framework)
## 🛠️Forked/Edited by: [Zerofour](https://github.com/Zerofour04)

---

## ⭐Features
- You can move if you're under arrest
- Bodycam feature
- MDT
- Status of the officer
- Backup system
- Police badge
- K9 Dog menu
- Camera system
- Police shield
- Speed camera system
- Traffic manager

## ℹ️Information
Hey, I'm releasing this police job because I rescripted this police job a few years ago, I mainly implemented better scripts/features in it.
**⚠️Please note the requirements you need for this script!**

## 🖼️Pictures:
<img src="https://user-images.githubusercontent.com/60815764/206313947-90388b07-0929-4c97-ae37-64b9368dd141.png" width=40%>
<img src="https://user-images.githubusercontent.com/60815764/206313945-7351d773-30b6-4feb-98a2-31d7ff4240b0.png" width=40%>
<img src="https://user-images.githubusercontent.com/60815764/206313943-299467cc-e99a-4c4e-beee-52169261dd7c.png" width=40%>

## 🧱Requirements
### You need this scripts for the custom police job:
- [MDT System](https://github.com/Zerofour04/mdt)
- [Bodycam feature](https://forum.cfx.re/t/iis-body-worn-video-bwv-bodycam-resource-custom-ui/1933960)
- [Traffic manager](https://github.com/xDope7137/TrafficManager)

### Default:
* Auto mode
  * [esx_billing](https://github.com/ESX-Org/esx_billing)
  * [esx_vehicleshop](https://github.com/ESX-Org/esx_vehicleshop)
* Player management (boss actions and armory with buyable weapons)
  * [esx_addoninventory](https://github.com/ESX-Org/esx_addoninventory)
  * [esx_datastore](https://github.com/ESX-Org/esx_datastore)
  * [esx_society](https://github.com/ESX-Org/esx_society)
* ESX Identity Support
  * [esx_identity](https://github.com/ESX-Org/esx_identity)
* ESX License Support
  * [esx_license](https://github.com/ESX-Org/esx_license)
* ESX Service Support
  * [esx_service](https://github.com/ESX-Org/esx_service)
* ESX Status Support
  * [esx_status](https://github.com/ESX-Org/esx_status)
  
 ## ⚙️Configuration
 * `Config.EnablePlayerManagement` = Enable if you want society managing.
 * `Config.EnableArmoryManagement` = Armory management
 * `Config.EnableESXIdentity` = Enable if you're using esx_identity.
 * `Config.EnableLicenses` = Enable if you're using esx_license.
 * `Config.EnableHandcuffTimer` = Enable handcuff timer? will unrestrain player after the time ends.
 * `Config.EnableJobBlip` = Enable blips for cops on duty, requires esx_society.
 * `Config.EnableCustomPeds` = Enable custom peds in cloak room? See Config.CustomPeds below to customize peds.
 * `Config.EnableESXService` = Enable esx service?
 * `Config.MaxInService` = How much people can be in service at once?

* `Config.PoliceStations` = Location & Blip
* `Config.AuthorizedWeapons` = Armory management
* `Config.AuthorizedVehicles` = Vehicle management
* `Config.Uniforms` = EUP 

### Police Backup Menu item:
https://github.com/Zerofour04/esx_policejob-improved/blob/4d6e5e51aa3c294ace1ea4b49e1689df9fb54422/esx_policejob/client/main.lua#L503

### Police Backup message:
https://github.com/Zerofour04/esx_policejob-improved/blob/4d6e5e51aa3c294ace1ea4b49e1689df9fb54422/esx_policejob/client/main.lua#L1983

### Police status menu item:
https://github.com/Zerofour04/esx_policejob-improved/blob/4d6e5e51aa3c294ace1ea4b49e1689df9fb54422/esx_policejob/client/main.lua#L458

### Police status message:
https://github.com/Zerofour04/esx_policejob-improved/blob/4d6e5e51aa3c294ace1ea4b49e1689df9fb54422/esx_policejob/client/main.lua#L1943
---

## 🔧Changelogs:
### [2.0.0] - Dec 4, 2022
 - Added Backup Sound when you request Backup
 - Added more objects in the traffic interaction
  - Added some Sheriff coordinates
 - Added own police menu
   - Bodycam feature
   - MDT system
   - Status of officer
   - Police Backup menu
   - K9 Dog Menu
   - Camera system
   - Shieldmenu
   - Speed measurement
   - Traffic Manager system
 - Updated `fx_version`
 - Fixed some translation error
 - Fixed some SQL File type errors

### [1.0.0] - Mar 27, 2021
  - Rewritten so that people can move while wearing handcuffs

## 📋Download & Installation
### Using [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx esx-org/esx_policejob
```

### Using Git
```
cd resources
git clone https://github.com/ESX-Org/esx_policejob [esx]/esx_policejob
```

### Manually
1. Download https://github.com/ESX-Org/esx_policejob/archive/master.zip
2. Put it in the `[esx]` directory
3. Import `esx_policejob.sql` in your database
4. Add this to your server.cfg:
```
start esx_policejob
```

## ⭐Credits / ❗Copyright
- Please do not upload this script anywhere else as a lot of time is invested in the script and out of respect for the developers

**Hey, some parts of the script were not created by me. I wrote and used this content a few years ago and I want to publish this content because I don't play FiveM anymore and want to help some people, also I keep improving the content. If you are one of the creators and don't want your code to be here, make a pull request/issue.**

**Hey, I've been programming passionately in my spare time for several years and I like to use ideas from other people, unfortunately, I don't always manage to credit every developer, but I try my best. If there is a piece of code in it that the developer doesn't want to have in it, I will of course remove it**

### 💌Thanks to all developers who are part of this script, because without them the script would not be as extensive
- [K9 Dog menu](https://forum.cfx.re/t/release-original-police-k9-updated/1061030)
- [MDT System](https://github.com/Zerofour04/mdt)
- [Bodycam feature](https://forum.cfx.re/t/iis-body-worn-video-bwv-bodycam-resource-custom-ui/1933960)
- [Traffic manager](https://github.com/xDope7137/TrafficManager)
- [Police Badge](https://github.com/Zerofour04/esx_PoliceBadge)
- [Police Shield](https://forum.cfx.re/t/release-police-shield/116095)

# ©️Legal
### License
esx_policejob - police script for ESX

Copyright (C) 2015-2020 Jérémie N'gadi

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
