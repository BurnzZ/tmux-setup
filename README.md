Check out the rest of my dotfiles here:
* [https://github.com/BurnzZ/dotfiles](https://github.com/BurnzZ/dotfiles)
* [https://github.com/BurnzZ/tmux-setup](https://github.com/BurnzZ/tmux-setup)

These people inspired almost all of my dotfiles:
* [Paul Irish](https://github.com/paulirish/dotfiles)
* [Cătălin Mariș](https://github.com/alrra/dotfiles)
* [Tom Vincent](https://github.com/tlvince/vim-config)
* [Mathias Bynens](https://github.com/mathiasbynens/dotfiles)

# Installation

```sh
git clone https://github.com/BurnzZ/tmux-setup.git ~/.tmux
ln -fs ~/.tmux/.tmux.conf ~/.tmux.conf

cd ~/.tmux
git submodule update --init
```

You can update all plugins using:
`git submodule foreach git pull origin master`

# Plugins

Currently, here are the plugins currently installed:

* [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)
* [Tmux Prefix Highlight](https://github.com/tmux-plugins/tmux-prefix-highlight)
* [Tmux Online Status](https://github.com/tmux-plugins/tmux-online-status)

# Notes

Make sure you are using `tmux 1.9` or higher.
