Raspberry Pi Framebuffer Copy
=============================
This program used for copy primary framebuffer to secondary framebuffer (eg. FBTFT). It require lastest raspberry pi firmware (> 2013-07-11) to working properly.

Notable Changes in this Fork
----------------------------
* Copy synced to VSYNC (TODO)
* Ability to skip every x frame (TODO)
* Custom rotation (TODO)
* Custom cropping/scaling (TODO)

Build
-----

    $ mkdir build
    
    $ cd build
    
    $ cmake ..
    
    $ make 
