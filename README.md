# Hyprland Dotfiles

My dotfiles for [Hyprland](https://github.com/hyprwm/Hyprland).

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
3. Backup your existing configuration files (unless using symlinks)
   ```bash
   cp -r ~/.config ~/config.backup  
4. Copy the files (or use symlinks)
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
5. Install [Lualine](https://github.com/nvim-lualine/lualine.nvim) and [e-ink](https://github.com/e-ink-colorscheme/e-ink.nvim).
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
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/bbcc5e72-7097-49f5-9631-7695a0b695cd" />

<img width="1366" height="767" alt="image" src="https://github.com/user-attachments/assets/5abf64a2-d1ae-47ee-b765-7f81251f8a13" />

<img width="1366" height="764" alt="image" src="https://github.com/user-attachments/assets/ed153976-fc09-4400-8070-afd0bfe59768" />
<img width="1366" height="766" alt="image" src="https://github.com/user-attachments/assets/bbe5e2b0-68f8-49de-b33b-163f902ab987" />
<img width="1360" height="768" alt="image" src="https://github.com/user-attachments/assets/de746adc-5605-4711-8429-9f8b07066f38" />





