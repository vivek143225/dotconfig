#PARU
sudo pacman -S --needed base-devel

git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si



paru -S hyprland alacritty waybar wlogout nwg-drawer nwg-look blueberry ncdu hyprpaper network-manager-applet blueman firefox
polkit-gnome papirus-icon-theme wev

#Theming
[(https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)
