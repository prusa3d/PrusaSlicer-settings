# Slic3r-settings

This project contains the Slic3r profiles for the 3D printers produced by Prusa Research http://www.prusa3d.com/

* [Slic3r settings MK2 - Settings for the Original Prusa i3 MK2 & MK2S](https://github.com/prusa3d/Slic3r-settings/tree/master/Slic3r%20settings%20MK2)
* [Slic3r settings 175 - Settings for the Prusa i3 with a 1.75mm filament extruder](https://github.com/prusa3d/Slic3r-settings/tree/master/Slic3r%20settings%20175)
* [Slic3r settings 3mm - Settings for the Prusa i3 with a 3mm filament extruder](https://github.com/prusa3d/Slic3r-settings/tree/master/Slic3r%20settings%203mm)

To apply these settings, you have to copy the particular github folder
([Slic3r settings MK2](https://github.com/prusa3d/Slic3r-settings/tree/master/Slic3r%20settings%20MK2) / 
[Slic3r settings 175](https://github.com/prusa3d/Slic3r-settings/tree/master/Slic3r%20settings%20175) / 
[Slic3r settings 3mm](https://github.com/prusa3d/Slic3r-settings/tree/master/Slic3r%20settings%203mm))
into a local folder, where Slic3r will find it. The destination depends on your operating system:

* Windows: "C:\Users\your_user_name\AppData\Roaming\Slic3r\" or "C:\Documents and Settings\your_user_name\Application Data\Slic3r\"
* Mac: "~/Library/Application Support/Slic3r/"
* Unix / Linux: "~/.Slic3r/"

In case you installed the Prusa3D Windows drivers package, the Start menu is filled in with Slic3r shortcuts. These shortcuts are stored in "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Prusa3D" and they point Slic3r to the particular settings folder using the --DataDir switch.

* "C:\Users\Public\Documents\Prusa3D\Slic3r settings MK2" for the MK2 & MK2S
* "C:\Users\Public\Documents\Prusa3D\Slic3r settings 175" for the legacy i3 with a 1.75mm extruder
* "C:\Users\Public\Documents\Prusa3D\Slic3r settings 3mm" for the legacy i3 with a 3mm filament extruder

Therefore if you installed the Windows drivers package from Prusa3D, you may as well extract the whole ([Slic3r settings](https://github.com/prusa3d/Slic3r-settings/tree/master/) to "C:\Users\Public\Documents\Prusa3D\".
