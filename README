# Xfce PulseAudio Panel Plugin

This modified version of the Xfce Pulseaudio Panel Plugin supports custom volume icons! Icons are defined as 
constants in the code, so to change you need to recompile.

## Configuration

Modify line 64 of `panel-plugin/pulseaudio-button.c` with paths from your filesystem.

```
static const char* icon_filenames[] = {"/home/josep/.scripts/xfce-i3-bar/ico/volume/volume-mute.png",
                                      "/home/josep/.scripts/xfce-i3-bar/ico/volume/volume-low.png",
                                      "/home/josep/.scripts/xfce-i3-bar/ico/volume/volume-medium.png",
                                      "/home/josep/.scripts/xfce-i3-bar/ico/volume/volume-high.png"};
```

## Installation

To install, run the following commands in a terminal at the repository root.

```
$ ./autogen.sh
$ ./configure --prefix=/usr/
$ make
$ sudo make install
```
To see the changes, log out and back in or restart the panel with `xfce4-panel -r`

# Original Readme File

Xfce PulseAudio Panel Plugin
============================

The Xfce PulseAudio Plugin is a plugin for the Xfce panel which provides a
convenient way to adjust the audio volume of the [PulseAudio sound system][1]
and to an auto mixer tool like pavucontrol. It can optionally handle
multimedia keys for controlling the audio volume.

See the file INSTALL for detailed instructions on how to build and install
Xfce PulseAudio Plugin.

[1]: http://www.freedesktop.org/wiki/Software/PulseAudio/ "PulseAudio Website"
