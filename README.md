# Hyprland Dotfiles

Minimal yet powerful configuration for [Hyprland](https://github.com/hyprwm/Hyprland). This setup aims for a simple aesthetic and an efficient workflow.

## Getting Started

1. Install dependencies
   ```bash
   sudo pacman -S hyprland wofi waybar hyprlock hyprpaper hypridle kitty nautilus pavucontrol starship neovim neofetch wireplumber power-profiles-daemon
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

## Screenshots
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f3a23670-8f2b-423b-aaa1-dea2c53f4a5c" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/8c5f9a66-b475-486b-b209-ac9d3bb99989" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/31c7e98a-15dc-4f9e-87a8-413793702dbd" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/20bab13a-ee23-48f0-bae3-75b1ad26a069" />



<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d33d325f-2d3d-4916-9529-e43bffb37a82" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/fa7832bd-9bc6-402c-84ff-e9c3e55e8a9a" />


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/482438f8-afde-4832-a599-ea033be034d1" />


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/cccc56d6-d446-4ffc-b66f-2e1e5fbaea8e" />

<img width="1364" height="768" alt="image" src="https://github.com/user-attachments/assets/5af76f7e-1959-4ab0-ab10-754930fa1a02" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9e514234-5bf6-4a0d-9b0f-08245fafd1f7" />

