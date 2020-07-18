Update 18-7-2020 :

DEVICE :

• Added Jelly
• Xiaomi part : fix FPS info need permissive mode, nuke audio gain and backlight dimmer, and add owl pic on display calibration
• clean up dt and add moar denial thanks to @Genkzsz11 for help
• sdm660_64: perf hal support
• IMS: Enable IMS feature flags for supported carriers
• data-ipa-cfg-mgr: Merge tag 'LA.UM.8.2.r1-06900-sdm660.0'

KERNEL :

• upstream AOSiP kernel to 4.4.230
• update wireguard to version 1.0.20200712

ROM :

16-7-2020
Update GMS updater component disable list
Update Ethereal theme colors
CPU info overlay updates
Translation updates
Pulse navbar audio gfx visualizer added
DeskClock: Remove notification sound from firing and snoozing channels
OwlsNest: Hardware key enable switch
Set Assistant UID of the current user
SystemUI: Add tile for enable/disable HW keys
Buttons: Hardware key disable support
OwlsNest: ticker/headsup availability
Status bar notification ticker
Contacts: Make the launch screen follow the system theme
AOSP Keyboard updates

9-7-2020 

Update translations
Add HeadsUp timeout function
Add Ethereal background
Allow the user to move battery icon to QS header
UI Improvements for screenrecord
Correct colors for icons in "Search settings" for dark theme
fonts: drop semi-bold from Gsans and FiraSans
Lockscreen clock updates
Extend brightness slider -/+ switch to the brightness mirror
Fix preview tile in grid option picker
Revert "ThemePicker: fix grid control activity name"
OwlsNest: Add Default USB Configuration switch
SystemUI: Add USB Tether tile
Trebuchet: Replace LockClock widget with DeskClock
Trebuchet: Add 5x6, 5x7 and 6x6 default workspaces
Revert "Add developer options for grid change for Styles"
Revert "Launcher3: we never want to disable grid control provider"
Disable QSB on first screen by default
QSB: request round search bar
Trebuchet: Update default workspace

The following only applies to our Official (non-Gapps) builds
AOSP Keyboard updates:
 - Add Bulgarian, Georgian and Ukrainian wordlists
 - Enable spellchecker for additional languages
 - HU enable predictive dictionary and remove unused letters
 - Add Hungarian QWERTY, enable predictive dictionary
 - Add support for Bepo keyboard layout
 - Add support for Australian English
 - Add Luxembourgish keyboard & spellchecking dictionary
Use a DayNight launch theme for AOSP Messaging and Dialer
AOSP Clock updates:
 - Remove notification sound from firing and snoozing channels
 - Move navigation bar to bottom
 - Also apply disabled color to annotations
 - Come to the dark side...
 - Rework notification channel implementation
