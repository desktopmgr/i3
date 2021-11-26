## i3  
  
i3 is a dynamic tiling window manager  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/desktopmgr/i3/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install i3 libnotify-bin catfish slimlock acpi-support wireless-tools gtk2-engine-murrine xfce4-terminal firefox xfce4-power-manager volumeicon-alsa xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome conky polybar xbindkeys tint2
```  

Fedora Based:

```shell
yum install i3 xfce4-power-manager gtk2-murrine-engine acpid wireless-tools xfce4-terminalfirefox  volumeicon xscreensaver policykit-1-gnome gnome-settings-daemon network-manager-gnome polybar xbindkeys tint2
```  

Arch Based:

```shell
pacman -S i3 gtk-engine-murrine xfce4-power-manager acpi wireless-tools xfce4-terminal firefox volumeicon xscreensaver polkit-gnome gnome-settings-daemon network-manager-applet conky tint2 xbindkeys polybar
```  

MacOS:  

```shell
brew install
```
  
```shell
mv -fv "$HOME/.config/i3" "$HOME/.config/i3.bak"
git clone https://github.com/desktopmgr/i3 "$HOME/.config/i3"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/i3" target="_blank" rel="noopener noreferrer">i3 wiki</a>  |  
  <a href="https://i3wm.org" target="_blank" rel="noopener noreferrer">i3 site</a>
</p>  
