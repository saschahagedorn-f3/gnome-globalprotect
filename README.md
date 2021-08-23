# Gnome GlobalProtect

Displays an icon in the menu bar which opens the GlobalProtect UI when clicked. The icon will be grayed out when no VPN connection exists. The extension checks for the VPN connectivity status every 5 seconds. 

## Installation

Clone this repo to the extensions folder:

```
mkdir -p ~/.local/share/gnome-shell/extensions
git clone https://github.com/saschahagedorn-f3/gnome-globalprotect ~/.local/share/gnome-shell/extensions/gnomeglobalprotect@sascha.hagedorn.form3.tech
```

Enable the extension:

```
gnome-extensions enable gnomeglobalprotect@sascha.hagedorn.form3.tech
```

Restart the GNOME shell with <kbd>Alt</kbd> + <kbd>F2</kbd> and type `r`.