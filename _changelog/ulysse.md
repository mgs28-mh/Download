---
codename:ulysse
---

=====================
  28 September 2021
=====================
Source Side Changelog:
 * Bump to 4.7
 * Merged 'LA.QSSI.11.0.r1-13200-qssi.0' CAF Tag
 * Merged August Securoty Patch
 * Allow to hide VPN icons in the statusbar
 * Some changes for PixelPropUtils to pas SafetyNet
 * Fix Battery Usage Header layout
 * Limit Keyguard charging stats updates
 * Fix some UI Crashes that really annoying
 * Set OpenGL Skia as default renderer
 * Add proper config for WiFi 5GHz support

Include 4.6 version update Changelog:
 * Use Android 12's FOD Icon
 * Fix touch issue on split screen
 * Set device name to market name if available
 * Use FileChannel#size for APK Sign verification
 * Make entityheader transparent
 * Add back missing FORCE_STOP_PACKAGES perm to SystemUI
 * Added Data usage info on Expanded QS Footer
 * Install seccomp filter even if permissive builds
 * Sleep when proximity is covered for 3 secs
 * Use temporary TwilightState when location is not availavle
 * Make Battery icon on QS Panel clickable
 * Save and use last fetched location
 * Make Guest user avatar follow system accent
 * Rework on the Action Buttons looks
 * Fixed Option of conquerOS Themer being rested in every reboot
 * Added Quick Suggestion section on conquerOS Features menu
 * Redesign Battery Info header
 * Fix date showing null on Shapeshift Tweleve clock face
 * Fix some UI Bugs
 * Added bouncy overscroll animation
 * Move conquerOS gesture settings to system gesture option
 * Follow system accent on SetupWizard
 * Fix vdso32 building for 4.19 kernels
 * Allow to use boottime as timestamp reference 
 * Avoid calling getSystemCameraKind if the camera was not mapped yet
 * Fix thread safety issues
 * Some more minor UI and bug fixes
 * New default wallpaper

Device Side Changelog:
 * Upstream Kernel to 4.9.284
 * Add XiaomiParts
 * Ship with GCamGo
 * Add KCAL and Sound Control Support
 * Misc and Some minor improvemnts

=====================
    15 August 2021
=====================
Source Side Changelog:
 * 4.5 Code base release
 * Merged LA.QSSI.11.0.r1-12700.01-qssi.0
 * Added Russian translation
 * Use wallpaper color on Android 12 Clock
 * Fixes on Android 12 Clock
 * Use normal font just like real Android 12 Clock
 * Grant suspend permission for Super Battery Saver
 * Added OxygenOS Icon Pack
 * Added Shapshift's Android Tweleve Clock
 * AppLock: Fix biometric prompt disappearing if app launched from resolver
 * fonts: Fix reference to Noto Sans Javanese 
 * Reworked Panel and change icons
 * QS Header item reorder
 * Add OOS Volume icons
 * Rework QS Drag handle
 * Disbale blur screen off animation
 * Added SoftAPManager. Now you can block someone used your Hotspot
 * Ask lockscreen pass/PIN to use Hotspot, and work mode tile
 * Use Cloudflare DNS
 * Hide sensitive information by default
 * Added Quick PIN Unlock. Phone will be unlocked once you enter correct PIN.
 * Use media artwork as QS Media Player Background
 * Some minor UI fixes
 * Some minor improvemnts and fixes

Device Side Changelog:
 * Upstream kernel to v4.9.279
 * Fix Dirac and bring back Dirac QS tile
 * Some minor improvemnts

=====================
    3 August 2021
=====================
Device Side Changelog:
* Fix Calling issue in previous build
* Upstream Kernel to 4.9.277
* Merge tag LA.UM.9.6.2.r1-04800-89xx.0 in kernel
* Enable LZ4 and ZSTD zram compression
* Update blobs from LA.UM.9.6.2.r1-04100-89xx.0

=====================
    22 July 2021
=====================
 - Merged LA.QSSI.11.0.r1-12600-qssi.0
 - Allow seamless rotation when PIP enabled
 - Added button to copy crash log to HasteBin
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
 - Initial build
