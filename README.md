<h3 align="center">
  Lycia Dotfiles
</h3>

# 🪴 Overview

A clean Linux setup featuring my own Lycia palette. Designed for both aesthetics and functionality, with purple, red, and rose accents, and plenty of non-disrupting eye candy.

All wallpapers are by [Annie Spratt](https://www.instagram.com/anniespratt)

## 🧠 Main Principles

- Consistency throughout the system
- Aesthetics above pure functionality, without disrupting workflow
- Unified style and reduced visual noise

## 💜 System Setup

- Operating System: [Arch Linux](https://archlinux.org)
- Colour Scheme: [Lycia](https://lycia.aevstiel.com)
- Desktop Environment: [GNOME](https://www.gnome.org) by [GNOME Foundation](https://foundation.gnome.org)
- GTK Theme: [Lycia GTK](https://github.com/aevstiel/Lycia-GTK-Theme) by [Aevstiel](https://github.com/aevstiel)
- Fonts: [Figtree](https://www.erikdkennedy.com/projects/figtree.html) by [Erik Kennedy](https://www.erikdkennedy.com)
- Icon Theme: [Reversal](https://github.com/yeyushengfan258/Reversal-icon-theme) by [yeyushengfan258](https://github.com/yeyushengfan258)
- Folder Icons: [Catppuccin Icons](https://store.kde.org/p/1715570) by [Faust Kropsvart](https://github.com/Fausto-Korpsvart)
- Terminal: [Ptyxis](https://gitlab.gnome.org/chergert/ptyxis) by [Christian Hergert](https://gitlab.gnome.org/chergert)
- Shell: [Z Shell](https://www.zsh.org) by [Paul Falstad](https://www.falstad.com)
- Zsh Theme: [PowerLevel10K](https://github.com/romkatv/powerlevel10k) by [Roman Perepelitsa](https://github.com/romkatv)
- Fetch: [Neofetch](https://github.com/dylanaraps/neofetch) by [dylanaraps](https://github.com/dylanaraps)
- Neofetch Theme: [Amethyst Fetch](https://github.com/aevstiel/amethyst-fetch) by [Aevstiel](https://github.com/aevstiel)
- Browser: [Zen](https://zen-browser.app) by [Zen Team](https://zen-browser.app/about)
- Start Page: [DelioFox](https://github.com/aevstiel/DelioFox) by [Aevstiel](https://github.com/aevstiel)
- Discord Theme: [Eris Discord](https://github.com/Aevstiel/eris) by [Aevstiel](https://github.com/aevstiel)

## Extensions

- Workspace Blur: [Blur My Shell](https://github.com/aunetx/blur-my-shell) by [Aurélien Hamy](https://github.com/aunetx)
- Window Open/Close Animations: [Burn My Windows](https://github.com/Schneegans/Burn-My-Windows) by [Simon Schneegans](https://github.com/Schneegans)
- Panel Clipboard: [Clipboard History](https://github.com/SUPERCILEX/gnome-clipboard-history) by [Alex Saveau](https://github.com/SUPERCILEX)
- QR from Clipboard: [ClipQR](https://github.com/drien/gnome-shell-extension-clipqr) by [Adrien Delessert](https://github.com/drien)
- Window Moving Animations: [Windows Effect](https://github.com/hermes83/compiz-windows-effect) by [hermes83](https://github.com/hermes83)
- Reboot into Different OS: [Custom Reboot](https://github.com/Nova1545/gnome-shell-extension-customreboot) by [Nova](https://github.com/Nova1545)
- Dock: [Dash to Dock](https://github.com/micheleg/dash-to-dock) by [Michele Gaio](https://github.com/micheleg)
- Clock and Weather Widgets: [Desktop Widgets](https://gitlab.com/AndrewZaech/azclock) by [Andrew Zaech](https://gitlab.com/AndrewZaech)
- Application Switcher: [Fly-Pie](https://github.com/Schneegans/Fly-Pie) by [Simon Schneegans](https://github.com/Schneegans)
- Logo on Panel: [Logo Menu](https://github.com/Aryan20/Logomenu) by [Aryan Kaushik](https://github.com/Aryan20)
- Song and Artist on Panel: [Mpris Label](https://github.com/Moon-0xff/gnome-mpris-label) by [Moon-0xff](https://github.com/Moon-0xff)
- Drives on Panel: [Removable Drive Menu](https://extensions.gnome.org/extension/7/removable-drive-menu) by [fmuellner](https://extensions.gnome.org/accounts/profile/fmuellner)
- Rounded Corners: [Rounded Window Corners](https://github.com/flexagoon/rounded-window-corners) by [Pavel Zolotarevskiy](https://github.com/flexagoon)
- Weather on Panel: [Weather or Not](https://gitlab.gnome.org/somepaulo/weather-or-not) by [Paulo Fino](https://gitlab.gnome.org/somepaulo)

## 🖼️ Gallery
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Screenshot1.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Screenshot2.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Screenshot3.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Screenshot4.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Screenshot5.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Screenshot6.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Bootloader.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Lockscreen1.png">
<img width=800 src="https://github.com/Aevstiel/Lycia-Dots/blob/main/Screenshots/Lockscreen2.png">

# 🛠️ Instructions

## GDM Theme
GDM is notoriously difficult to customize, you need to make a .xml file then compile stuff and it's a whole mess. I've already done most of the hard word, the rest should be easy.

### Download the gnome shell theme

It is available here [here](https://github.com/Aevstiel/Lycia-Dots/tree/main/.themes/Lycia/gnome-shell)

### Backup the original gnome theme

```sudo cp /usr/share/gnome-shell/gnome-shell-theme.gresource /usr/share/gnome-shell/gnome-shell-theme-original.gresource```

### Copy the gresources file into the gnome shell directory

After changing directory to the gnome shell one you just downloaded, execute this command:

```sudo cp ./gnome-shell-theme.gresource /usr/share/gnome-shell```

### Logout and enjoy

If following these steps doesn't work, kindly submit and issue and I will get back as soon as possible.
