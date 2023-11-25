Download Rufus [Here](https://rufus.ie/en/)

# Role
Rufus is a bootable usb drive utility. This is the software I used to create the bootable SD card from the [[Raspberry Pi OS]]
# Setup
Download the executable and run it – no installation is necessary.

The executable is digitally signed and the signature should state:

- _"Akeo Consulting"_ (v1.3.0 or later)
- _"Pete Batard - Open Source Developer"_ (v1.2.0 or earlier)
#### Notes on DOS support:
If you create a DOS bootable drive and use a non-US keyboard, Rufus will attempt to select a keyboard layout according to the locale of your system.
#### Notes on ISO Support:
All versions of Rufus since v1.1.0 allow the creation of a bootable USB from an ISO image.
Creating an ISO image from a physical disc or from a set of files is very easy to do however, through the use of a CD burning application.
# Information
Optionally clone it from github:
> $ git clone https://github.com/pbatard/rufus