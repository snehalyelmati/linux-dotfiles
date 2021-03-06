# dotfiles

My Linux dotfiles, I use [Arch](https://archlinux.org/) btw.

_Note: if you want to give these dotfiles a try, you should fork this repo, review the code and remove things you don't want or need. Use at your own risk._

- [`i3WM`](https://github.com/i3/i3) - A tiling window manager for X11.
- [`tmux`](https://github.com/tmux/tmux) - A terminal multiplexer, runs on OpenBSD, FreeBSD, NetBSD, Linux, macOS and Solaris.
- [`zsh`](https://github.com/zsh-users/zsh) - Highly customizable interactive login shell and command interpreter for shell scripting.
  - [`Oh My Zsh`](https://github.com/ohmyzsh/ohmyzsh) - Oh My Zsh is an open source, community-driven framework for managing your zsh configuration.
  - [`p10k`](https://github.com/romkatv/powerlevel10k) - Powerlevel10k is a theme for Zsh.
  - [`autosuggestions`](https://github.com/zsh-users/zsh-autosuggestions) - Fish-like fast/unobtrusive autosuggestions for zsh.
  - [`syntax-highlighting`](https://github.com/zsh-users/zsh-syntax-highlighting) - Fish shell-like syntax highlighting for Zsh.
- [`neovim`](https://neovim.io/) - Hyperextensible Vim-based text editor.
  - [`nvim-lspconfig`](https://github.com/neovim/nvim-lspconfig) - Quickstart configurations for the Nvim LSP client.
  - [`telescope`](https://github.com/nvim-telescope/telescope.nvim) - A highly extensible fuzzy finder built with Lua.
  - [`treesitter`](https://tree-sitter.github.io/tree-sitter/) - Tree-sitter is a parser generator tool and an incremental parsing library, built with Rust.
  - [`nvim-tree`](https://github.com/kyazdani42/nvim-tree.lua) - A file explorer tree written in Lua.
  - [`null-ls`](https://github.com/jose-elias-alvarez/null-ls.nvim) - null-ls helps to inject LSP diagnostics, code actions, and more via Lua.
  - [`gitsigns`](https://github.com/lewis6991/gitsigns.nvim) - Super fast git decorations for neovim implemented purely in lua/teal.
  - [`gruvbox-material`](https://github.com/sainnhe/gruvbox-material) - A modified version of gruvbox colorscheme with softer colors.
- [`vim`](https://github.com/vim/vim) - Vim is a free and open-source text editor which is highly configurable, built to make creating and changing any kind of text very efficient.
  - [`ctrlp`](https://github.com/ctrlpvim/ctrlp.vim) - Full path fuzzy file, buffer, mru, tag, ... finder for Vim.
  - [`YouCompleteMe`](https://github.com/ycm-core/YouCompleteMe) - A code-completion engine for Vim.
  - [`vim-airline`](https://github.com/vim-airline/vim-airline) - A customizable statusbar/tabline for Vim.
  - [`gruvbox`](https://github.com/morhetz/gruvbox) - A retro color theme for Vim.
- [`alacritty`](https://github.com/alacritty/alacritty) - A fast, cross-platform, OpenGL terminal emulator. Supported platforms: BSD, Linux, macOS and Windows.
- [`ranger`](https://github.com/ranger/ranger) - A VIM-inspired filemanager for the console.
- [`picom`](https://github.com/yshui/picom/tree/next) - A standalone compositor for X11.
- [`redshift`](https://github.com/jonls/redshift) - Redshift adjusts the color temperature of your screen according to your surroundings.
- [`pfetch`](https://github.com/dylanaraps/pfetch) - A minimal system information tool written in POSIX sh.

## Screenshots

![tmux.png](./images/tmux.png)

![nvim.png](/images/nvim.png)

## Description

- [`.config`](./.config) - consists of configuration files for Neovim, Alacritty, i3WM, picom, ranger and Redshift.
- [`.p10k.zsh`](./.p10k.zsh) - Powerlevel10k theme config file for zsh.
- [`.tmux.conf`](./.tmux.conf) - tmux configuration file.
- [`.vimrc`](./.vimrc) - vim configuration file.
- [`.zshrc`](./.zshrc) - zsh configuration file.
- [`20-intel.conf`](./20-intel.conf) - config file to fix screen-tearing on Arch based systems, to be used with [xf86-video-intel](https://gitlab.freedesktop.org/xorg/driver/xf86-video-intel) driver.
- [`backup.sh`](./backup.sh) - simple script to make a copy of all the specified dotfiles.
- [`blurlock`](./blurlock), [`i3exit`](./i3exit) - [Manjaro](https://manjaro.org/)'s lockscreen scripts for i3.
- [`.scripts`](./.scripts) - custom scripts for easy access, including tmux scripts.

## Installation

- Copy contents of `.config/` to `~/.config`.
- Copy `.p10k.zsh`, `.tmux.conf`, `.vimrc` and `.zshrc` to `~/`.
- Copy `blurlock` and `i3exit` to `/usr/bin`.
- Copy fonts from `fonts` folder to `/usr/share/fonts` or `~/.local/share/fonts`.
- Copy contents of `.scripts/` to `~/.scripts`.
- For `20-intel.conf` refer to this section in the [ArchWiki](https://wiki.archlinux.org/title/intel_graphics#Xorg_configuration).

## References

- [Mathias???s dotfiles](https://github.com/mathiasbynens/dotfiles)
- [Webpro's dotfiles](https://github.com/webpro/awesome-dotfiles)
- [Neovim from Scratch by chris@machine](https://www.youtube.com/playlist?list=PLhoH5vyxr6Qq41NFL4GvhFp-WLd5xzIzZ)
