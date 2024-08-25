#PARU
sudo pacman -S --needed base-devel

git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si



paru -S zsh wget hyprland alacritty waybar wlogout nwg-drawer nwg-look blueberry ncdu hyprpaper network-manager-applet blueman firefox
polkit-gnome papirus-icon-theme wev lohit-fonts ttf-meslo-nerd thunar

#Theming
[(https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)
