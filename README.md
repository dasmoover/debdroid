Debdroid V4
========

##Linux Chroot Daemon for Android Devices - Supports Lollipop 5.0


Debdroid is a tool for the Android platform which runs a full Linux distribution as a daemon. 
Any rooted device can run fully supported ARM distributions such as Kali, Debian, Ubuntu, etc.

Debdroid has been successfully tested on Android 2.3 and up to 5.0. Confirmed working on my N9.


#How To Install:
##1. Download the git repo
##2. Place ARM image at /sdcard/linux.img
##3. Flash the zip file in twrp

#How To Use:
##1. debshell "cmd" - run any command under linux
##2. debshell "passwd" - change root pass
##3. debshell "/etc/init.d/ssh restart" - starts ssh
##4. debshell bash - Gives you full access to a bash chroot
