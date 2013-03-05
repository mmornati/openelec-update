openelec-update
===============

OpenElec for RaspberryPI Update Script

Installation Instruction
------------------------
To use this script you should copy it on your raspberry OpenElec 

----------------------------------------------------------------
scp update.sh root@openelec:
----------------------------------------------------------------

The default root user for openelec distribution is 'openelec'.

Then you should to connect via ssh to your OpenElec and execute the script.
It will automatically check if a new version is available, it shown to you the
new version name and ask for a confirmation.

----------------------------------------------------------------
root ~ # ./update.sh 
Update required, will download latest version.
Current Version: r13395
Latest Version: r13450 (OpenELEC-RPi.arm-devel-20130305190626-r13450.tar.bz2)
Continue (y/n)?y
Connecting to openelec.thestateofme.com (46.149.19.9:80)
OpenELEC-RPi.arm-dev 100%
Download complete

Uncompressing tarball, files extracted:
OpenELEC-RPi.arm-devel-20130305190626-r13450/
....
....

OpenELEC files succesfully moved to update directory
Temporary files deleted
System will restart shortly
Enjoy!
----------------------------------------------------------------


If you decide to install the new version, it will download the OpenElec tar.gz
file, decompress it in the update folder of the openelec distribution and
restart the RaspberryPI.

Installation and Update Done!
