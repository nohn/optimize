[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fnohn%2Foptimize.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fnohn%2Foptimize?ref=badge_shield)

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


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fnohn%2Foptimize.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fnohn%2Foptimize?ref=badge_large)