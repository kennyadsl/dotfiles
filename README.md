kennyadsl dotfiles
===============

Inspired by [croaky](https://github.com/croaky/dotfiles).


Requirements
------------

Install [Homebrew](https://brew.sh/) with

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"


Install [rcm](https://github.com/mike-burns/rcm).

    brew tap thoughtbot/formulae
    brew install rcm

Install
-------

Clone onto your laptop:

    mkdir -p ~/Code/kennyadsl/dotfiles
    git clone git://github.com/kennyadsl/dotfiles.git ~/Code/kennyadsl/dotfiles

Install:

    env RCRC=$HOME/kennyadsl/dotfiles/rcrc rcup

This will create symlinks for config files in your home directory.

You can safely run `rcup` multiple times to update.

What's in it?
-------------

Read the code :P
