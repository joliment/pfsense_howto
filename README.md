pfsense_howto
=============

####Configuration and all that bunch of stuff.####



1. Download an *.iso image file from  [pfsense.org](http://pfsense.org  "Yeah click it!")


2. Get [Physdiskwrite](http://m0n0.ch/wall/physdiskwrite.php "You'll need this!") utility for making a bootable USB    


3. Make bootable USB drive
   
(with Windows cmd.exe)

>`physdiskwrite [-u] [-d driveno] <image-file>` 

for example
>`physdiskwrite -u pfSense-1.2.3-RELEASE-xg-nanobsd.img.gz` and then choose 0..n option

Of course if you use USB memory bigger than 2 GB (likely to happen) remember to use `-u` (if not this is unnecessary)

The fastest way is to run cmd.exe "As an Administrator" and than manually move to the directory where are both Physdiskwrite and *gz files) with `dir` and `cd`
___
**Don't just simply drag-and-drop the image file onto the physdiskwrite.exe icon, unless you are certainly sure you are using the hidden "Administrator Account" in Windows!**

