<h1 align="center"> 🚓esx_policejob</h1>

## 👑Creator: [ESX Framework](https://github.com/esx-framework)
## 🛠️Forked/Edited by: [Zerofour](https://github.com/Zerofour04)

---

## ⭐Features
- Camera system
- Shield system
- Speed measurement
- S 
- You can move if you're under arrest

## ⚙️Changelogs:
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

## 🖼️Pictures:
<img src="https://user-images.githubusercontent.com/60815764/206313947-90388b07-0929-4c97-ae37-64b9368dd141.png" width=40%>
<img src="https://user-images.githubusercontent.com/60815764/206313945-7351d773-30b6-4feb-98a2-31d7ff4240b0.png" width=40%>
<img src="https://user-images.githubusercontent.com/60815764/206313943-299467cc-e99a-4c4e-beee-52169261dd7c.png" width=40%>


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

## 🧱Requirements
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



## 📝Notes
-  * If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
   * If you want armory management you have to set `Config.EnableArmoryManagement` to `true` in `config.lua`
   * If you want license management you have to set `Config.EnableLicenses` to `true` in `config.lua`
   * If you want service management you have to set `Config.MaxInService` to a higher value than `-1` in `config.lua`

# ©️Legal
### License
esx_policejob - police script for ESX

Copyright (C) 2015-2020 Jérémie N'gadi

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
