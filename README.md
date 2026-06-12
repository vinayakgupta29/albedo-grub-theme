# albedo-grub-theme
Albedo theme for GRUB Bootloader

# Albedo Grub Theme
A custom GRUB theme designed to provide a clean and visually appealing boot experience.

## Overview

`Albedo Grub Theme` is a custom GRUB theme that enhances the appearance of the boot menu while maintaining readability and usability.

The theme is designed to integrate seamlessly with modern Linux desktop setups and can be customized further to match your preferred aesthetic.

---

## Features

* Custom GRUB menu styling
* Modern visual design
* Improved menu readability
* Custom fonts and colors
* Easy installation and modification
* Compatible with GRUB 2

---

## Preview

<!-- ### Main Menu

> Add screenshot here

![GRUB Main Menu](./screenshots/main-menu.png)

### Alternate View

> Add screenshot here

![GRUB Alternate View](./screenshots/alternate-view.png)

---
-->

## Background

Current background:


![theme](./background.png)

---

## Requirements

* GRUB 2
* Linux distribution using GRUB as the bootloader

---

## Installation

Clone the repository:

```bash
git clone https://github.com/vinayakgupta29/albedo-grub-theme.git
```

Move the theme directory into GRUB's themes directory:

```bash
sudo mkdir -p /boot/grub/themes
sudo cp -r albedo-grub-theme /boot/grub/themes/
```

Edit your GRUB configuration:

```bash
sudo nano /etc/default/grub
```

Add or modify:

```bash
GRUB_THEME="/boot/grub/themes/albedo-grub-theme/theme.txt"
```

Regenerate the GRUB configuration:

### Arch Linux

```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

### Debian / Ubuntu

```bash
sudo update-grub
```

Reboot to see the changes.

---

## Directory Structure

```text
albedo-grub-theme/
├── theme.txt
├── background.png
├── fonts/
├── icons/
└── assets/
```

---

## Customization

You can customize:

* Background image
* Fonts
* Colors
* Menu positioning
* Icons
* Selection highlights

Most visual settings can be modified through the `theme.txt` file.


---

## Compatibility

Tested on:

* Arch Linux

Additional distribution testing is welcome.

---

## Roadmap

* [ ] Additional background variants
* [ ] Higher resolution assets
* [ ] Alternative color schemes
* [ ] Improved accessibility options
* [ ] Multi-theme releases

---

## Contributing

Contributions, bug reports, and suggestions are welcome.

Feel free to open an issue or submit a pull request.

---

## License

Specify your preferred license here.


* GPLv3


---

## Credits

* GRUB Project
* Contributors and testers
* Artwork credits (if applicable)

