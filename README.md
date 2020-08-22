# Dot Files

This repo contains the common dotfiles I use

## `.*rc`

These dotfiles are for shell customization, in case you don't know that... The shell-specific `.zshrc` and `.bashrc` files are set to also source the distro-specific dot file (for now just `.archrc`).

* `.zshrc` - My ZSH config, complete with external `ZSH2000` theme and some OhMyZ.sh plugins.
* `.distrorc` - Script that finds out the distro and sources a specific distro's associated `.rc` file (e.g. `arch.rc`)
* `.commonrc` - My personal config additions that are generic across any distro.
* `.archrc` - My personal config additions specialized for arch-based distros.
* `.ubunturc` - My personal config additions specialized for ubuntu-based distros.
