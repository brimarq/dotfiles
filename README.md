# Dotfiles

These are based upon [Mathias Byens' dotfiles](https://github.com/mathiasbynens/dotfiles), adapted for my use on macOS. 

## Installation  

WARNING: Backup your original `~/.bashrc` and `~/.bash_profile` BEFORE installing!

1. Clone this repo
2. Make `./install` executable with `chmod +x ./install`
3. Run `. ./install` 
4. Run `source ~/.bash_profile` to load the dotfiles.  

Running `./install` will `rsync` the contents of `./src` into `$HOME`.  

Rename the `./dotfiles/.bash_profile_partials/.private.example` file to `.private` for anything that you want to avoid committing to git. 
