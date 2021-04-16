# Warna-GTK-Theme
වර්ණ is a theme for GNOME desktops which is like a combination of Sweet and WhiteSur GTK themes

![main](https://github.com/RDPerera/Warna-GTK-Theme/blob/main/Screen%20Shots/A.png?raw=true)
# Installation is easy!
## Install Tweak Tool
Tweaks is designed for GNOME Shell but can be used in other desktops. A few features will be missing when Tweaks is run on a different desktop

The first step is to make sure that we have the universe repository enabled on our Ubuntu system
```
sudo add-apt-repository universe
```
Once ready, execute the following command to install Tweak Tool on your Ubuntu system
```
sudo apt install gnome-tweak-tool
```
## Use the stable package
You can choose the compressed file compiled in stable version and unzip it to the theme folder ~/.themes under the user folder.

## Compile from source
You can run ./install.sh to install the default WhiteSur GTK theme pack which includes GNOME Shell (Pantheon), Cinnamon, XFWM (XFCE), Metacity, and Plank themes.

# Other recommended stuffs
## Papirus-Icon-Theme
![main](https://github.com/RDPerera/Warna-GTK-Theme/blob/main/Screen%20Shots/O1.png?raw=true)

**You can install Papirus from our official PPA:(For UBUNTU DERIVATIONS)**
```
sudo add-apt-repository ppa:papirus/papirus
sudo apt-get update
sudo apt-get install papirus-icon-theme
or download .deb packages from here.
```
**NOTE**: Now the daily builds of the papirus-icon-themes package are placed in ppa:papirus/papirus-dev.
**OFFICIAL**: https://github.com/PapirusDevelopmentTeam/papirus-icon-theme

## Whitesur Wallpaper
![main](https://github.com/RDPerera/Warna-GTK-Theme/blob/main/Screen%20Shots/O2.png?raw=true)
**4K** : https://github.com/vinceliuice/WhiteSur-kde/blob/master/wallpaper/WhiteSur_4k.png?raw=true

**HD** : https://github.com/vinceliuice/WhiteSur-kde/blob/master/wallpaper/WhiteSur.png?raw=true

## Blyr - Blur Effect to GNOME Shell UI elements.
![main](https://github.com/RDPerera/Warna-GTK-Theme/blob/main/Screen%20Shots/Q3.png?raw=true)
**Manual Instalation**
```
git clone https://github.com/yozoon/gnome-shell-extension-blyr.git
cd gnome-shell-extension-blyr/
make local-install
```

Now just restart the Shell and enable the extension.
To remove the extension just run:

```make local-uninstall```

**Install blyr using the official repository:** [extensions.gnome.org](https://extensions.gnome.org/extension/1251/blyr/)
