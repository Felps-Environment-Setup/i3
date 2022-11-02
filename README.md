# MY PERSONAL I3 CONFIGURATION

## Need to install

- Polybar:
    - Arch linux: `yay -S polybar`.

## Setup

- Access the directory `~/.config/i3` e delete everything.
- Clone this repository with `git clone <url> .`.
- Create the polybar directory with `mkdir ~/.config/polybar`.
- Copy the `launch.sh` and `config-polybar.ini` with the commands:
    - `cp ~/.config/i3/launch.sh ~/.config/polybar`
    - `cp ~/.config/i3/config-polybar.sh ~/.config/polybar`

Then logout and login again.

## Settings

- You can change the keyboard layout in line 198 of config file.

## Rofi themes

You can change the rofi theme typing the command `<leader>+d` and then selecting `Rofi Theme Selector`.

You can also install new rofi themes, here some links:

- [https://github.com/lr-tech/rofi-themes-collection](https://github.com/lr-tech/rofi-themes-collection)
