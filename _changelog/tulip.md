---
codename:tulip
---
=====================
    29 July 2021
=====================
 - Fixed Android 12 Clock face marginEnd
 - Added NetworkTraffic Meter
 - Enabled Wi-Fi Display Cast
 - Added and enabled Xiaomi Doze
 - Enabled Zygote Preforking for better app loading performance
 - Improve battery backup
 - Some cleanup and improvement on init scripts
 - Some small bug fixes and improvement 

=====================
    20 July 2021
=====================
 - Merged LA.QSSI.11.0.r1-12600-qssi.0
 - Allow seamless rotation when PIP enabled
 - Added button to cpoy crash log to HasteBin
 - Redesigned Power menu glbal action
 - Android S Media Seamless background 
 - Implement SystemUIGoogle from redfin 11 
 - Enable weather on lockscreen date [Gapps] Only
 - Update FOD Indication margin [FOD Devices only]
 - Fix notification overlapping clock faces
 - Added Android S, S DP3, OnePlus Analog Number, Minimal, and Roman
 - Added Google Sans. Manrope, and OnePlus sans fonts
 - Fixed margin for Android S Clock face
 - Use ListPreference instead of Drop down on some settings option
 - Removed shadow under action bar on Light theme
 - Removed unrequired dividers in some sections
 - Use normal preference for BatteryTip
 - Enabled updateable APEX
 - Corner roundedd when notch hiden
 - Fix headset button keymapping

=====================
    12 July 2021
=====================
 - 4.4 Code bas release
 - Merged LA.QSSI.11.0.r1-12400.02-qssi.0
 - Redesigned Settings Dashboard UI 
 - Allow Hotspot client use VPN upstream 
 - Add Native Zygote fork loop 
 - OxygenOS 11 QS Panel style
 - Updated prebuilt apps 
 - Optimized new jemalloc. 69FPS POOPG. thanks to ProtonAOSP 
 - Allow user to unlink notification amd ringtone volume 
 - Unlimited Photo storage with original quality (Gapps variant only)
 - Fix lock icon drawable 
 - Fix some overlay 
 - Some other small improvement and optimization 
 - Rebased tree for tulip, whyred, wayne, and jasmine_sprout
 - Rework on WFD
 - Update IMS Blobs from LA.UM.9.6.2.r1-04100-89xx.0

=====================
    20 June 2021
=====================
 - 4.3 code base release
 - Based on LA.QSSI.11.0.r1-12200-qssi.0 CAF Tag!
 - Redesigned About Phone
 - Redesigned Settings Dashboard
 - Redesigned ConquerOS Features Dashboard
 - Redesigned default Settings preference style.
 - Added ConquerOS Themer
 - Added new ConquerOS wallpaper
 - Added Option to change HW renderer to Vulkan under dev options
 - Added Long Screenshot
 - Added long press power button to enable flashlight
 - Added option to hide lock icon on lockscreen
 - Added 404 IDE, 404 Sammy, and Shapeshift Clock Face
 - Added Oxypink, Oixel Blue, Neon Carrot, and Blueline accent color
 - Show LTE+/4G+ if possible
 - Reduced UI corner roumd radius
 - Improvement for live blur
 - Added new wallpaper
 - Fixed QS Panel glitch on devices with small display/lower resolution
 - Enabled Permission Hub 2.0
 - Added OOS Silent Icon on status bar
 - Now you can prevent Battery Saver from reduce display refresh rate
 - Some improvement for QS Panel detail and UI
 - Some improvement for System Navigation
 - Some Improvement for Package manager
 - Moved Battery Graph to Main Battery Info
 - Under the hood performance improvements

=====================
    12 March 2021
=====================

* March security patch
* Implement PixelPropUtils to pass device certification
* Implement Face Unlock
^ Add OxygenOS Style Clear Button
* Small updates on ConquerUI
* Added per-apps Data, WIFI, VPN Restriction
* Some underhood fizes
* vibrate on QS tile click

=====================
    19 March 2021
=====================

* Use Pixel libperfmgr AIDL Power HAL
* Update perfd from taimen
* Fixed SafetyNet Problem not passing
* Update IMS Blobs from LA.UM.9.6.2.r1-03600-89xx.0
^ Update WFD Blobs from LA.UM.9.6.2.r1-03600-89xx.0
* Updated OpenGLES, Vulkan, Adreno Blobs
* Enables fluence voice recording
* Removed unused HMP aware boot argument
* Removed unused soundtrigger blobs
* Some underhood performance tuning
* Fixed Dialog Rounded corner overlay
* Added toggle to use ConquerUI Black and White QS Tile
* Added support for exfat SD Cards
* Removed QS Panel Drag Handle
* Tweaked QS Panel UI

=====================
    19 April 2021
=====================

* Bump to 4.2
* Added Aggressive Battery
* Added Volum Panel Styles
* Eanbled PermissionHub
* Added Battery Icon Style
* Added opyion to show Battery Percentage
* Reorder QSTiles
* Redesign QS Media Player
* Make QS Tile looks even nicer
* Added gesture to skip track by holding volume button
* Added FP Icon if FP Registered on keyguard
* Small fixes and improves

=====================
     03 May 2021
=====================

* applock: Check current and called activity package before locking again
* Added LiveDisplay
* Remove ugly network activity arrow on status bar
( Remove "Clean All" Text button
* Remove FP Icon on lockscreen
* Allow to limit Screenrecorder framerate
* Apply system_icons_keyguard_padding_end to parent view
* Revert secondary home handler
( Merge CAF Tag "LA.QSSI.11.0.r1-11600-qssi.0"
