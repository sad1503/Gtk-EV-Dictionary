# Gtk-EV-Dictionary
## About
An English-Vietnamese dictionary for LINUX-kernel OS.
User interface is powered by GTK library.
## Installation

Download and install GTK 3.0 at:

https://www.gtk.org/download/linux.php 

Run `sudo apt-get install build-essential libgtk-3-dev` to add gtk headers to `pkg-config` search path.

Compile the codes using
```
gcc tudien.c -o execfile -w bt-5.0.0/lib/libbt.a -rdynamic `pkg-config --cflags --libs gtk+-3.0`
```

Then you can run the application by `./execfile`

## Demostration

[![Watch the video](https://img.youtube.com/vi/7Z3-SUrP3Ds/maxresdefault.jpg)](https://youtu.be/7Z3-SUrP3Ds)
