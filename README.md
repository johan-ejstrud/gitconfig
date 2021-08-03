# gitconfig
My `.gitconfig` files that I use across different working environments.
The `.gitconfig` file is shared between all working environments.
The `.gitconfig_local` file can be costumised for each working environment.

# Installation
1. Clone repository to computer, or install Dropbox where a copy is also kept in `Dropbox/repo/gitconfig/.gitconfig`.
1. Find `.gitconfig` file on computer (usually `~/.gitconfig`, check with `git config --list --show-origin`).
1. In bash (Linux) run   
   ```
   rm ~/.gitconfig
   ln -s ~/path/to/dropbox/or/repo/gitconfig/.gitconfig ~/.gitconfig
   cp ~/path/to/dropbox/or/repo/gitconfig/.gitconfig_local ~/.gitconfig_local
   ```
   If a symbolic link can't be created (Windows) simply copy the file. This has to be repeated every time there are updates.
1. Modify `~/.gitconfig_local` for the curren system.
