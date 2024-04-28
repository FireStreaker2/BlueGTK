# BlueGTK

A GTK theme based off of the [Catppuccin Mocha Standard Teal Dark](https://github.com/catppuccin/gtk/releases/download/v1.0.3/catppuccin-mocha-teal-standard+default.zip) theme.

# Note
This repository contains all the raw CSS and image files for the GTK theme, which is just a lightly modified version of the original. All credit belongs to the original owners, this just serves as a way for me to store the theme I use on a daily basis. An example usage can be found in my [dotfiles](https://github.com/FireStreaker2/dotfiles).

# Usage

## Installation

Installing the BlueGTK theme is very simple, only a couple commands need to be run.

```bash
$ git clone https://github.com/FireStreaker2/BlueGTK.git
$ sudo mv BlueGTK /usr/share/themes/
```

## Application

In order to then use it, edit your GTK configuration files like so:

GTK 2:

```
# ~/.config/gtkrc
include "/usr/share/themes/BlueGTK/gtk-2.0/gtkrc"

gtk-theme-name="BlueGTK"
```

GTK 3/4:

```
# GTK 3: ~/.config/gtk-3.0/settings.ini
# GTK 4: ~/.config/gtk-4.0/settings.ini

[Settings]
gtk-theme-name = "BlueGTK"
```

# License

[MIT](https://github.com/FireStreaker2/BlueGTK/blob/main/LICENSE)
