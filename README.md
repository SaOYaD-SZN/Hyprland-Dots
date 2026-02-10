<div align="center">

# 🌟 Hyprland Dotfiles

### *A Premium Arch Linux Rice with Hyprland Compositor*

<p align="center">
  <img src="https://img.shields.io/github/stars/SaOYaD123/Hyprland-Dots?style=for-the-badge&logo=starship&color=C9CBFF&logoColor=D9E0EE&labelColor=302D41" alt="stars">
  <img src="https://img.shields.io/github/forks/SaOYaD123/Hyprland-Dots?style=for-the-badge&logo=git&color=F28FAD&logoColor=D9E0EE&labelColor=302D41" alt="forks">
  <img src="https://img.shields.io/github/license/SaOYaD123/Hyprland-Dots?style=for-the-badge&logo=opensourceinitiative&color=ABE9B3&logoColor=D9E0EE&labelColor=302D41" alt="license">
  <img src="https://img.shields.io/github/last-commit/SaOYaD123/Hyprland-Dots?style=for-the-badge&logo=github&color=96CDFB&logoColor=D9E0EE&labelColor=302D41" alt="last commit">
  <img src="https://img.shields.io/github/issues/SaOYaD123/Hyprland-Dots?style=for-the-badge&logo=gitbook&color=DDB6F2&logoColor=D9E0EE&labelColor=302D41" alt="issues">
</p>

<p align="center">
  A meticulously crafted collection of configuration files for <b>Hyprland</b> on Arch Linux,<br>
  featuring custom AGS widgets, beautiful themes, and a fully integrated desktop experience.<br>
  <i>Built with 98.3% Lua and CSS for maximum customization.</i>
</p>

</div>

---

## 🎯 Features at a Glance

<table>
<tr>
<td width="50%">

### 💎 **Premium Experience**
- 🖥️ Hyprland Wayland compositor
- 🎨 Custom AGS (Aylur's GTK Shell) widgets
- 🌈 Dynamic color schemes with Wallust
- ✨ Beautiful animations and effects

</td>
<td width="50%">

### 🛠️ **Fully Configured**
- ⚡ Optimized Neovim setup (Lua)
- 📊 Customized Waybar & Swaync
- 🎭 Multiple theme options
- 📁 Complete icon & font configs

</td>
</tr>
</table>

---

## 📑 Table of Contents

- [✨ Showcase](#-showcase)
- [📋 Prerequisites](#-prerequisites)
- [🎯 What's Included](#-whats-included)
- [🚀 Quick Start](#-quick-start)
- [📦 Installation](#-installation)
- [⚙️ Configuration](#️-configuration)
- [🎨 Customization](#-customization)
- [⌨️ Keybindings](#️-keybindings)
- [🔧 Troubleshooting](#-troubleshooting)
- [🤝 Contributing](#-contributing)
- [🙏 Acknowledgments](#-acknowledgments)
- [📝 License](#-license)
- [📬 Contact](#-contact)

---

## ✨ Showcase

<div align="center">

### *Experience the Beauty of Hyprland*

<img src="review/0.png" alt="Main Desktop" width="800">
<p><i>Main desktop with AGS widgets and custom Waybar</i></p>

<img src="review/1.png" alt="System Overview" width="800">
<p><i>System monitoring and workflow</i></p>

</div>

<details>
<summary><b>📸 View More Screenshots</b></summary>

<br>

<table>
  <tr>
    <td width="50%">
      <img src="review/2.png" alt="Screenshot 2">
      <p align="center"><i>Terminal & Development Setup</i></p>
    </td>
    <td width="50%">
      <img src="review/3.png" alt="Screenshot 3">
      <p align="center"><i>Application Launcher</i></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="review/4.png" alt="Screenshot 4">
      <p align="center"><i>Notification Center</i></p>
    </td>
    <td width="50%">
      <img src="review/5.png" alt="Screenshot 5">
      <p align="center"><i>System Monitors</i></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="review/6.png" alt="Screenshot 6">
      <p align="center"><i>File Manager Integration</i></p>
    </td>
    <td width="50%">
      <img src="review/7.png" alt="Screenshot 7">
      <p align="center"><i>Lock Screen</i></p>
    </td>
  </tr>
</table>

</details>

---

## 📋 Prerequisites

Before installing these dotfiles, ensure your system meets the following requirements:

### 🖥️ **System Requirements**
- **OS**: Arch Linux (or Arch-based distribution)
- **Display Server**: Wayland
- **Compositor**: Hyprland (latest version recommended)

### 📦 **Required Packages**

<details>
<summary><b>Core Dependencies</b></summary>

```bash
# Compositor & Core
hyprland hyprpaper hypridle hyprlock

# Shell & Terminal
zsh kitty

# Widgets & Bar
ags
waybar
swaync (notification daemon)

# Application Launcher
rofi-wayland

# System Utilities
btop          # System monitor
cava          # Audio visualizer
fastfetch     # System info
wallust       # Color scheme generator

# Theme Components
kvantum
qt5ct qt6ct
nwg-look
gtk3

# Media & Extras
spicetify-cli  # Spotify customization
ghostty        # Alternative terminal emulator (optional)

# Note: Oh My Zsh and Powerlevel10k are installed separately (see Installation section, Step 5)
```
</details>

### 🔧 **Optional But Recommended**
- **Fonts**: Nerd Fonts (JetBrainsMono, FiraCode)
- **Icon Pack**: Papirus or similar
- **File Manager**: Thunar, Nautilus, or Dolphin
- **Browser**: Firefox/Chromium with Vencord for Discord

---

## 🎯 What's Included

This repository contains a comprehensive set of configurations:

### 📂 **Configuration Files**

<table>
<tr>
<td width="50%">

#### 🎨 **Hyprland Ecosystem**
- `hypr/` - Hyprland compositor config
  - `hyprland.conf` - Main configuration
  - `hypridle.conf` - Idle daemon
  - `hyprlock.conf` - Lock screen
  - `hyprpaper.conf` - Wallpaper daemon

#### 🔮 **AGS Widgets**
- `ags/` - Custom JavaScript widgets
  - Dashboard widgets
  - System monitors
  - Media controls
  - Custom modules

</td>
<td width="50%">

#### 🖥️ **Terminal & Shell**
- `.zshrc` - Zsh configuration
- `.p10k.zsh` - Powerlevel10k theme
- `kitty/` - Terminal emulator
- `nvim/` - Neovim (Lua configs)

#### 🎭 **Themes & Appearance**
- `waybar/` - Status bar (CSS)
- `swaync/` - Notification center
- `rofi/` - App launcher themes
- `wlogout/` - Logout menu styles
- `Kvantum/` - Qt theme engine
- `.themes/` - GTK themes
- `.icons/` - Icon packs

</td>
</tr>
</table>

### 🖼️ **Additional Resources**
- **aesthetic-wallpapers/** - Curated wallpaper collection (100+ high-quality images)
- **Font configurations** - Optimized font rendering
- **Color schemes** - Pre-configured wallust palettes

---

## 🚀 Quick Start

<div align="center">
<i>For experienced users who know what they're doing</i>
</div>

```bash
# Clone the repository
git clone https://github.com/SaOYaD123/Hyprland-Dots.git ~/Hyprland-Dots
cd ~/Hyprland-Dots

# Note: The rest of this guide assumes you cloned to ~/Hyprland-Dots
# If you used a different path, adjust the commands accordingly

# Backup your current configs (important!)
mkdir -p ~/dotfiles_backup
cp -r ~/.config ~/dotfiles_backup/
cp ~/.zshrc ~/.p10k.zsh ~/dotfiles_backup/ 2>/dev/null

# Deploy configurations
cp -r .config/* ~/.config/
cp .zshrc .p10k.zsh ~/
cp -r .themes .icons ~/

# Set zsh as default shell
chsh -s $(which zsh)

# Restart Hyprland
hyprctl reload
```

---

## 📦 Installation

### Step 1: Install Dependencies

<details>
<summary><b>📥 Install All Required Packages</b></summary>

```bash
# Update system
sudo pacman -Syu

# Install Hyprland and core components
sudo pacman -S hyprland hyprpaper hypridle hyprlock

# Install shell and terminal
sudo pacman -S zsh kitty

# Install AGS and widgets
yay -S ags

# Install bar and notifications
sudo pacman -S waybar
yay -S swaync

# Install utilities
sudo pacman -S rofi-wayland btop fastfetch
yay -S cava wallust

# Install theme components
sudo pacman -S kvantum qt5ct qt6ct gtk3
yay -S nwg-look

# Install fonts (recommended)
sudo pacman -S ttf-jetbrains-mono-nerd ttf-firacode-nerd

# Install optional packages
yay -S spicetify-cli ghostty
```
</details>

### Step 2: Clone Repository

```bash
git clone https://github.com/SaOYaD123/Hyprland-Dots.git ~/Hyprland-Dots
cd ~/Hyprland-Dots

# Note: The rest of this guide assumes you cloned to ~/Hyprland-Dots
# If you used a different path, adjust the commands accordingly
```

### Step 3: Backup Existing Configuration

**⚠️ IMPORTANT**: Always backup your current dotfiles before proceeding!

```bash
# Create backup directory
mkdir -p ~/dotfiles_backup

# Backup existing configurations
cp -r ~/.config ~/dotfiles_backup/config_backup_$(date +%Y%m%d_%H%M%S)
cp ~/.zshrc ~/dotfiles_backup/.zshrc.backup 2>/dev/null
cp ~/.p10k.zsh ~/dotfiles_backup/.p10k.zsh.backup 2>/dev/null
```

### Step 4: Install Dotfiles

```bash
# Copy configuration files
cp -r .config/* ~/.config/

# Copy shell configurations
cp .zshrc ~/.zshrc
cp .p10k.zsh ~/.p10k.zsh

# Copy themes and icons
cp -r .themes ~/
cp -r .icons ~/

# Optional: Copy wallpapers
cp -r aesthetic-wallpapers ~/Pictures/
```

### Step 5: Configure Shell

```bash
# Install Oh My Zsh (if not already installed)
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install Powerlevel10k theme
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# Set zsh as default shell
chsh -s $(which zsh)
```

### Step 6: Apply Configuration

```bash
# Source the new zsh configuration
source ~/.zshrc

# Restart Hyprland (or logout and login again)
hyprctl reload
```

---

## ⚙️ Configuration

### 🎨 **Hyprland Settings**

The main Hyprland configuration is located at `~/.config/hypr/hyprland.conf`

Key configuration sections:
- **Monitors**: Display configuration
- **Input**: Keyboard/mouse settings
- **Animations**: Motion and transition effects
- **Window Rules**: Application-specific behaviors
- **Keybindings**: Keyboard shortcuts

### 📊 **AGS Widgets**

AGS configuration is in `~/.config/ags/`

- `config.js` - Main AGS configuration
- `user_options.js` - User-customizable options
- `variables.js` - Global variables
- `modules/` - Custom widget modules

### 🎭 **Theme Customization**

Edit these files to customize appearance:
- **Waybar**: `~/.config/waybar/style.css`
- **Rofi**: `~/.config/rofi/config.rasi`
- **Kitty**: `~/.config/kitty/kitty.conf`
- **Notifications**: `~/.config/swaync/style.css`

---

## 🎨 Customization

### 🖼️ **Changing Wallpapers**

```bash
# Using hyprpaper (recommended)
# Edit ~/.config/hypr/hyprpaper.conf
preload = ~/Pictures/aesthetic-wallpapers/your-wallpaper.png
wallpaper = ,~/Pictures/aesthetic-wallpapers/your-wallpaper.png
```

### 🌈 **Color Schemes**

This setup uses Wallust for dynamic color scheme generation:

```bash
# Generate color scheme from wallpaper
wallust run ~/Pictures/wallpaper.png

# Apply to all applications
wallust cs
```

### ⚙️ **AGS Widget Configuration**

Edit `~/.config/ags/user_options.js` to customize:
- Widget positions
- Update intervals
- Enabled/disabled modules
- Custom commands

### 🔤 **Fonts**

To change fonts, edit:
- **GTK**: `~/.config/gtk-3.0/settings.ini`
- **Waybar**: `~/.config/waybar/config.jsonc`
- **Kitty**: `~/.config/kitty/kitty.conf`

---

## ⌨️ Keybindings

### 🔑 **Essential Shortcuts**

<details>
<summary><b>View All Keybindings</b></summary>

#### Window Management
- `SUPER + Q` - Close active window
- `SUPER + F` - Toggle fullscreen
- `SUPER + V` - Toggle floating mode
- `SUPER + [1-9]` - Switch to workspace 1-9
- `SUPER + Shift + [1-9]` - Move window to workspace 1-9

#### Application Launchers
- `SUPER + Return` - Terminal (Kitty)
- `SUPER + D` - Application launcher (Rofi)
- `SUPER + E` - File manager
- `SUPER + B` - Browser

#### System Controls
- `SUPER + L` - Lock screen
- `SUPER + Shift + E` - Power menu
- `SUPER + Shift + R` - Reload Hyprland

#### Screenshots
- `Print` - Screenshot area
- `SUPER + Print` - Screenshot full screen
- `SUPER + Shift + S` - Screenshot window

</details>

> 💡 **Tip**: See `~/.config/hypr/hyprland.conf` for complete keybinding list

---

## 🔧 Troubleshooting

### ❓ Common Issues

<details>
<summary><b>AGS widgets not showing</b></summary>

```bash
# Check AGS is running
pgrep ags

# Restart AGS
pkill ags
ags &
```
</details>

<details>
<summary><b>Waybar not loading</b></summary>

```bash
# Check for errors
waybar -l debug

# Restart Waybar
pkill waybar
waybar &
```
</details>

<details>
<summary><b>Font icons not displaying</b></summary>

```bash
# Install required fonts
sudo pacman -S ttf-jetbrains-mono-nerd ttf-font-awesome

# Refresh font cache
fc-cache -fv
```
</details>

<details>
<summary><b>Zsh configuration issues</b></summary>

```bash
# Reset to default
mv ~/.zshrc ~/.zshrc.backup
cp ~/Hyprland-Dots/.zshrc ~/.zshrc

# Source the configuration
source ~/.zshrc
```
</details>

### 📚 **Getting Help**

If you encounter issues:
1. Check the [Issues](https://github.com/SaOYaD123/Hyprland-Dots/issues) page
2. Read Hyprland [documentation](https://wiki.hyprland.org/)
3. Join the Hyprland [Discord](https://discord.gg/hyprland)

---

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how you can help:

### 🌟 **Ways to Contribute**

- 🐛 Report bugs and issues
- 💡 Suggest new features or improvements
- 📝 Improve documentation
- 🎨 Share your customizations
- 🔧 Submit pull requests

### 📋 **Contribution Guidelines**

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### 💬 **Code of Conduct**

Please be respectful and constructive. We're all here to learn and improve!

---

## 🙏 Acknowledgments

This configuration wouldn't be possible without these amazing projects:

### 🎯 **Core Technologies**
- [Hyprland](https://hyprland.org/) - Dynamic tiling Wayland compositor
- [AGS](https://github.com/Aylur/ags) - Aylur's GTK Shell for custom widgets
- [Waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar
- [Rofi](https://github.com/davatorium/rofi) - Window switcher and app launcher

### 🛠️ **Tools & Utilities**
- [Wallust](https://codeberg.org/explosion-mental/wallust) - Color scheme generator
- [Swaync](https://github.com/ErikReider/SwayNotificationCenter) - Notification daemon
- [Kvantum](https://github.com/tsujan/Kvantum) - SVG-based Qt theme engine
- [Powerlevel10k](https://github.com/romkatv/powerlevel10k) - Zsh theme
- [Neovim](https://neovim.io/) - Hyperextensible Vim-based text editor

### 🎨 **Inspiration**
- The r/unixporn community
- Various dotfiles repositories on GitHub
- Hyprland showcase submissions

### 💝 **Special Thanks**
- All contributors and testers
- The Arch Linux community
- Everyone who starred this repository

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License - Copyright (c) 2025 SaOYaD

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```

### ⚖️ **What This Means**
- ✅ Use for personal or commercial projects
- ✅ Modify and distribute
- ✅ Private use
- ❌ No warranty provided
- ❌ Author not liable

---

## 📬 Contact

<div align="center">

### 💬 **Get in Touch**

<p>
  <a href="https://github.com/SaOYaD123/Hyprland-Dots/issues">
    <img src="https://img.shields.io/badge/Issues-Report%20Bug-red?style=for-the-badge&logo=github" alt="Issues">
  </a>
  <a href="https://github.com/SaOYaD123/Hyprland-Dots/pulls">
    <img src="https://img.shields.io/badge/Pull%20Requests-Contribute-blue?style=for-the-badge&logo=github" alt="Pull Requests">
  </a>
</p>

**Have questions or suggestions?**
- 🐛 [Report a Bug](https://github.com/SaOYaD123/Hyprland-Dots/issues/new)
- 💡 [Request a Feature](https://github.com/SaOYaD123/Hyprland-Dots/issues/new)
- 💬 [Start a Discussion](https://github.com/SaOYaD123/Hyprland-Dots/discussions)

</div>

---

<div align="center">

### ⭐ **Show Your Support**

If you found this helpful, please consider giving it a ⭐!

### 🚀 **Made with ❤️ for the Linux community**

*Arch Linux • Hyprland • Wayland*

<img src="https://img.shields.io/badge/Arch%20Linux-btw-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white" alt="Arch Linux">
<img src="https://img.shields.io/badge/Hyprland-Wayland-5865F2?style=for-the-badge&logo=wayland&logoColor=white" alt="Hyprland">

---

**[⬆ Back to Top](#-hyprland-dotfiles)**

</div>
