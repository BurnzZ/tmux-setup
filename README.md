Check out the rest of my dotfiles here:
* [https://github.com/BurnzZ/dotfiles](https://github.com/BurnzZ/dotfiles)
* [https://github.com/BurnzZ/vim-setup](https://github.com/BurnzZ/vim-setup)

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

Make sure you are using `tmux 3.0` or higher.
