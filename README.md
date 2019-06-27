# System-Toolbox

==============

I'm going to use this repo as a place for me to put all the random files that I use to tweak my computer.

Feel free to borrow/take whatever you like from here just remember I offer no guarantees about it.

This is going to be mostly high-level convenience tweaks, since I'm not really a system guy.

## Bash

The bash directory contains my `.terminalTweaks` extension to the `.bashrc`. You need to `source` it from your local rc or `.bash_profile` file. This is now a **legacy** offering, as I've migrated to using ZSH for everything.

## ZSH

The zsh directory contains the `.terminalTweaks` I've collected in Bash, wrapped up as an [Oh My ZSH](https://ohmyz.sh/) plugin called `zack`. To add it, copy the `zack` directory into your `~/.oh-my-zsh/plugins/` directory and follow the instructions in the README.

## OSX

The osx directory contains OS tweaks I find necessary. The main one here is the Sort & Unique automator workflow. If you open it in Automator, you should be able to save it as a system extension, which will allow you to sort and unique text system-wide from the right click menu.
