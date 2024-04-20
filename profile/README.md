# Droidian for miatoll

Repositories for building Droidian on miatoll devices.

## Features:
* Camera
* Sound
* Brightness control
* Rotation
* Fingerprint
* Auto brightness (partial)
* Proximity
* Vibration
* WiFi
* Hotspot
* NFC
* Bluetooth
* Calls/Data/SMS
* SD card
* Waydroid
* MTP
* GPS
* Encryption (partial)

## Download for my device:

https://github.com/gnumdk-miatoll/droidian/releases/tag/nightly

## Before Installation
### Android version
Device has to be downgraded to stock Android 10:
* For Redmi Note 9 Pro (Global) requires stock MIUI 12.0.2
* Redmi Note 9S and 9 Pro (India variant) require stock MIUI 12.0.4
* Redmi Note 9 Pro Max requires stock MIUI 12.0.3
* Redmi Note 9 Pro Max requires stock MIUI 12.0.3
* Poco M2 Pro requires stock MIUI 12.0.3
 
### Save SIM settings

The Access Point Name or APN can be found in the Settings menu of Android.
Take a piece of paper or a text editor, and write down everything that you see on that screen.
These are likely to include a URL (e. g., internet.carrier.net), a username, and possibly a password.


APN settings can also be found at http://apn.how/

## Installation
### Unlocking the bootloader

* First create an account at 
Download https://en.miui.com/unlock/download_en.html and follow tutorial:
https://new.c.mi.com/global/post/101245?utm_source=miui&utm_medium=official_web_faq&utm_campaign=official_web_miui

You really need to wait one week :(

### Install fastboot

https://command-not-found.com/fastboot

### Flash your device
```
$ sudo apt install 
$ unzip -d droidian  droidian-UNOFFICIAL-phosh-phone-xiaomi_miatoll-api29-arm64-nightly_20240420.zip 
$ cd droidian
$ ./flash_all.sh
```
