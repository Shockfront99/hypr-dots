# Hyprland Dotfiles

Minimal yet powerful configuration for [Hyprland](https://github.com/hyprwm/Hyprland). This setup aims for a simple aesthetic and an efficient workflow.

## Getting Started

1. Install dependencies
   ```bash
   sudo pacman -S hyprland wofi waybar hyprlock hyprpaper hypridle kitty thunar pavucontrol starship neovim neofetch wireplumber power-profiles-daemon nwg-look gnome-themes-extra
   yay -S wlogout
   ```
   You can use any AUR helper of your choice
   
2. Clone the repo
   ```bash
   git clone https://github.com/Shockfront99/hypr-dots/ ~/.config/hypr-dots
   ```
3. Backup your existing configuration files
   ```bash
   cp -r ~/.config ~/config.backup  
4. Copy the files
   ```bash
   cp -r ~/.config/hypr-dots/config/hypr ~/.config/
   cp -r ~/.config/hypr-dots/config/kitty ~/.config/
   cp -r ~/.config/hypr-dots/config/neofetch ~/.config/
   cp -r ~/.config/hypr-dots/config/nvim ~/.config/
   cp -r ~/.config/hypr-dots/config/waybar ~/.config/
   cp -r ~/.config/hypr-dots/config/wlogout ~/.config/
   cp -r ~/.config/hypr-dots/config/wofi ~/.config/
   cp -r ~/.config/hypr-dots/config/xdg-desktop-portal ~/.config/
   cp -r ~/.config/hypr-dots/config/starship.toml ~/.config/
   ```
5. Install [Lualine](https://github.com/nvim-lualine/lualine.nvim) and [Tokyonight](https://github.com/folke/tokyonight.nvim).
6. Configure your shell to use starship by 
   adding this to the end of ~/.bashrc:
   ```bash
   eval "$(starship init bash)"
   ```
   Add this to the end of ~/.config/fish/config.fish:
   ```bash
   starship init fish | source
   ```
   Add this to the end of .zshrc:
   ```bash
   eval "$(starship init zsh)"
   ```
7. Set your GTK theme to Adwaita-dark
<img width="1316" height="671" alt="image" src="https://github.com/user-attachments/assets/3589a321-3d65-4b0f-bf58-cd3195de9f96" />



## Screenshots
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f3a23670-8f2b-423b-aaa1-dea2c53f4a5c" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/feaa19e1-d915-4ee7-aada-71ac33a34879" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ff550dce-bc00-439b-8bbb-a8bc02c01f2f" />
<img width="1367" height="769" alt="image" src="https://github.com/user-attachments/assets/969879a5-b26a-4517-9b76-bf1361fec60c" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/20bab13a-ee23-48f0-bae3-75b1ad26a069" />
