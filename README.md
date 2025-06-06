## Magnetic gtk theme

![2pxrounded](https://github.com/user-attachments/assets/858bde3b-bb98-42b3-bca0-a47a5ae32d60)

## Requirements

- GTK `>=3.20`
- `gnome-themes-extra` (or `gnome-themes-standard`)
- Murrine engine — The package name depends on the distro.
  - `gtk-engine-murrine` on Arch Linux
  - `gtk-murrine-engine` on Fedora
  - `gtk2-engine-murrine` on openSUSE
  - `gtk2-engines-murrine` on Debian, Ubuntu, etc.
- `sassc` — build dependency

- `Icon theme` [Tela-circle](https://github.com/vinceliuice/Tela-circle-icon-theme)

## Donate

If you like my project, you can buy me a coffee:

<span class="paypal"><a href="https://www.paypal.me/vinceliuice" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>

## Installation

### Manual Installation

Run the following commands in the terminal:

```sh
./install.sh
```

> Tip: `./install.sh` allows the following options:

```
-d, --dest DIR          Specify destination directory (Default: ~/.themes)
-n, --name NAME         Specify theme name (Default: Magnetic)
-t, --theme VARIANT...  Specify theme color variant(s) [default|purple|pink|red|orange|yellow|green|teal|grey|all] (Default: blue)
-c, --color VARIANT...  Specify color variant(s) [standard|light|dark] (Default: All variants)
-s, --size VARIANT...   Specify size variant [standard|compact] (Default: standard variant)

-l, --libadwaita        Link installed gtk-4.0 theme to config folder for all libadwaita app use this theme

-r, --remove,
-u, --uninstall         Uninstall/Remove installed themes or links

--tweaks                Specify versions for tweaks
                        1. [nord|dracula|gruvbox|all]   (Nord/Dracula/gruvbox/all) ColorSchemes version
                        2. black                        Blackness color version
                        3. float                        Floating gnome-shell panel style
                        4. outline                      Windows with 2px outline style

-h, --help              Show help
```

> For more information, run: `./install.sh --help`

### Flatpak Installation

Automatically install your host GTK+ theme as a Flatpak. Use this:

- [pakitheme](https://github.com/refi64/pakitheme)

