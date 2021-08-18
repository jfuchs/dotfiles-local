my dotfiles
===================
I use [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles) as the
foundation of my personal configuration. These files are the `.local`
modifications that build on top of the foundation.

Install
-------

Install Thoughtbot's dotfiles:

    git clone git://github.com/thoughtbot/dotfiles.git
    env RCRC=$HOME/dotfiles/rcrc rcup

Then clone mine:

    git clone git://github.com/geoffharcourt/dotfiles.git ~/dotfiles-local

And re-run rcup to link:

    rcup


This will create symlinks for config files in your home directory from
Thoughtbot's dotfiles and my local customizations.

You can safely run `rcup` multiple times to update:

    rcup

Credits
-------

- https://github.com/thoughtbot/dotfiles
- https://github.com/geoffharcourt/dotfiles-local
- https://github.com/silverlyra/dotfiles