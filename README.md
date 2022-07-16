## The files 

Configuration files in (\*)NIX systems usually start with a 'dot'.  Examples include directories and files like: `~/.config`,  `~/.zshrc` and `~/.gitconfig`. These files can exist at any location but are usually found in your home directory `~/` and in the [XDG_CONFIG_HOME](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) directory, which by convention is usually `~/.config`.

## Keeping a history of content changes

This portion is optional, but recommended so that you easily tag, comment and find past historical changes.  This repository uses [git](https://git-scm.com/), as such it utilises a central location for all my current configurations. These central files are linked to the home directory structure using a local dotfile management strategy discussed below.

## Backing up and sharing

This repository uses [github](www.github.com) to keep a central copy of my configuration and associated git repository.  This central location allows for easy sharing between machines with a simple `git clone`.  I prefer to clone this repository locally into `~/.dotfiles`.

## Local dotfile manangement strategy

Given the configuration files are centrally located and not in expected locations in home directory, we need a tool and a strategy to make them useable on a machine.  
This repo uses [Dotter](https://github.com/SuperCuber/dotter) a rust based config driven dotfile manager.

## You have options to do this differently

Multiple strategies have been devised to backup, share, and keep change history of files.  If this repos approach is not to your liking you can find alternative [tools](https://github.com/webpro/awesome-dotfiles#tools) and [tutorials](https://github.com/webpro/awesome-dotfiles#articles) to accomplish the same ends but in different ways.

### Other resources

* [Video](https://www.youtube.com/watch?v=r_MpUP6aKiQ)
* [Getting Started With Dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789)
* [The best way to store your dotfiles: A bare Git repository ](https://www.atlassian.com/git/tutorials/dotfiles)
* [Managing Your Dotfiles](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)
* [Awesome Dot files](https://github.com/webpro/awesome-dotfiles)
* Symantic Link Manager like [GNU-Stow](https://www.gnu.org/software/stow/)
