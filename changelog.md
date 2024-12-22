# Delta Changelog

## Update v1.4.0 - Network widget overhaul (Dec 22, 2024)

### Network widget overhaul
 - Network skin replaced with new version that fits in better with the theme
 

## Update v1.3.4 - Uptime widget overhaul (Nov 2, 2023)

### Uptime widget overhaul
 - Replaced the uptime widget with a new more sleek version to fit better with the theme
 - It will now only tell you days and hours since last restart by default
 - Hovering the widget will give you a more precise time (minutes and seconds)
 - Added font configuration into the config

### Changes
 - Renamed "Drive" directory to "Storage"

### Fixes
 - Fix for GPU bar exceeding 100% during usage spikes

## Update v1.3.3 - User greetings (Nov 11, 2022)

### Additions
- Added a greeting skin that changes based on time

### Fixes
- Reversed the day of the month and month so it is in the correct order (date/date and time skins)

## Hotfix v1.3.2 - Spectral colours (May 5, 2022)

### Fixes
- Fixed the GPU color coded skin not having any red

## Update v1.3.1 - Spectral colours (Apr 19, 2022)

Finally got this feature working, now the colour coded bar skins will change from from green to red on a spectrum instead of having four colour states.

### Changes
- Colours will now change on a spectrum rather than have 4 possible colours

## Update v1.3 (Feb 12, 2022)

### Additions
- Added new Network skin
- Added a GPU bar
- Added several more configuration options

### Changes
- Moved the detailed clock and the large clock skins into seperate directories so both can be loaded at the same time.
- Added configuration instructions to the README

## Hotfix 1.2.1 (Nov. 13, 2021)

### Fixes
- Fixed C Drive Color Coded skin not changing colours

## Update 1.2 (Sept. 26, 2021)

### Additions
- Added a config file in @Resources/config.ini
- Added a custom drive skin that will display the drive defined in the config file

### Changes
- Markdown formatting for the changelog file

### Fixes
- Fixed the CPU bar's text not being spaced out enough
- Fixed the slightly too dark colors for the color coded D: drive skin
- Color coded D: drive skin now changes colors properly

## Update v1.1 (2021/07/20)

### Additions
- Added a Drive D: and E: skin
- Added a toolbar which you can put other Rainmeter skins on. Designed for Delta skins
- Created changelog.txt

### Changes
- Change "Disk" to "Drive" in the C Drive.ini

### Fixes
- Fixed issue where some of the Large Clock.ini would sometimes get cut off
- Fixed inconsistencies between licenses

### Known Bugs
- It seems that the color for all the "Drive Color Coded.ini" skins are not displaying the proper shade of green, I have no clue why.