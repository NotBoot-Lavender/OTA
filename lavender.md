Update 25-7-2020 :

DEVICE :

• clean up and add moar denial
• enable livedisplay overlay and migrate to 2.0
• update overlay from stock
• totally fix dt2w issue
• filter out the conference host in the CEP for some carriers
• initial gapps build : disable RRO enforce fix setup error on boot
• etc

KERNEL :

• upstream AOSiP kernel to 4.4.231
• merge caf tag 'LA.UM.8.2.r2-02300-sdm660.0'
• some improvement

ROM :

24-7-2020 

Move remaining active edge/motion sense code to settings for the Pixel 4 series
Add support for per app network isolation
Redo gestures page in OwlsNest
Update GMS updater component disable list
Update Ethereal theme colors
CPU Info overlay updates:
- Don't show during doze
- Check early if CPU temp is available
- Fix CPU info overlay text layout
- Bring back CPU temperature to CPU info overlay
- Adjust CPU overlay style
- Fix number of CPUs check

The following only applies to our Official (non-Gapps) builds:
AOSP clock Updates:
- Fix crash when there are pending processes
- Add increasing volume option for alarm clocks
- Fix FAB not being shown everytime
- Properly align settings
