### Additional Information
Built and configured using [slock-flexipatch](https://github.com/bakkeby/slock-flexipatch)

### Patches included:
- [blur_pixelated_screen](https://tools.suckless.org/slock/patches/blur-pixelated-screen/)
    - sets the lockscreen picture to a blured or pixelated screenshot

- [dpms](https://tools.suckless.org/slock/patches/dpms/)
    - interacts with the Display Power Signaling and automatically shuts down the monitor after a
    configurable amount of seconds
    - the monitor will automatically be activated by pressing a key or moving the mouse and the
    password can be entered then


### Original README
```
slock - simple screen locker
============================
simple screen locker utility for X.


Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


Running slock
-------------
Simply invoke the 'slock' command. To get out of it, enter your password.
```
