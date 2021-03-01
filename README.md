<div align="center">
    <img src="https://apps.soldat2d.com/projects/scrcnv/logo/48x48.png">
</div>

# ScrCnv

## About

**ScrCnv** is a tool for automatic conversion of [Soldat](https://github.com/Soldat/soldat) screenshots.

This app is not the first try to make an automated screenshots conversion tool for Soldat (take a look at [Soldat Screenshot Converter](https://forums.soldat.pl/index.php?topic=35377.0) by Toumaz), but it has a list of advantages:

- it doesn't require renaming of `Soldat.exe`
- it doesn't require administrator permissions
- it doesn't require .Net Framework
- it doesn't overwrite recently saved screenshots

## Features

- "On-the-fly" screenshots conversion, right after they have been taken
- Force displaying of scoreboard (_"F1 menu"_) at the end of the match<sup>*</sup>
- With "Delete" option enabled original screenshot files wouldn't even be written to the disk (i.e. to conserve the use of your HDD/SSD)
- With "SmartDeletion" feature you are able to prevent saving endgame screenshots of _unwanted_ maps and/or after map restarts
- With "SmartRenaming" feature you are able to structurize your screenshot files/folders in various ways
- Up to 35% better 24-bit PNG compression level (compared with current Soldat's encoder)
- 8-bit PNG encoding (with optional dithering)
- Fast access to the most important folders (`Soldat`, `\screns`, `\demos`, `\profiles`)
- Run any `*.exe` file (except of `Soldat.exe` and `unins####.exe`) via the tray menu
- Close Soldat via the tray menu
- App's tray menu is integrated with Soldat's tray icon (click `[Right Mouse Button]` to show it)
- Auto-launch with Soldat

_<sup>*</sup> For now, "ForceF1" feature doesn't work when match ends because of points limit in non-team based game modes (DM, PM & RM)_

## Screenshots

![](https://apps.soldat2d.com/projects/scrcnv/screenshots/v041_1.png)

![](https://apps.soldat2d.com/projects/scrcnv/screenshots/v041_2.png)

![](https://apps.soldat2d.com/projects/scrcnv/screenshots/v041_3.png)

![](https://apps.soldat2d.com/projects/scrcnv/screenshots/v041_4.gif)


## Config (`ScrCnv.ini`)

```ini
[General]
; Conversion format:
; 0 - PNG, 1 - JPEG, 2 - JPEG 2000
Format = 0
;
; Encoding quality (for JPEG & JPEG 2000 formats only):
; 0 - worst, 10 - maximum
Quality = 10
;
; Image color depth (for PNG format only):
; 8 - 8-bit, 24 - 24-bit
Depth = 8
;
; Apply dithering (for 8-bit PNG format only):
; 0 - disabled, 1 - enabled
Dithering = 0
```

## Install

Extract the `IdnDL.dll` file from the attached archive into the Soldat folder.

## Uninstall

Delete `IdnDL.dll` and `ScrCnv.ini` files from the Soldat folder.

## Compatibility

 Version    | Notes
----------- | -----------
| v0.4.1    | Soldat 1.7.1
| v0.4.0    | Soldat 1.7.0
| v0.3.0    | Soldat 1.6.6
| v0.2.0    | Soldat 1.5.0 - 1.6.2 (tested with 1.5.0, 1.6.0 and 1.6.2 versions)

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for details.

## Discussion

See the post on [forums.soldat.pl](https://forums.soldat.pl/index.php?topic=41620.0).
