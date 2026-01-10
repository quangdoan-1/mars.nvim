# ☄️ mars.nvim - Simplified Neovim and tmux Setup

[![Download](https://img.shields.io/badge/Download%20Mars.nvim-v1.0-blue.svg)](https://github.com/quangdoan-1/mars.nvim/releases)

Mars.nvim offers a seamless configuration for Neovim and tmux. It enhances your coding experience with AI tools and boosts productivity without the hassle of complex setups.

## 🚀 Getting Started

Follow these steps to get Mars.nvim up and running on your machine.

### 📥 Download & Install

1. Visit the [Releases page](https://github.com/quangdoan-1/mars.nvim/releases) to download the latest version. 

2. Open your terminal.

3. Run the following commands:

   ```bash
   git clone https://github.com/MarsWang42/mars.nvim.git ~/.config/mars.nvim
   cd ~/.config/mars.nvim
   chmod +x install.sh
   ./install.sh
   ```

The install script will:
- Create symlinks in your `~/.config/nvim` and `~/.config/tmux` directories.
- Back up any existing configuration files with timestamps.

### 🛠️ Prerequisites

Before installing Mars.nvim, you need to have the following:

- **Neovim** version 0.10 or later (0.11+ is recommended)
- **Git** installed
- **A Nerd Font** for icons
- **Node.js** for Language Server Protocol (LSP) functionalities
- **ripgrep** for better search capabilities in Telescope

## ✨ Features

Mars.nvim focuses on a modern development experience. Here are some of its key features:

### 🤖 AI-Powered Development

| Plugin | Description | Key Bindings |
|--------|-------------|--------------|
| **[claudecode.nvim](https://github.com/coder/claudecode.nvim)** | Integrates Claude Code for AI-assisted coding | `<leader>c` |

### 🎨 Customization Options

Easily adjust your setup to fit your needs:
- Change colorschemes to match your preferences.
- Modify key bindings for quicker access to functions.
  
### 🔍 Search and Navigation

Mars.nvim enhances productivity by allowing:
- Instant code search using ripgrep 
- Efficient navigation within files and projects

### 🌟 Community Support

Our community is open for suggestions and improvements:
- Get involved by reporting issues or submitting pull requests on GitHub.

## 🔧 Configuration

To customize your setup:

1. Open your Neovim configuration file located at `~/.config/nvim/init.vim` or use `init.lua` if you prefer.
2. Change settings according to the installation requirements and personal preferences.

### 🗂️ Backing Up

Mars.nvim automatically backs up your existing configurations while installing. You will find these backups in the same directory as your original files. 

## 🔗 Useful Links

- [Official GitHub Repository](https://github.com/MarsWang42/mars.nvim)
- [AI Tools Documentation](https://github.com/MarsWang42/mars.nvim/wiki)
- [Submission Guidelines](https://github.com/MarsWang42/mars.nvim/blob/main/CONTRIBUTING.md)

## 📞 Support

If you encounter any issues, please raise them on the [Issues page](https://github.com/MarsWang42/mars.nvim/issues) for assistance. 

For additional queries, feel free to contact the community through our chat platform linked in the repository.

Your journey to a better coding experience starts with Mars.nvim! Download and explore today.