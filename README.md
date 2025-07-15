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

lossy optimzation (sorta) of these mime types is supported

* video/mp4
* video/quicktime[1]
* video/webm[1]
* video/x-matroska[1]

[1] files are converted to mp4 during optimzation

requirements
============

optimize relies on these tools (depending on the mime types you like
to optimize): gifsicle, jpegoptim, optipng, VBoxManage, yui-compressor,
ffmpeg

install requirements on Ubuntu Linux
------------------------------------

If you like to optimize images:

        sudo apt-get install gifsicle jpegoptim optipng

If you like to optimiue video files:

        sudo apt-get install ffmpeg

If you like to optimize CSS and JavaScript:

        sudo apt-get install yui-compressor

If you like to optimize Virtual Disk Images (VDI):

        sudo apt-get install virtualbox

If you like to optimuze video files:

        sudo apt-get install ffmpeg
