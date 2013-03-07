Prezto — Instantly Awesome Zsh
==============================

(Fork for installing it on ubuntu and customise it)

Installation
------------

    sudo apt-get install git zsh
    cd
    git clone --recursive https://github.com/j-d/prezto.git .zprezto

    rm .zlogin
    rm .zlogout
    rm .zpreztorc
    rm .zprofile
    rm .zshenv
    rm .zshrc
    ln -s ./.zprezto/runcoms/zlogin .zlogin
    ln -s ./.zprezto/runcoms/zlogout .zlogout
    ln -s ./.zprezto/runcoms/zpreztorc .zpreztorc
    ln -s ./.zprezto/runcoms/zprofile .zprofile
    ln -s ./.zprezto/runcoms/zshenv .zshenv
    ln -s ./.zprezto/runcoms/zshrc .zshrc
    zsh

Maybe:

    chsh -s /bin/zsh
