RPI-Wireless-Hotspot
--------------------

Configures your Raspberry Pi to use an attatched WiFi dongle as a hotspot,
broadcasting your ethernet connection to other devices.


Features:
=========

* The created hotspot runs automatically on boot, no extra configuration necessary

* Your new network is WPA encryped, default SSID is "RaspberryPiFi", WPA key
  is "123456789A".

* Once set up, the local network facilites of the Pi will still operate as 
  normal

Requirements:
=============

1. A Raspberry Pi model B running raspbian

2. A linux compatible wifi dongle, with the appropriate drivers installed

3. An active ethernet connection


Installation:
=============

* Navigate to folder, and execute "./install"

* This should automatically set everything up and leave you ready to go


Notes and configuration
=======================

* This setup has been tested on a fresh install of raspbian from the official downloads page

* It is advised that this be set up on a fresh install

* if set up on an existing install it should work fine, but take note that this will overwrite certain network config files... if you have
  not modified them then you _should_ have nothing to worry about

* on some occasions, running a full "apt-get upgrade" seems to break the setup, at this point the reason is uncertain.

