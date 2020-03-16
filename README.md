nord-gtk
=====

nord-gtk is a fork of oomox-gtk-theme: https://github.com/themix-project/oomox-gtk-theme.

### Theme examples

![Screenshot_Page_1](https://raw.githubusercontent.com/......png "Screenshot_Page_1")
![Screenshot_Page_2](https://raw.githubusercontent.com/......png "Screenshot_Page_2")
![Screenshot_Page_3](https://raw.githubusercontent.com/......png "Screenshot_Page_3")

#### Prerequisites

You need to have those dependencies:
 - `glib-compile-schemas`
 - `gdk-pixbuf-pixdata`
 - `sassc`
 - `gtk3`

##### Arch Linux

```
sudo pacman -S --needed bash grep sed bc glib2 gdk-pixbuf2 sassc librsvg
```

#### How to generate the theme using CLI:

```bash
git clone https://github.com/libXq/nord-gtk
cd nord-gtk
./export_theme.sh
```