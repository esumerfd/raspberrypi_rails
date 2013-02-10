raspberrypi_rails
=================

Experimenting with the features of the Raspberry PI. Ideas include:

1) Make the the site self deployable. No cap deploy, just https://localhost/update.

Site:

It might not be running at the moment but give it a shot:

[http://pi.bitbashers.org:3000/]

Background
==========

These are the steps taken to get rails running on the Raspberry PI.

-  sudo apt-get install ruby1.9.3
-  sudo apt-get install rubygems
-  sudo apt-get install libsqlite3-dev
-  sudo gem install rails
-  gem install sqlite3
-  sudo apt-get install node

Then to get "git" to mainain the source:

-  sudo apt-get install git

Raspberry PI Setup
==================
The basic setup of the machine is not unusual but these where the things
that I touched from the boot config menu (raspi-config)

-  update raspi_config
-  change_local to en_US UTF-8 (defaults en_GB)
-  change_timezone US/Estern
-  config_keyboard (needs to be switched to US Apple)
-  boot behavior to no-desktop (don't want X crashing at boot time)
-  ssh enabled
-  expand_rootfs (to use the whole SD card for disk space)



