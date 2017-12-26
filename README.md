# dot_tmux
My tmux config

## Installation
### Manual installation
This repository is prepared to be used together with gnu stow. See [Brandon Invergo's
explanation](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
on how to use it. In short

```
mkdir ~/dotfiles
cd ~/dotfiles
git clone https://github.com/fmauch/dot_tmux.git
stow dot_tmux
```

This will create symlinks for the dotfiles specified in ```dot_tmux``` relative to your home folder.

### Automatic installation
I personally use a shell script to install all my dotfiles at once that clones multiple repositories
and calls stow on them. You find it in my [dotfiles repository](https://github.com/fmauch/dotfiles).
The installation would then be

```
cd
git clone https://github.com/fmauch/dotfiles
cd dotfiles
# You might want to have a look at this to see which modules this will pull.
./install.sh
```
