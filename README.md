# Dot Files

This repo contains the common dotfiles I use

## `.*rc`

These dotfiles are for shell customization, in case you don't know that... The shell-specific `.zshrc` and `.bashrc` files are set to also source the distro-specific dot file.

* `.zshrc` - My ZSH config, complete with external [`ZSH2000`][0] theme and some OhMyZ.sh plugins.
* `.distrorc` - Script that finds out the distro and sources a specific distro's associated `.rc` file (e.g. `arch.rc`)
* `.commonrc` - My personal config additions that are generic across any distro.
  * `.commonrc` references a program called pride, which is a script that will print a predetermined set of colors across the top of the terminal window. It uses full RGB color values so if your terminal doesn't support that then it likely won't look very good. The script is a modified version of the script found [here][1]. I have my colors set to the agender flag :3
* `.archrc` - My personal config additions specialized for arch-based distros.
* `.ubunturc` - My personal config additions specialized for ubuntu-based distros.

[0]: https://github.com/maverick9000/zsh2000
[1]: https://gist.github.com/boringcactus/18503c17b4307bb57f9dda1284410f4d
