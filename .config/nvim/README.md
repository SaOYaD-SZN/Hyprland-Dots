<div align="center">

# ✨ Neovim Configuration

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=8AADF4&center=true&vCenter=true&random=false&width=600&lines=A+Modern+Neovim+Setup;Blazingly+Fast+%E2%9A%A1;Fully+Customizable+%F0%9F%8E%A8;Built+with+Love+%F0%9F%92%99" alt="Typing SVG" />

<p align="center">
  <img src="https://img.shields.io/github/stars/SaOYaD-SZN/Neovim-dots?style=for-the-badge&logo=starship&color=C9CBFF&logoColor=D9E0EE&labelColor=302D41" alt="stars">
  <img src="https://img.shields.io/github/last-commit/SaOYaD-SZN/Neovim-dots?style=for-the-badge&logo=github&color=FFB1C8&logoColor=D9E0EE&labelColor=302D41" alt="last commit">
  <img src="https://img.shields.io/github/repo-size/SaOYaD-SZN/Neovim-dots?style=for-the-badge&logo=databricks&color=B5E8E0&logoColor=D9E0EE&labelColor=302D41" alt="repo size">
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-showcase">Showcase</a> •
  <a href="#-structure">Structure</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-credits">Credits</a>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

## ✨ Features

<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║                    🚀 POWERED BY MODERN TOOLS                  ║
╚═══════════════════════════════════════════════════════════════╝
```

</div>

<table>
<tr>
<td width="50%">

### 🎯 Core Features

- 🔥 **LSP Integration** - Powered by `nvim-lspconfig`
- ⚡ **Blazing Fast** - Optimized with `lazy.nvim`
- 🎨 **Theme Switcher** - Dynamic themes via `themery.nvim`
- 📸 **Code Screenshots** - Beautiful captures with `nvim-silicon`
- 💾 **Session Persistence** - Never lose your work
- 🔍 **Fuzzy Finding** - Lightning-fast with Telescope

</td>
<td width="50%">

### 🛠️ Development Tools

- 📦 **Mason Integration** - Easy LSP/linter management
- 🧪 **Testing Suite** - Integrated with `neotest`
- 🎯 **Smart Completion** - Powered by `blink.cmp`
- 🌳 **Treesitter** - Advanced syntax highlighting
- 🔧 **DAP Support** - Full debugging capabilities
- 🤖 **AI Copilot** - GitHub Copilot integration

</td>
</tr>
</table>

### 🌐 Language Support

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

## 📸 Showcase

<div align="center">

<table>
<tr>
<td width="50%">
<img src="./images/buffer-neotree-markdown.png" alt="Buffer & Neotree" />
<p align="center"><b>📁 File Explorer & Buffer Management</b></p>
</td>
<td width="50%">
<img src="./images/cmp-colorPicker.png" alt="Completion & Color Picker" />
<p align="center"><b>🎨 Smart Completion & Color Picker</b></p>
</td>
</tr>
<tr>
<td width="50%">
<img src="./images/Dashboard.png" alt="Dashboard" />
<p align="center"><b>🏠 Beautiful Dashboard</b></p>
</td>
<td width="50%">
<img src="./images/Telescope.png" alt="Telescope" />
<p align="center"><b>🔭 Powerful Fuzzy Finder</b></p>
</td>
</tr>
<tr>
<td width="50%">
<img src="./images/copilot-cmp.png" alt="Copilot Integration" />
<p align="center"><b>🤖 AI-Powered Suggestions</b></p>
</td>
<td width="50%">
<img src="./images/testing-terminal.png" alt="Testing & Terminal" />
<p align="center"><b>🧪 Integrated Testing & Terminal</b></p>
</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

## 📂 Structure

<details>
<summary><b>🗂️ Click to expand file structure</b></summary>

<br>

```
📂 ~/.config/nvim
├── 📂 lua
│   ├── 📂 config
│   │   ├── 🔧 autocmds.lua          # Auto commands
│   │   ├── ⌨️  keymaps.lua           # Key mappings
│   │   ├── 💤 lazy.lua              # Plugin manager config
│   │   └── ⚙️  options.lua           # Neovim options
│   ├── 📂 custom
│   │   └── 🔭 telescope-preview.lua # Custom telescope config
│   └── 📂 plugins
│       ├── 🤖 ai.lua                # AI integrations
│       ├── 📝 annotations.lua       # Code annotations
│       ├── 💾 auto-save.lua         # Auto-save functionality
│       ├── 🔗 autopairs.lua         # Auto-pair brackets
│       ├── 🏷️  autotag.lua           # Auto-close HTML tags
│       ├── 📑 bufferline.lua        # Buffer management
│       ├── 💡 completions.lua       # Completion engine
│       ├── 📍 context.lua           # Context awareness
│       ├── 🎯 cursor-highlight.lua  # Cursor highlighting
│       ├── 🐛 dap.lua               # Debugging
│       ├── 🗄️  database.lua          # Database tools
│       ├── ⚡ flash.lua             # Fast navigation
│       ├── 🌿 git.lua               # Git integration
│       ├── 🔍 grug-far.lua          # Search & replace
│       ├── 🎯 harpoon.lua           # Quick file navigation
│       ├── 🎨 icons.lua             # Icon support
│       ├── 🖼️  img-clip.lua          # Image clipboard
│       ├── 📏 indent-guides.lua     # Indent visualization
│       ├── 📚 lazydev.lua           # Lazy development
│       ├── 🌐 live-server.lua       # Live web server
│       ├── 🔄 live-share.lua        # Collaboration
│       ├── 🔧 lsp.lua               # LSP configuration
│       ├── 📖 markdown.lua          # Markdown support
│       ├── 📄 mdx.lua               # MDX support
│       ├── 🎪 mini-textobjects.lua  # Text objects
│       ├── 🔱 neogit.lua            # Git interface
│       ├── 🧪 neotest.lua           # Testing framework
│       ├── 🌳 neotree.lua           # File explorer
│       ├── 🎭 noice.lua             # UI enhancements
│       ├── 💫 nvchad.lua            # NvChad utilities
│       ├── 💾 persistance.lua       # Session management
│       ├── 🦀 rust.lua              # Rust tooling
│       ├── 📸 screenshots.lua       # Code screenshots
│       ├── 🍿 snacks.lua            # Utility functions
│       ├── ✂️  snippets.lua          # Code snippets
│       ├── 📊 statusline.lua        # Status bar
│       ├── 🎨 tailwind.lua          # Tailwind CSS tools
│       ├── 🔭 telescope.lua         # Fuzzy finder
│       ├── 🌈 theme.lua             # Theme configuration
│       ├── ✅ todo-comments.lua     # TODO highlights
│       ├── 🌲 treesitter.lua        # Syntax parsing
│       ├── 🚨 trouble.lua           # Diagnostics list
│       ├── 💬 ts-comments.lua       # Smart comments
│       ├── ⏮️  undotree.lua          # Undo history
│       ├── 🔀 vim-tmux-navigation.lua # Tmux integration
│       ├── ❓ which-key.lua         # Keybinding helper
│       └── 📋 yanky.lua             # Yank management
├── 🚀 init.lua                      # Entry point
├── 🔒 lazy-lock.json                # Plugin lockfile
└── 📖 README.md                     # This file
```

</details>

<div align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

## 📋 Requirements

<div align="center">

| Tool | Version | Required | Purpose |
|:----:|:-------:|:--------:|:-------:|
| <img src="https://neovim.io/logos/neovim-mark-flat.png" width="20"> **Neovim** | ≥ 0.9.0 | ✅ | Core Editor |
| <img src="https://imagemagick.org/image/wizard.png" width="20"> **ImageMagick** | Latest | ✅ | Image Support |
| <img src="https://www.python.org/static/favicon.ico" width="20"> **Python** | Latest | ✅ | Image Plugin |
| <img src="https://git-scm.com/favicon.ico" width="20"> **Git** | ≥ 2.40.0 | ✅ | Version Control |
| <img src="https://www.nerdfonts.com/assets/img/nerd-fonts-logo.svg" width="20"> **Nerd Font** | Latest | ✅ | Icons & Glyphs |
| 🖼️ **Silicon** | Latest | ⚠️ | Screenshots |
| 🔗 **GNU Stow** | Latest | ⚠️ | Symlink Manager |
| 🐙 **GitHub CLI** | Latest | ⚠️ | GitHub Integration |

</div>

> [!NOTE]
> Items marked with ⚠️ are optional but recommended for full functionality.

<div align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

## 🚀 Installation

<div align="center">

### Quick Start in 4 Steps

</div>

<table>
<tr>
<td width="50%">

#### 1️⃣ Clone Repository

```bash
git clone https://github.com/SaOYaD-SZN/Neovim-dots.git
cd Neovim-dots
```

</td>
<td width="50%">

#### 2️⃣ Backup Existing Config

```bash
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

</td>
</tr>
<tr>
<td width="50%">

#### 3️⃣ Create Symlinks

```bash
# Using GNU Stow (recommended)
stow neovim

# Or manually
ln -s $(pwd) ~/.config/nvim
```

</td>
<td width="50%">

#### 4️⃣ Launch Neovim

```bash
nvim
```

<p><i>Plugins will install automatically!</i></p>

</td>
</tr>
</table>

<div align="center">

### 🎉 That's it! Enjoy your new Neovim setup!

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

## ⚙️ Customization

<details>
<summary><b>🎨 How to customize this configuration</b></summary>

<br>

### Changing Theme

```lua
-- lua/plugins/theme.lua
-- Modify the theme configuration or use the built-in theme switcher
-- Press <leader>th to open theme picker
```

### Adding New Plugins

```lua
-- Create a new file in lua/plugins/
-- Example: lua/plugins/my-plugin.lua
return {
  "author/plugin-name",
  config = function()
    -- Your configuration here
  end
}
```

### Custom Keymaps

```lua
-- lua/config/keymaps.lua
-- Add your custom keybindings
vim.keymap.set("n", "<leader>cc", ":YourCommand<CR>", { desc = "Description" })
```

### LSP Configuration

```lua
-- lua/plugins/lsp.lua
-- Add or modify LSP servers in the ensure_installed table
```

</details>

<div align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

## 🎯 Key Features Breakdown

<details>
<summary><b>🔍 Click to see detailed feature explanations</b></summary>

<br>

### 🤖 AI Integration
- GitHub Copilot support for intelligent code suggestions
- Context-aware completions
- Multi-line suggestions

### 🧪 Testing Framework
- Run tests directly from Neovim
- Real-time test output
- Support for multiple testing frameworks

### 📸 Code Screenshots
- Create beautiful code screenshots with `nvim-silicon`
- Customizable themes and backgrounds
- Perfect for sharing code snippets

### 🎨 Theme Switcher
- Switch between multiple themes on the fly
- Preview themes before applying
- Persistent theme selection

### 🔧 LSP & Linting
- Automatic LSP server installation
- Real-time diagnostics
- Code actions and refactoring
- Format on save

</details>

<div align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

## 🙏 Credits

<div align="center">

<table>
<tr>
<td align="center" width="33%">
<img src="https://github.com/folke.png" width="100px;" alt="folke"/><br />
<sub><b><a href="https://github.com/folke">@folke</a></b></sub><br />
<sub>Creator of <a href="https://github.com/LazyVim/LazyVim">💤 LazyVim</a></sub><br />
<sub>Inspiration & Learning Source</sub>
</td>
<td align="center" width="33%">
<img src="https://github.com/siduck.png" width="100px;" alt="siduck"/><br />
<sub><b><a href="https://github.com/siduck">@siduck</a></b></sub><br />
<sub>Creator of <a href="https://github.com/NvChad/NvChad">NvChad</a></sub><br />
<sub>Amazing Plugins & Inspiration</sub>
</td>
<td align="center" width="33%">
<img src="https://neovim.io/logos/neovim-mark-flat.png" width="100px;" alt="Neovim"/><br />
<sub><b>Neovim Team</b></sub><br />
<sub>For creating this amazing editor</sub><br />
<sub>& the incredible community</sub>
</td>
</tr>
</table>

### 💎 Special Thanks

A huge shoutout to all the plugin authors and contributors who make Neovim the powerful editor it is today. This configuration wouldn't be possible without their hard work and dedication.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

## 📊 Statistics

<div align="center">

![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)
![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)
![LazyVim](https://img.shields.io/badge/LazyVim-Powered-blue?style=for-the-badge)

<img src="https://github-readme-stats.vercel.app/api/pin/?username=SaOYaD-SZN&repo=Neovim-dots&theme=tokyonight&hide_border=true&bg_color=1A1B27&title_color=8AADF4&text_color=CAD3F5&icon_color=C6A0F6" />

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
</div>

## 📝 License

<div align="center">

This configuration is free and open source. Feel free to use, modify, and share!

<img src="https://forthebadge.com/images/badges/built-with-love.svg" />
<img src="https://forthebadge.com/images/badges/powered-by-coffee.svg" />

### ⭐ If you find this useful, please consider giving it a star!

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<p align="center">
Made with 💙 by <a href="https://github.com/SaOYaD-SZN">SaOYaD-SZN</a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=170&section=footer&fontSize=42&fontColor=fff&animation=twinkling" />

</div>
