# Neovim config highly inspired by ThePrimeagen

## Dependencies
- ripgrep
- gcc
- npm (node 18+)
- python3
- python3 venv
- golang
- rust
- fd
- wget

## Initial setup
- clone / export / simlink this repo to `$HOME/.config/nvim`
- open lua/wouter/packer.lua with nvim
  - `:so`
  - `:PackerSync`
  - Wait for plugins to download
- Download your LSPs by typing `:Mason` and selecting / installing them

