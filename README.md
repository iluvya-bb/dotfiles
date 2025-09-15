# 🛠️ Dotfiles — Coding Utilities Only

These are my personal **dotfiles** focused exclusively on improving my coding workflow. They’re designed for speed, consistency, and portability across machines.  

> ⚠️ **Note:** These configs are optimized for my environment (Arch Linux). Feel free to fork and adapt them to your own setup.

---

## ✨ Features
- 🧰 **Developer Utilities** — Preconfigured tools for fast coding (e.g., Neovim/AstroNvim, tmux, zsh).  
- 📦 **Language Tooling** — Ready-to-use settings for JavaScript/TypeScript, React, Flutter, and AWS development.  
- ⚡ **Productivity Enhancements** — Aliases, keybindings, and helpers to make everyday tasks smoother.  
- 🧹 **Minimalist & Clean** — Only essential coding utilities—no unrelated desktop or system tweaks.

---

## 📂 Structure

---

## 🚀 Installation
Clone the repository and create **symbolic links**:  
```bash
# Clone the repo
git clone https://github.com/iluvya-bb/dotfiles.git ~/dotfiles

# Use symlinks to apply configs
ln -s ~/dotfiles/nvim ~/.config/nvim
ln -s ~/dotfiles/zsh ~/.config/zsh
ln -s ~/dotfiles/tmux ~/.config/tmux
ln -s ~/dotfiles/git/.gitconfig ~/.gitconfig

