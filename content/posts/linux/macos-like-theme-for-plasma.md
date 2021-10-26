---
title: "macOS-like theme for Plasma"
summary: "This is the theme I use with Plasma"
date: "2021-10-25"
categories: ["Linux"]
series: ["Linux"]
weight: 1
aliases: ["/macos-theme"]
tags: ["Linux", "Plasma", "KDE"]
author: "Rushi"
---

![Edna theme](/img/edna-theme.png)

## Guide

### Kvantum

First, make sure you have `kvantum-manager` installed on your distro.

Ubuntu-based:
```bash
sudo add-apt-repository ppa:papirus/papirus
sudo apt update
sudo apt install qt5-style-kvantum qt5-style-kvantum-themes
```

Arch-based:
```bash
sudo pacman -S kvantum-qt5
```

Afterwards, make sure you set the "Application Style" to "kvantum-dark".

### Edna Theme

The Edna theme can be installed via the System Settings -> Global Theme.

The Kvantum theme can be obtained [here](https://www.pling.com/p/1367055/).

After that, simply enable the Edna theme in the System Settings and set the Kvantum theme in Kvantum Manager!

### Icons

Personally, I like the `Inverse-blue-dark` icons the most with this theme (can be installed via the System Settings -> Icons), but it's ultimately up to you which icons to choose for this theme.

### Widgets

You'll need to install the "Better inline clock" widget (right click on the desktop -> Add Widgets -> Get New Widgets).

### Latte Dock

Finally, make sure you have `latte-dock` installed on your distro.

Ubuntu-based:
```bash
sudo apt install latte-dock
```

Arch-based:
```bash
sudo pacman -S latte-dock
```

Simple! Now, just download [this](http://to-do) config for Latte, and import it in the settings (right click on an empty part of the dock, and choose "Configure Latte").

All done, phew!

### Conclusion

I think this theme is quite nice for getting the most screen real-estate with a simple and clean macOS-like appearance.

If you'd like to see more Linux guides, or more content in general, make sure to check the Archive out!