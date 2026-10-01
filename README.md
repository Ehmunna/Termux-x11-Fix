![logo](file_00000000c9e482118aa7f63af58e9cbb.png)


Shizuku & aShell Setup Guide
This guide explains how to install and set up Shizuku and aShell on Android.

# Shizuku Install
Download Shizuku
https://t.me/ehmunnax/23

⚙️ Setup Steps

1. Connect your phone to any Wi-Fi network.
2. Open Developer Options.
3. Enable the following options:
   - Wireless Debugging
   - Security Settings (if available on your device)
4. Open Wireless Debugging and select Pair device with pairing code.
5. Enter the displayed pairing code when requested.
6. Start the Shizuku service.
7. Check that Shizuku is running successfully.

## aShell Install

Download aShell 

https://t.me/ehmunnax/21

⚙️ Setup Steps

1. Install and open aShell.
2. Grant/request the required Shizuku permission.
3. Start the aShell service/session.
4. You can now use aShell with the required permissions.


📌 Requirements

- Android device
- Developer Options enabled
- Wireless Debugging
- Shizuku
- aShell
- Wi-Fi connection for the wireless-debugging setup

## First command 
```
/system/bin/device_config set_sync_disabled_for_tests persistent
```
```
/system/bin/device_config put activity_manager max_phantom_processes 2147483647
```
```
adb shell settings put global settings_enable_monitor_phantom_procs false
```
