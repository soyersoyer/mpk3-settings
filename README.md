# MPK3 Settings

This is a GTK UI that allows to configure the Akai MPK mini III MIDI keyboard.
It currently allows for reading the programs settings, changing them and writing
back to the device and reading and writing the settings to a file.
It's in a very early stage of development and has not been thoroughly tested.

Use at your own risk.

## Installation

### From Flathub

```
flatpak install flathub io.github.tsmetana.mpk3-settings
```

### From source

```
$ autoreconf -i
$ ./configure
$ make
```
The resulting binary doesn't need to be installed but `make install` / `make uninstall` works too.
