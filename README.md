about
=====

optimize is a wrapper around various file size optimization tools. It
currently losslessly optimizes these mime types:

* application/javascript
* application/x-virtualbox-vdi
* image/gif
* image/jpeg
* image/png
* image/x-apple-ios-png
* text/css
* text/html

requirements
============

optimize relies on these tools (depending on the mime types you like
to optimize): gifsicle, jpegoptim, optipng, VBoxManage, yui-compressor

install requirements on Ubuntu Linux
------------------------------------

If you like to optimize images:

        sudo apt-get install gifsicle jpegoptim optipng

If you like to optimize CSS and JavaScript:

        sudo apt-get install yui-compressor

If you like to optimize Virtual Disk Images (VDI):

        sudo apt-get install virtualbox
