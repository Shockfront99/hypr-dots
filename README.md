# Hyprland Dotfiles

Minimal yet powerful configuration for [Hyprland](https://github.com/hyprwm/Hyprland) on Wayland. This setup aims for a simple aesthetic, and an efficient workflow tailored to my taste.

## Getting Started

1. Install dependencies
   ```bash
   sudo pacman -S hyprland wofi waybar hyprlock hyprpaper kitty nautilus starship neovim neofetch
   yay -S wlogout
   ```
   You can use any AUR helper of your choice
   
2. Clone the repo
   ```bash
   git clone https://github.com/Shockfront99/hypr-dots/ ~/.config/hypr-dots
   ```
   
3. Copy the files
   ```bash
   cp -r ~.config/hypr-dots/config/hypr ~/.config/hypr
   cp -r ~.config/hypr-dots/config/kitty ~/.config/kitty
   cp -r ~.config/hypr-dots/config/neofetch ~/.config/neofetch
   cp -r ~.config/hypr-dots/config/nvim ~/.config/nvim
   cp -r ~.config/hypr-dots/config/waybar ~/.config/waybar
   cp -r ~.config/hypr-dots/config/wlogout ~/.config/wlogout
   cp -r ~.config/hypr-dots/config/wofi ~/.config/wofi
   ```
