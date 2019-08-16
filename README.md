# PrusaSlicer - settings 

### Applicable since Slic3r PE 1.40.0

PrusaSlicer settings are present in the `live` directory. The structure is as follows:

`live / {vendor name} / {bundle version}.ini`

Each bundle contains complete configuration of relevant printers, filaments and prints options.

Along with them is an index file, which Slic3r reads and uses to find out which version is the newest compatible:

`live / {vendor name} / index.ini`

Slic3r downloads these setting bundles automatically (unless updating is disabled), and so there should be no need to install them by hand.

## Settings for previous / legacy Slic3r versions

This project contains the Slic3r profiles for the 3D printers produced by Prusa Research http://www.prusa3d.com/

* [Slic3r settings MK2 - Settings for the Original Prusa i3 MK2 & MK2S & MK2MM & MK3](https://github.com/prusa3d/Slic3r-settings/tree/master/old/Slic3r%20settings%20MK2S%20MK2MM%20and%20MK3)
* [Slic3r settings 175 - Settings for the Prusa i3 with a 1.75mm filament extruder](https://github.com/prusa3d/Slic3r-settings/tree/master/old/Slic3r%20settings%20175)
* [Slic3r settings 3mm - Settings for the Prusa i3 with a 3mm filament extruder](https://github.com/prusa3d/Slic3r-settings/tree/master/old/Slic3r%20settings%203mm)

To apply these settings, you have to copy the particular github folder
([Slic3r settings MK2, MK2S, MK2MM and MK3](https://github.com/prusa3d/Slic3r-settings/tree/master/Slic3r%20settings%20MK2S%20MK2MM%20and%20MK3) /
[Slic3r settings 175](https://github.com/prusa3d/Slic3r-settings/tree/master/old/Slic3r%20settings%20175) /
[Slic3r settings 3mm](https://github.com/prusa3d/Slic3r-settings/tree/master/old/Slic3r%20settings%203mm))
into a local folder, where Slic3r will find it. The destination depends on your operating system and Slic3r version:

__Slic3r PE 1.38.4 and later__

 * Windows: "C:\Users\your_user_name\AppData\Roaming\Slic3rPE" or "C:\Documents and Settings\your_user_name\Application Data\Slic3rPE"
 * Mac: ~/Library/Application\ Support/Slic3rPE/
 * Unix / Linux: "~/.Slic3rPE/"

__All other versions__

* Windows: "C:\Users\your_user_name\AppData\Roaming\Slic3r\" or "C:\Documents and Settings\your_user_name\Application Data\Slic3r\"
* Mac: "~/Library/Application Support/Slic3r/"
* Unix / Linux: "~/.Slic3r/"

In case you installed the Prusa3D Windows drivers package, the Start menu is filled in with Slic3r shortcuts. These shortcuts are stored in "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Prusa3D" and they point Slic3r to the particular settings folder using the --DataDir switch.

* "C:\Users\Public\Documents\Prusa3D\Slic3r settings MK2" for the MK2 & MK2S &MK2MM & MK3
* "C:\Users\Public\Documents\Prusa3D\Slic3r settings 175" for the legacy i3 with a 1.75mm extruder
* "C:\Users\Public\Documents\Prusa3D\Slic3r settings 3mm" for the legacy i3 with a 3mm filament extruder

Therefore if you installed the Windows drivers package from Prusa3D, you may as well extract the whole ([Slic3r settings](https://github.com/prusa3d/Slic3r-settings/tree/master/) to "C:\Users\Public\Documents\Prusa3D\".
