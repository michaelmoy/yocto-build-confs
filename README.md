# yocto
Yocto Projects. One Machine or Project per Branch

Put this repo in the yocto folder and in the poky/build/conf folder, make a link to the config files in this repo.

ln -s /home/michael/MoySandbox/yocto/yocto-build-confs/conf/local.conf /home/michael/MoySandbox/yocto/poky/build/conf/local.conf

ln -s /home/michael/MoySandbox/yocto/yocto-build-confs/conf/bblayers.conf /home/michael/MoySandbox/yocto/poky/build/conf/bblayers.conf

The 7 Inch Touchscreen works on dunfell automatically. All the other branches need to be build for TS only suppport.

The branch breakdown:

- rp4-64-w1-php-dunfell Has One Wire and Apache2 with PHP for a Dunfell branch build
- rp4-64-w1-php-qt5-dunfell Has qt5 Apps added

- rp4-64-qt6-kirkstone Has qt6 Apps using the kirstone branch
- rp4-64-apache2-qt6-kirkstone Has Apache2 added
