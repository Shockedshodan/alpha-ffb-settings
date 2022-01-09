# alpha-ffb-settings
Repo for sharing good, or at least decent, settings for Simagic Alpha series base

## Installation
* Go into your root folder of Simagic Alpha Manager.
* Rename `ini` directory to a different name, e.g `ini_my_backup` or your name.
* Run from [Git-Bash console](https://git-scm.com/download/win) the command `git clone https://github.com/Shockedshodan/alpha-ffb-settings ./ini` to fetch all files from the repository.
* (optionally) Copy your INI files (which you still want to use) from ini-backup folder.

Possibly, you will need to reload your Alpha Manager.

## Files structure

```
/ROOT (AlphaManager/ini folder)
  /AC_MX5.ini     <-- AlphaBase settings for Mazda MX5 in AC
  /AC/default.txt <-- Recommended default settings for Assetto Corsa
  /AC/MX5.ini     <-- Custom settings for MX5 (optional)
```

* `AC/default.txt` -- these settings could be used as optimal for your AlphaBase.
* `AC/MX5.ini` -- optionally, particular sim settings can be mentioned for a car/a group of cars. But it's more preferable to keep differences in base settings, as it's easier to manage.

### Vendor's settings

| File  | Sim app |
| ------------- | ------------- |
| `AC.ini`  | Assetto Corsa  |
| `ACC.ini` | Assetto Corsa Competizione |
| `iRacing.ini` | iRacing |
| `DirtRally2.ini` | Dirt Rally 2.0 |
| `EUROTRUCKS.ini` | Eurotrucks |
| `data.ini` | (I don't know the purpose of this file) |

**Please do not change these files. But please update them if the settings were updated (in future releases)**

### Filename Convention
Filename format: `SimName_ShortCarNameOrType.ini`<br>
E.g.: `AC_MX5.ini`, or `AC_TCR.ini` for TCR group of cars, in case it works for a whole car group.<br>
The short name shall be very recognizable. Don't be shy to mention a bit more in the file name. But one car shall have only one file.

NOTE: Filename must be short as possible as it is hard to read long names in Alpha Manager dropdown.

## Adding a new setup

### Base settings (`*.ini` file)
* Fork the repository.
* Add/update base settings.
* Create a pull request with a new or updated settings INI file.
* Add extra information to describe what has been changed and why.
* Once it has approved from the community, the reference to this file shall be added to a related information page (TBD: add link to such page)

#### Car Simulator Settings
Any base settings must be related to the sim settings.<br>
Default sim settings shall be added along with base settings (e.g. `AC/default.txt`).<br>
Custom sim settings for a car can be added along with base settings (e.g. `AC/MX5.txt`).<br>

Force Feedback settings can be found here:
Assetto Corsa: `Content Manager > Settings > Assetto Corsa > Contols > Force Feedback`

## Assetto Corsa Mods for Force Feedback

### Sidekick 
An in-game dashboard. It is able to highlight FFB spikes when you have it too high/strong.
- `v1.11.1` https://www.racedepartment.com/downloads/sidekick.11007/
- `v1.14.1` (extended) https://www.nutrimatic.cc/assetto-corsa/sidekick-extended/

### FFBClip
A debug tool for FFB
- https://www.racedepartment.com/downloads/ffbclip-app.7910/
