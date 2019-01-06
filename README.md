Raspberry Pi Framebuffer Copy
=============================
This program is used for copying the primary framebuffer to the secondary framebuffer (eg. FBTFT). It requires the latest Raspberry Pi firmware (> 2013-07-11) to work.

Modifications
----------------------------
* Copy synced to VSYNC
* Skip every other frame (30fps)
* Ability to skip every x frame (TODO)
* Custom rotation (TODO)
* Custom cropping/scaling (TODO)

Build
-----

    $ mkdir build
    
    $ cd build
    
    $ cmake ..
    
    $ make 
