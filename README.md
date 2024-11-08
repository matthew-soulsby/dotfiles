# dotfiles

Just a repo to store dotfiles and other configuration.

## Dependencies

### zsh

* oh-my-zsh
* pure
* tmux

### nvim

* lazygit
* ripgrep
* rsync

## Installation - Stow

From the root of this repository, run: 
* Common: `stow --dotfiles -d common -t ~ .`
* Linux: `stow --dotfiles -d linux -t ~ .`
* WSL: `stow --dotfiles -d wsl -t ~ .`

