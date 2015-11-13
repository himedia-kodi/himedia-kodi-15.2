##############himedia readme
### himedia kodi 15.2
########################################################################################
This is a special branch for RockChip rk3368 platform. First of all, you need the lastest verson of rk3368 sdk. The implement of decoder and render are same as Amlogic. It request a library name "librkffplayer.so", you can find it on lastest version rk3368 sdk. And the more important thing is, you need a device run with rk3368, such as HiMadie H8 Octa Core, which had deep modified to meet this new speicial version.

Our modifies were commited to branch himedia-15.2, so please checkout it after you clone repository.

$git clone https://github.com/himedia-kodi/himedia-kodi-15.2.git

$git checkout -b himedia-15.2 origin/himedia-15.2

We modified ffmpeg too, so after checkout branch, apply the ffmpeg patch "kodi-ffmpeg-patch-20150910.patch" to your ffmpeg. Then build the apk, and install to run it.

You'd better to run your apk on HiMadie H8 Octa Core, we are not sure if it run well on other devices.

Have fun and enjoy!
