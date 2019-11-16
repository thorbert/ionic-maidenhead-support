---
layout: default
---

# Quick Start

![Quick Start Image](/ionic-maidenhead/assets/images/ionic.png)

# Description

This app is designed for amateur radio "rovers" (operators who move from location to location while operating). This app provides a quick and easy way to sense your current [maidenhead grid locator](https://en.wikipedia.org/wiki/Maidenhead_Locator_System) using the Ionic's onboard GPS. Grid locators are frequently used in VHF/UHF contests and are often exchanged in low power (QRP) operating modes. This app puts the geolocation on your wrist, freeing you up to move about, tune stations, and enjoy operating without having to figure out your current operating location.

Pressing the upper-right button will activate the position sensor, which will remain active until a configurable number of samples have been received (see settings). You'll see a satellite icon while the position sensor is active.

Pressing the lower-right button will deactivate the position sensor. The satellite icon will not be visible if the position sensor is inactive.

Pressing the left button will exit the app.

# Settings

The app has additional settings, available on you mobile device, to control behaviors that aren't usually necessary to modify during normal operation. These settings include:

* GPS active on start (acquire position from GPS when app starts)
* Keep screen on (drains power if always on)
* Position sample limit (automatically disables GPS to conserve power after N samples have been read)
* Maidenhead grid precision (2,3,4,5)
* Background color selector
* Label color selector
* Value color selector