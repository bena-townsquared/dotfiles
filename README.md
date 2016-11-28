# dotfiles

## Installing

* [install the latest MacVim binary][install-macvim]
* install oh-my-zsh
* run this command:
    ``` bash
    for f in .*
    do
      ln -s `pwd`/$f ~/$f
    done
    ```

[install-macvim]: https://github.com/macvim-dev/macvim
