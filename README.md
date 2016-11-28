# dotfiles

## Installing

- clone this to ~/dev/dotfiles
- [install powerline fonts][install-powerline-fonts]
- [install the latest MacVim binary][install-macvim]
- install oh-my-zsh
- create symbolic links to dotfiles:

    ``` bash
    for f in .*
    do
      ln -s `pwd`/$f ~/$f
    done
    ```
- clone repos

    ``` bash
    git clone https://github.com/vim-airline/vim-airline.git .janus/03-vim-airline
    git clone https://github.com/chriskempson/tomorrow-theme.git
    ```

[install-macvim]: https://github.com/macvim-dev/macvim
[install-powerline-fonts]: https://github.com/powerline/fonts#installation
