# my vim configuration file
![vim logo](https://www.dropbox.com/s/exmyr8i4llyq6zq/Screenshot%202017-09-24%2011.05.32.png?raw=1)

Inspired by existing vimrc settings:
- https://github.com/sheerun/vimrc

Config is incrementally updated to get convenient and most powerful vim experience.

## plugins
I'm using [vim-plug](https://github.com/junegunn/vim-plug) - a minimalist Vim plugin manager.

## vim unix installation
- [Download plug.vim](https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim) and put it in the "autoload" directory.
```sh
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
- copy .vimrc to your `$HOME` folder.
- reload .vimrc and `:PlugInstall` to install plugins.
